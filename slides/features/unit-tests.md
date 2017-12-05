## Tests unitaires

Laravel vient avec une configuration par défaut de PHPUnit.

```php
public function testBasicExample()
{
    $response = $this->json('POST', '/user', ['name' => 'Sally']);

    $response
        ->assertStatus(200)
        ->assertJson([
            'created' => true,
        ]);
}
```

Note:
Mocking:

- S'assurer que les fonctions sont appelé, et avec les bons params.