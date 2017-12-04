## Routage

La gestion des URLs est centralisée.

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
- Pas besoin de RegEx
- Gestion des méthodes HTTP