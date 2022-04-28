## Failures

28 april 2022 : file_put_contents(Local route):
failed to open stream: No such file or directory

### Solution

```bash
php artisan config:cache
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
