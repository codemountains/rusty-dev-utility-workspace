# Rusty Dev Utility in Workspace

The `div-utility` structure is based on the [Package Layout](https://doc.rust-lang.org/cargo/guide/project-layout.html) as described in [The Cargo Book](https://doc.rust-lang.org/cargo/index.html).

## Cargo run

The `default-members` manifest key is defined in [Cargo.toml](Cargo.toml).

```
% cargo run
Application start!
```

## Cargo run dev-utility commands

Use the `--package` option to specify a binary.

```
% cargo run --package good_morning
Good morning!
```

```
% cargo run --packagehello
Hello!
```

## LICENSE

This project is licensed under the [MIT license](LICENSE).
