# externalsecretstore

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

A Helm chart for Kubernetes

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| name | string | `"test-secretstore"` | the secretstore name |
| serviceaccountname | string | `"test-serviceaccount"` | the name of the serviceaccount used to access the key_vault |
| vaulturl | string | `"http://vault.test"` | the url to the azure key_vault |

----------------------------------------------
