---
title: "deploymentAudience resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deploymentAudience resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List deploymentAudiences](../api/deploymentaudience-list.md)|[deploymentAudience](../resources/windowsupdates-deploymentaudience.md) collection|Get a list of the [deploymentAudience](../resources/deploymentaudience.md) objects and their properties.|
|[Create deploymentAudience](../api/windowsupdates-deploymentaudience-create.md)|[deploymentAudience](../resources/windowsupdates-deploymentaudience.md)|Create a new [deploymentAudience](../resources/windowsupdates-deploymentaudience.md) object.|
|[Get deploymentAudience](../api/windowsupdates-deploymentaudience-get.md)|[deploymentAudience](../resources/windowsupdates-deploymentaudience.md)|Read the properties and relationships of a [deploymentAudience](../resources/windowsupdates-deploymentaudience.md) object.|
|[Update deploymentAudience](../api/windowsupdates-deploymentaudience-update.md)|[deploymentAudience](../resources/windowsupdates-deploymentaudience.md)|Update the properties of a [deploymentAudience](../resources/windowsupdates-deploymentaudience.md) object.|
|[Delete deploymentAudience](../api/windowsupdates-deploymentaudience-delete.md)|None|Deletes a [deploymentAudience](../resources/windowsupdates-deploymentaudience.md) object.|
|[applicableUpdatesDrivers](../api/windowsupdates-deploymentaudience-applicableupdatesdrivers.md)|[applicableUpdateDriver](../resources/windowsupdates-applicableupdatedriver.md) collection|**TODO: Add Description**|
|[updateAudience](../api/windowsupdates-deploymentaudience-updateaudience.md)|None|**TODO: Add Description**|
|[updateAudienceById](../api/windowsupdates-deploymentaudience-updateaudiencebyid.md)|None|**TODO: Add Description**|
|[List exclusions](../api/windowsupdates-deploymentaudience-list-exclusions.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|Get the updatableAsset resources from the exclusions navigation property.|
|[Create updatableAsset](../api/windowsupdates-deploymentaudience-post-exclusions.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md)|Create a new updatableAsset object.|
|[List members](../api/windowsupdates-deploymentaudience-list-members.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|Get the updatableAsset resources from the members navigation property.|
|[Create updatableAsset](../api/windowsupdates-deploymentaudience-post-members.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md)|Create a new updatableAsset object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|exclusions|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|**TODO: Add Description**|
|members|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.deploymentAudience",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.deploymentAudience",
  "id": "String (identifier)"
}
```

