## Routage

La gestion des URLs est centralisée.

```text
/my_task_page.php?action=edit&id=23&lang=fr
/fr/task/23
```

```php
// app/Http/routes.php
use App\Task;
use Illuminate\Http\Request;

// Show Task Dashboard
Route::get('/', function () { /* ... */ });

// Add New Task
Route::post('/task', function (Request $request) { /* ... */ });

// Delete Task
Route::delete('/task/{task}', function (Task $task) { /* ... */ });
```

Note:
- Facile à lire et partager
- Ranking SEO
- Pas besoin de RegEx
- Gestion des méthodes HTTP
- Groupage