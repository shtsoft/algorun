# algorun

[![CI][actions-badge]][actions-url]

[actions-badge]: https://github.com/shtsoft/algorun/actions/workflows/ci.yaml/badge.svg
[actions-url]: https://github.com/shtsoft/algorun/actions/workflows/ci.yaml

A test mule for a web service which **securely** runs client algorithms in a configurable and monitorable way.

- security
  * Rust for the [backend](backend)
  * TypeScript for the [frontend](frontend)
  * virtualization on [seL4](https://sel4.systems) and authorization with tokens to enable [capability-based security](http://habitatchronicles.com/2017/05/what-are-capabilities/)

## Deployment

The following two sections describe possibilities to deploy algorun.

### From Source

To deploy algorun from source, first clone the repo.
Then follow then follow the respective installation and usage descriptions of the [backend](backend) and [frontend](frontend).

### Docker

...

## Contributing

If you want to contribute: [CONTRIBUTING](CONTRIBUTING.md).

### Security

For security-related issues see: [SECURITY](SECURITY.md).
