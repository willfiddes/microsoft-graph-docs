---
title: "catalogEntry resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# catalogEntry resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List catalogEntries](../api/catalogentry-list.md)|[catalogEntry](../resources/windowsupdates-catalogentry.md) collection|Get a list of the [catalogEntry](../resources/catalogentry.md) objects and their properties.|
|[Create catalogEntry](../api/windowsupdates-catalogentry-create.md)|[catalogEntry](../resources/windowsupdates-catalogentry.md)|Create a new [catalogEntry](../resources/windowsupdates-catalogentry.md) object.|
|[Get catalogEntry](../api/windowsupdates-catalogentry-get.md)|[catalogEntry](../resources/windowsupdates-catalogentry.md)|Read the properties and relationships of a [catalogEntry](../resources/windowsupdates-catalogentry.md) object.|
|[Update catalogEntry](../api/windowsupdates-catalogentry-update.md)|[catalogEntry](../resources/windowsupdates-catalogentry.md)|Update the properties of a [catalogEntry](../resources/windowsupdates-catalogentry.md) object.|
|[Delete catalogEntry](../api/windowsupdates-catalogentry-delete.md)|None|Deletes a [catalogEntry](../resources/windowsupdates-catalogentry.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deployableUntilDateTime|DateTimeOffset|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|
|releaseDate|DateTimeOffset|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.catalogEntry",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.catalogEntry",
  "id": "String (identifier)",
  "displayName": "String",
  "releaseDate": "String (timestamp)",
  "deployableUntilDateTime": "String (timestamp)"
}
```

