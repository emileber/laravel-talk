## [Lumen](https://lumen.laravel.com/)

> The stunningly fast micro-framework by Laravel.

```php
// Reimagine what you expect...
$app->get('/', function() {
	return ['version' => '5.3']
});

// From your micro-framework...
$app->post('framework/{id}', function($framework) {
	$this->dispatch(new Energy($framework));
});
```

Note:
Alternative légère