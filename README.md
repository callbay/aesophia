# aesophia

This is the __sophia__ compiler for the æternity system which compiles contracts written in __sophia__ to [FATE](https://github.com/aeternity/protocol/blob/master/contracts/fate.md) instructions.

The compiler is currently being used three places
 - [The command line compiler](https://github.com/aeternity/aesophia_cli)
 - [The HTTP compiler](https://github.com/aeternity/aesophia_http)
 - In [Aeternity node](https://github.com/aeternity/aeternity) tests

## Documentation

* [Smart Contracts on aeternity Blockchain](https://github.com/aeternity/protocol/blob/master/contracts/contracts.md).
* [Sophia Documentation](docs/sophia.md).
* [Sophia Standard Library](docs/sophia_stdlib.md).

## Versioning

Versioning should follow the [semantic versioning](https://semver.org/spec/v2.0.0) guidelines. Id est, given a version number MAJOR.MINOR.PATCH, increment the:

- MAJOR version when you make incompatible API changes
- MINOR version when you add functionality in a backwards compatible manner
- PATCH version when you make backwards compatible bug fixes


## Interface Modules

The basic modules for interfacing the compiler:

* [aeso_compiler: the Sophia compiler](./docs/aeso_compiler.md)
* [aeso_aci: the ACI interface](./docs/aeso_aci.md)
