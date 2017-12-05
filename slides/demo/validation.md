## Validation

- Plusieurs règles prédéfinies
- Simplification et centralisation de la validation

```php
$validator = Validator::make($request->all(), [
    'name' => 'required|max:255',
]);
```

Note:
Création de classe `Validator`