# CLI Argument provider for Figment

This crate is a pretty simple implementation for getting config options from cli arguments.

---

### Usage

CLI Arguments:
```shell
./program --db.name=my-database --host=my-host --port=5432 --user=my-user --password=my-password
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