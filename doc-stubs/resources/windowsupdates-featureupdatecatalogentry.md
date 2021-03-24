---
title: "featureUpdateCatalogEntry resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# featureUpdateCatalogEntry resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [softwareUpdateCatalogEntry](../resources/softwareupdatecatalogentry.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List featureUpdateCatalogEntries](../api/featureupdatecatalogentry-list.md)|[featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md) collection|Get a list of the [featureUpdateCatalogEntry](../resources/featureupdatecatalogentry.md) objects and their properties.|
|[Create featureUpdateCatalogEntry](../api/windowsupdates-featureupdatecatalogentry-create.md)|[featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md)|Create a new [featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md) object.|
|[Get featureUpdateCatalogEntry](../api/windowsupdates-featureupdatecatalogentry-get.md)|[featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md)|Read the properties and relationships of a [featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md) object.|
|[Update featureUpdateCatalogEntry](../api/windowsupdates-featureupdatecatalogentry-update.md)|[featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md)|Update the properties of a [featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md) object.|
|[Delete featureUpdateCatalogEntry](../api/windowsupdates-featureupdatecatalogentry-delete.md)|None|Deletes a [featureUpdateCatalogEntry](../resources/windowsupdates-featureupdatecatalogentry.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deployableUntilDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|displayName|String|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|
|releaseDate|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|version|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.featureUpdateCatalogEntry",
  "baseType": "microsoft.graph.windowsUpdates.softwareUpdateCatalogEntry",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.featureUpdateCatalogEntry",
  "id": "String (identifier)",
  "displayName": "String",
  "releaseDate": "String (timestamp)",
  "deployableUntilDateTime": "String (timestamp)",
  "version": "String"
}
```

