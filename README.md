# Cloud Storage Providers Initialization

Accepts [microservice instance](https://github.com/makeomatic/mservice) and extends it with methods

`.provider()` -> returns provider from `selectTransport` function passed in configuration

`.providers` -> array of initialized `config.transport` options

Extends `_connectors` of mservice and pushes `provider.connect()` functions there
