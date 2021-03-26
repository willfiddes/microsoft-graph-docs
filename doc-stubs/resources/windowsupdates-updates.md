---
title: "updates resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# updates resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List updates](../api/updates-list.md)|[updates](../resources/windowsupdates-updates.md) collection|Get a list of the [updates](../resources/updates.md) objects and their properties.|
|[Create updates](../api/windowsupdates-updates-create.md)|[updates](../resources/windowsupdates-updates.md)|Create a new [updates](../resources/windowsupdates-updates.md) object.|
|[Get updates](../api/windowsupdates-updates-get.md)|[updates](../resources/windowsupdates-updates.md)|Read the properties and relationships of an [updates](../resources/windowsupdates-updates.md) object.|
|[Update updates](../api/windowsupdates-updates-update.md)|[updates](../resources/windowsupdates-updates.md)|Update the properties of an [updates](../resources/windowsupdates-updates.md) object.|
|[Delete updates](../api/windowsupdates-updates-delete.md)|None|Deletes an [updates](../resources/windowsupdates-updates.md) object.|
|[List catalog](../api/windowsupdates-updates-list-catalog.md)|[catalog](../resources/windowsupdates-catalog.md) collection|Get the catalog resources from the catalog navigation property.|
|[Create catalog](../api/windowsupdates-updates-post-catalog.md)|[catalog](../resources/windowsupdates-catalog.md)|Create a new catalog object.|
|[List deployments](../api/windowsupdates-updates-list-deployments.md)|[deployment](../resources/windowsupdates-deployment.md) collection|Get the deployment resources from the deployments navigation property.|
|[Create deployment](../api/windowsupdates-updates-post-deployments.md)|[deployment](../resources/windowsupdates-deployment.md)|Create a new deployment object.|
|[List updatableAssets](../api/windowsupdates-updates-list-updatableassets.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|Get the updatableAsset resources from the updatableAssets navigation property.|
|[Create updatableAsset](../api/windowsupdates-updates-post-updatableassets.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md)|Create a new updatableAsset object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|catalog|[catalog](../resources/windowsupdates-catalog.md)|**TODO: Add Description**|
|deployments|[deployment](../resources/windowsupdates-deployment.md) collection|**TODO: Add Description**|
|updatableAssets|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.updates",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.updates",
  "id": "String (identifier)"
}
```

