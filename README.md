# zero2prod

## cargo-watch

```sh
cargo watch -x check -x test -x run
```

## migrate db

```sh
SKIP_DOCKER=true ./scripts/init_db.sh
```

## sqlx-prepare

```sh
cargo sqlx prepare -- --lib
```

## Too many open files

```sh
ulimit -n 10000
```
