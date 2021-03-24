---
title: "expeditedQualityUpdateReference resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# expeditedQualityUpdateReference resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [qualityUpdateReference](../resources/qualityupdatereference.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|classification|qualityUpdateClassification|**TODO: Add Description** Inherited from [qualityUpdateReference](../resources/windowsupdates-qualityupdatereference.md). Possible values are: `all`, `security`, `nonSecurity`.|
|equivalentContent|equivalentContentOption|**TODO: Add Description**. Possible values are: `none`, `latestSecurity`.|
|releaseDate|DateTimeOffset|**TODO: Add Description** Inherited from [qualityUpdateReference](../resources/windowsupdates-qualityupdatereference.md)|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsUpdates.expeditedQualityUpdateReference"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.expeditedQualityUpdateReference",
  "classification": "String",
  "releaseDate": "String (timestamp)",
  "equivalentContent": "String"
}
```

