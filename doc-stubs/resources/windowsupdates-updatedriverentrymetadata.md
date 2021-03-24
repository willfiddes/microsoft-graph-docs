---
title: "updateDriverEntryMetadata resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# updateDriverEntryMetadata resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|catalogEntryId|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|driverClass|String|**TODO: Add Description**|
|manufacturer|String|**TODO: Add Description**|
|provider|String|**TODO: Add Description**|
|releaseDate|DateTimeOffset|**TODO: Add Description**|
|version|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsUpdates.updateDriverEntryMetadata"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.updateDriverEntryMetadata",
  "catalogEntryId": "String",
  "displayName": "String",
  "releaseDate": "String (timestamp)",
  "description": "String",
  "driverClass": "String",
  "provider": "String",
  "manufacturer": "String",
  "version": "String"
}
```

