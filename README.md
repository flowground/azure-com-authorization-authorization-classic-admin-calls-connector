# ![LOGO](logo.png) AuthorizationManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the AuthorizationManagementClient API (version 2015-07-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/authorization-authorization-ClassicAdminCalls/2015-07-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:20+03:00

## API Description

Role based access control provides you a way to apply granular level policy administration down to individual resources or resource groups. These operations enable you to manage role definitions and role assignments. A role definition describes the set of actions that can be performed on resources. A role assignment grants access to Azure Active Directory users.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets service administrator, account administrator, and co-administrators for the subscription.

*Tags:* `ClassicAdministrators`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

## License

**flow**ground :- Telekom iPaaS / azure-com-authorization-authorization-classic-admin-calls-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
