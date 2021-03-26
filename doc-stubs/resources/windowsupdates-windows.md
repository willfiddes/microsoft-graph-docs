---
title: "windows resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# windows resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List windows](../api/windows-list.md)|[windows](../resources/windowsupdates-windows.md) collection|Get a list of the [windows](../resources/windows.md) objects and their properties.|
|[Create windows](../api/windowsupdates-windows-create.md)|[windows](../resources/windowsupdates-windows.md)|Create a new [windows](../resources/windowsupdates-windows.md) object.|
|[Get windows](../api/windowsupdates-windows-get.md)|[windows](../resources/windowsupdates-windows.md)|Read the properties and relationships of a [windows](../resources/windowsupdates-windows.md) object.|
|[Update windows](../api/windowsupdates-windows-update.md)|[windows](../resources/windowsupdates-windows.md)|Update the properties of a [windows](../resources/windowsupdates-windows.md) object.|
|[Delete windows](../api/windowsupdates-windows-delete.md)|None|Deletes a [windows](../resources/windowsupdates-windows.md) object.|
|[List updates](../api/windowsupdates-windows-list-updates.md)|[updates](../resources/windowsupdates-updates.md) collection|Get the updates resources from the updates navigation property.|
|[Create updates](../api/windowsupdates-windows-post-updates.md)|[updates](../resources/windowsupdates-updates.md)|Create a new updates object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|updates|[updates](../resources/windowsupdates-updates.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.windows",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.windows",
  "id": "String (identifier)"
}
```

