## Migrations de la base de données

```bash
$ php artisan make:migration create_tasks_table --create=tasks
```

Création d'une table pour les tâches.

```php
public function up()
{
    Schema::create('tasks', function (Blueprint $table) {
        $table->increments('id');
        $table->string('name');
        $table->timestamps();
    });
}
```

Note:
Besoin particulier = RAW SQL