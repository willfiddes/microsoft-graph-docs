---
title: "catalog resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# catalog resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List catalogs](../api/catalog-list.md)|[catalog](../resources/windowsupdates-catalog.md) collection|Get a list of the [catalog](../resources/catalog.md) objects and their properties.|
|[Create catalog](../api/windowsupdates-catalog-create.md)|[catalog](../resources/windowsupdates-catalog.md)|Create a new [catalog](../resources/windowsupdates-catalog.md) object.|
|[Get catalog](../api/windowsupdates-catalog-get.md)|[catalog](../resources/windowsupdates-catalog.md)|Read the properties and relationships of a [catalog](../resources/windowsupdates-catalog.md) object.|
|[Update catalog](../api/windowsupdates-catalog-update.md)|[catalog](../resources/windowsupdates-catalog.md)|Update the properties of a [catalog](../resources/windowsupdates-catalog.md) object.|
|[Delete catalog](../api/windowsupdates-catalog-delete.md)|None|Deletes a [catalog](../resources/windowsupdates-catalog.md) object.|
|[List entries](../api/windowsupdates-catalog-list-entries.md)|[catalogEntry](../resources/windowsupdates-catalogentry.md) collection|Get the catalogEntry resources from the entries navigation property.|
|[Create catalogEntry](../api/windowsupdates-catalog-post-entries.md)|[catalogEntry](../resources/windowsupdates-catalogentry.md)|Create a new catalogEntry object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|entries|[catalogEntry](../resources/windowsupdates-catalogentry.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.catalog",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.catalog",
  "id": "String (identifier)"
}
```

