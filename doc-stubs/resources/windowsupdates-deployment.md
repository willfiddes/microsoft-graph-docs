---
title: "deployment resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deployment resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List deployments](../api/deployment-list.md)|[deployment](../resources/windowsupdates-deployment.md) collection|Get a list of the [deployment](../resources/deployment.md) objects and their properties.|
|[Create deployment](../api/windowsupdates-deployment-create.md)|[deployment](../resources/windowsupdates-deployment.md)|Create a new [deployment](../resources/windowsupdates-deployment.md) object.|
|[Get deployment](../api/windowsupdates-deployment-get.md)|[deployment](../resources/windowsupdates-deployment.md)|Read the properties and relationships of a [deployment](../resources/windowsupdates-deployment.md) object.|
|[Update deployment](../api/windowsupdates-deployment-update.md)|[deployment](../resources/windowsupdates-deployment.md)|Update the properties of a [deployment](../resources/windowsupdates-deployment.md) object.|
|[Delete deployment](../api/windowsupdates-deployment-delete.md)|None|Deletes a [deployment](../resources/windowsupdates-deployment.md) object.|
|[updateSettings](../api/windowsupdates-deployment-updatesettings.md)|None|**TODO: Add Description**|
|[List deploymentAudience](../api/windowsupdates-deployment-list-audience.md)|[deploymentAudience](../resources/windowsupdates-deploymentaudience.md) collection|Get the deploymentAudience resources from the audience navigation property.|
|[Create deploymentAudience](../api/windowsupdates-deployment-post-audience.md)|[deploymentAudience](../resources/windowsupdates-deploymentaudience.md)|Create a new deploymentAudience object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|content|[deployableContent](../resources/windowsupdates-deployablecontent.md)|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|settings|[deploymentSettings](../resources/windowsupdates-deploymentsettings.md)|**TODO: Add Description**|
|state|[deploymentState](../resources/windowsupdates-deploymentstate.md)|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|audience|[deploymentAudience](../resources/windowsupdates-deploymentaudience.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.deployment",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.deployment",
  "id": "String (identifier)",
  "state": {
    "@odata.type": "microsoft.graph.windowsUpdates.deploymentState"
  },
  "content": {
    "@odata.type": "microsoft.graph.windowsUpdates.deployableContent"
  },
  "settings": {
    "@odata.type": "microsoft.graph.windowsUpdates.deploymentSettings"
  },
  "createdDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)"
}
```

