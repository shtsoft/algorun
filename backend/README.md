# algorun/backend

[![GPL licensed][license-badge]][license-url]

[license-badge]: https://img.shields.io/badge/license-GPL-blue.svg
[license-url]: ./Cargo.toml

The **Rust** backend of [algorun](https://github.com/shtsoft/algorun).

- Rust:
  * safety:
    + thoroughly testet
    + memory-safety: no `unsafe`-code
    + ...

### Installation

Having a clone of the [algorun repo](https://github.com/shtsoft/algorun), generate the algorun binary by running the following commands in the context of the repo top-level:

```console
user@host:~$ cd backend
user@host:~$ cargo build --release
```

Then copy the resulting binary `target/release/algorun` to the appropriate location.

### Usage

To get a usage description just run the app without arguments:

```console
user@host:~$ algorun
```

Typical usage is like:

```console
user@host:~$ algorun --serve /path/to/frontend/dist --ip 1.2.3.4 --port 80
```

The command serves the [frontend](../frontend)-installation `/path/to/frontend/dist` on `1.2.3.4:80`.

## Contributing

If you want to contribute: [CONTRIBUTING](CONTRIBUTING.md).

### Security

For security-related issues see: [SECURITY](../SECURITY.md).
