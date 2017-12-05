## Vues

Sépare la logique de l'application de la logique de présentation.

```php
Route::get('/', function () {
    return view('tasks');
});
```

Une vue est composé d'un ou plusieurs template.

`'tasks'` fait référence à `resources/views/tasks.blade.php`

Note:
- Logique de business
- Passe les données à la vue