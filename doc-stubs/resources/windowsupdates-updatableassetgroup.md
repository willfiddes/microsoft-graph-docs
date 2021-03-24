---
title: "updatableAssetGroup resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# updatableAssetGroup resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [updatableAsset](../resources/updatableasset.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List updatableAssetGroups](../api/updatableassetgroup-list.md)|[updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md) collection|Get a list of the [updatableAssetGroup](../resources/updatableassetgroup.md) objects and their properties.|
|[Create updatableAssetGroup](../api/windowsupdates-updatableassetgroup-create.md)|[updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md)|Create a new [updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md) object.|
|[Get updatableAssetGroup](../api/windowsupdates-updatableassetgroup-get.md)|[updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md)|Read the properties and relationships of an [updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md) object.|
|[Update updatableAssetGroup](../api/windowsupdates-updatableassetgroup-update.md)|[updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md)|Update the properties of an [updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md) object.|
|[Delete updatableAssetGroup](../api/windowsupdates-updatableassetgroup-delete.md)|None|Deletes an [updatableAssetGroup](../resources/windowsupdates-updatableassetgroup.md) object.|
|[addMembers](../api/windowsupdates-updatableassetgroup-addmembers.md)|None|**TODO: Add Description**|
|[addMembersById](../api/windowsupdates-updatableassetgroup-addmembersbyid.md)|None|**TODO: Add Description**|
|[removeMembers](../api/windowsupdates-updatableassetgroup-removemembers.md)|None|**TODO: Add Description**|
|[removeMembersById](../api/windowsupdates-updatableassetgroup-removemembersbyid.md)|None|**TODO: Add Description**|
|[List members](../api/windowsupdates-updatableassetgroup-list-members.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|Get the updatableAsset resources from the members navigation property.|
|[Create updatableAsset](../api/windowsupdates-updatableassetgroup-post-members.md)|[updatableAsset](../resources/windowsupdates-updatableasset.md)|Create a new updatableAsset object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|members|[updatableAsset](../resources/windowsupdates-updatableasset.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.updatableAssetGroup",
  "baseType": "microsoft.graph.windowsUpdates.updatableAsset",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.updatableAssetGroup",
  "id": "String (identifier)"
}
```

