# CLI Argument provider for Figment

This crate is a pretty simple implementation for getting config options from cli arguments.

---

### Usage

CLI Arguments:
```shell
./program --db.name=my-database --db.host=my-host --db.port=5432 --db.user=my-user --db.password=my-password
```

TOML config:
```toml
[db]
name = "my-database"
host = "localhost"
port = 5432
user = "my-user"
password = "my-password"
```
