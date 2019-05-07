# ![LOGO](logo.png) Azure ML Commitment Plans Management Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure ML Commitment Plans Management Client API (version 2016-05-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/machinelearning-commitmentPlans/2016-05-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:19+03:00

## API Description

These APIs allow end users to operate on Azure Machine Learning Commitment Plans resources and their child Commitment Association resources. They support CRUD operations for commitment plans, get and list operations for commitment associations, moving commitment associations between commitment plans, and retrieving commitment plan usage history.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Azure Machine Learning Studio Commitment Plan RP REST API operations.

*Tags:* `Operation`

#### Input Parameters
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Retrieve all Azure ML commitment plans in a subscription.

*Tags:* `CommitmentPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `$skipToken` - _optional_ - Continuation token for pagination.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Lists the available commitment plan SKUs.

*Tags:* `Skus`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Retrieve all Azure ML commitment plans in a resource group.

*Tags:* `CommitmentPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `$skipToken` - _optional_ - Continuation token for pagination.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Remove an existing Azure ML commitment plan.

*Tags:* `CommitmentPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Retrieve an Azure ML commitment plan by its subscription, resource group and name.

*Tags:* `CommitmentPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Patch an existing Azure ML commitment plan resource.

*Tags:* `CommitmentPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Create a new Azure ML commitment plan resource or updates an existing one.

*Tags:* `CommitmentPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Get all commitment associations for a parent commitment plan.

*Tags:* `CommitmentAssociations`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `$skipToken` - _optional_ - Continuation token for pagination.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Get a commitment association.

*Tags:* `CommitmentAssociations`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `commitmentAssociationName` - _required_ - The commitment association name.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Re-parent a commitment association from one commitment plan to another.

*Tags:* `CommitmentAssociations`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `commitmentAssociationName` - _required_ - The commitment association name.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

### Retrieve the usage history for an Azure ML commitment plan.

*Tags:* `CommitmentPlans`

#### Input Parameters
* `subscriptionId` - _required_ - Azure Subscription ID.
* `resourceGroupName` - _required_ - The resource group name.
* `commitmentPlanName` - _required_ - The Azure ML commitment plan name.
* `$skipToken` - _optional_ - Continuation token for pagination.
* `api-version` - _required_ - The version of the Microsoft.MachineLearning resource provider API to use.

## License

**flow**ground :- Telekom iPaaS / azure-com-machinelearning-commitment-plans-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
