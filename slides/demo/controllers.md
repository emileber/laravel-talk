## Controlleurs

```bash
php artisan make:controller TaskController
```

```php
public function store(Request $request)
{
    /* ...validation here... */

    $task = new Task(['name' => $request->name]);
    $task->save();

    return redirect('/');
}
```

```php
Route::post('/task', 'TaskController@store');
```

Note:
- Sortir la logique des routes
- Restreindre les responsabilités