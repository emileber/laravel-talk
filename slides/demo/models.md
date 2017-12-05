## Modèle de données Eloquent

[Eloquent](https://laravel.com/docs/5.5/eloquent) est l'ORM (object-relational mapper) de Laravel par défaut.

Un modèle correspond à une table dans la base de données.

```php
use Illuminate\Database\Eloquent\Model;

class Task extends Model { }
```

Pour récupérer les tâches:

```php
Task::orderBy('created_at', 'asc')->get()
```

Note:
- Peut être vide, mais nécessaire.
