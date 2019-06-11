# ![LOGO](logo.png) RecoveryServicesClient **flow**ground Connector

## Description

A generated **flow**ground connector for the RecoveryServicesClient API (version 2016-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/recoveryservices-registeredidentities/2016-06-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:09+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Uploads a certificate for a resource.

*Tags:* `VaultCertificates`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.
* `certificateName` - _required_ - Certificate friendly name.

### Unregisters the given container from your Recovery Services vault.

*Tags:* `RegisteredIdentities`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription Id.
* `api-version` - _required_ - Client Api Version.
* `resourceGroupName` - _required_ - The name of the resource group where the recovery services vault is present.
* `vaultName` - _required_ - The name of the recovery services vault.
* `identityName` - _required_ - Name of the protection container to unregister.

## License

**flow**ground :- Telekom iPaaS / azure-com-recoveryservices-registeredidentities-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
