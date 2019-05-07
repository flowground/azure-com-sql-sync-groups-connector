# ![LOGO](logo.png) SqlManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SqlManagementClient API (version 2015-05-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-syncGroups/2015-05-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:13+03:00

## API Description

The Azure SQL Database management API provides a RESTful set of web APIs that interact with Azure SQL Database services to manage your databases. The API enables users to create, retrieve, update, and delete databases, servers, and other entities.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a collection of sync database ids.

*Tags:* `SyncGroups`

#### Input Parameters
* `locationName` - _required_ - The name of the region where the resource is located.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Lists sync groups under a hub database.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Deletes a sync group.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a sync group.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Updates a sync group.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Creates or updates a sync group.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Cancels a sync group synchronization.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a collection of hub database schemas.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Gets a collection of sync group logs.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `startTime` - _required_ - Get logs generated after this time.
* `endTime` - _required_ - Get logs generated before this time.
* `type` - _required_ - The types of logs to retrieve.
    Possible values: All, Error, Warning, Success.
* `continuationToken` - _optional_ - The continuation token for this operation.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Refreshes a hub database schema.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

### Triggers a sync group synchronization.

*Tags:* `SyncGroups`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database on which the sync group is hosted.
* `syncGroupName` - _required_ - The name of the sync group.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `api-version` - _required_ - The API version to use for the request.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-sync-groups-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
