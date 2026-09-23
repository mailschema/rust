# Contributing

This repository publishes the Rust crate for MailSchema. The protocol schemas are maintained in [`mailschema/mailschema`](https://github.com/mailschema/mailschema); Rust-specific API and packaging changes belong here and must remain compatible with those canonical files.

Run the crate checks before opening a pull request:

```sh
cargo test
cargo package
```

Changes to MAP behavior, shared schemas or Registry records should begin in the [main project repository](https://github.com/mailschema/mailschema/blob/main/CONTRIBUTING.md).

