# Description
Nextcloud docker compose file.

## Hints
- Add domain to `config/config.php` file
```
...
'trusted_domains' =>
  array (
  0 => 'localhost:8080',
  1 => 'my.domain.name',
  ),
...
```