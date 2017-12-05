## Configurations

- En PHP directement dans l'app
- S'écrase avec des variables d'environnement

`config/app.php`

```
    'env' => env('APP_ENV', 'production'),
```

`.env`

```
APP_ENV=debug
```

Note:
- Différent pour chaque environnement
- Pas versionné
- Bonne pratique