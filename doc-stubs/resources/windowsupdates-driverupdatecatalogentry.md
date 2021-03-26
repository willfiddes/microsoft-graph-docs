---
title: "driverUpdateCatalogEntry resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# driverUpdateCatalogEntry resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [softwareUpdateCatalogEntry](../resources/softwareupdatecatalogentry.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List driverUpdateCatalogEntries](../api/driverupdatecatalogentry-list.md)|[driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) collection|Get a list of the [driverUpdateCatalogEntry](../resources/driverupdatecatalogentry.md) objects and their properties.|
|[Create driverUpdateCatalogEntry](../api/windowsupdates-driverupdatecatalogentry-create.md)|[driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md)|Create a new [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) object.|
|[Get driverUpdateCatalogEntry](../api/windowsupdates-driverupdatecatalogentry-get.md)|[driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md)|Read the properties and relationships of a [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) object.|
|[Update driverUpdateCatalogEntry](../api/windowsupdates-driverupdatecatalogentry-update.md)|[driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md)|Update the properties of a [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) object.|
|[Delete driverUpdateCatalogEntry](../api/windowsupdates-driverupdatecatalogentry-delete.md)|None|Deletes a [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deployableUntilDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|driverClass|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|
|manufacturer|String|**TODO: Add Description**|
|provider|String|**TODO: Add Description**|
|releaseDate|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|version|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.driverUpdateCatalogEntry",
  "baseType": "microsoft.graph.windowsUpdates.softwareUpdateCatalogEntry",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.driverUpdateCatalogEntry",
  "id": "String (identifier)",
  "displayName": "String",
  "releaseDate": "String (timestamp)",
  "deployableUntilDateTime": "String (timestamp)",
  "description": "String",
  "driverClass": "String",
  "provider": "String",
  "manufacturer": "String",
  "version": "String"
}
```

