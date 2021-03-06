# Cloud Foundry HashiCorp Vault Broker Changelog

## v0.4.0 (Unreleased)
FEATURES:
- [#39](https://github.com/hashicorp/vault-service-broker/pull/39) adds support for application-level secrets engines but also contains a **breaking change** in the format of the JSON returned by the `Bind` call so should be adopted with caution

## v0.3.0 (January 23, 2019)

FEATURES:
- [#37](https://github.com/hashicorp/vault-service-broker/pull/37) adds support for all configuration variables to be provided through CredHub with UAA for CredHub authentication

IMPROVEMENTS:
- Adds functional tests documenting current behavior of the Vault Service Broker
- Adds Travis CI builds

BUG FIXES:
- Resolves [#25](https://github.com/hashicorp/vault-service-broker/issues/25), an extraneous error renewing the Vault token on startup


## v0.2.0 (July 24, 2017)

- Initial Release
- Implements the Bind, Unbind, Provision, and Deprovision calls for the Open Service Broker API
