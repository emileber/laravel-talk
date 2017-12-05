## Gestion de la [cache](https://laravel.com/docs/5.5/cache)

File cache, Redis, Memcached, etc. interchangeable avec une config.

```
'memcached' => [
    [
        'host' => '127.0.0.1',
        'port' => 11211,
        'weight' => 100
    ],
],
```

Note:
- Plusieurs driver (pilote), File par défaut.
- Servir les données plus vite (éviter les opérations coûteuses)