## Templates

Le plus proche du navigateur, le HTML généré avec [Laravel Blade](https://laravel.com/docs/5.5/blade).

```html
<tbody>
    @foreach ($tasks as $task)
        <tr>
            <td class="table-text"><div>{{ $task->name }}</div></td>
        </tr>
    @endforeach
</tbody>
```

Compilé en PHP et mis en cache, donc aucun impact sur la performance.

Note:
- PHP est toujours disponible
- Héritage, inclusion, etc.
- Plusieurs raccourcis simple