---
title: "qualityUpdateCatalogEntry resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# qualityUpdateCatalogEntry resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [softwareUpdateCatalogEntry](../resources/softwareupdatecatalogentry.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List qualityUpdateCatalogEntries](../api/qualityupdatecatalogentry-list.md)|[qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md) collection|Get a list of the [qualityUpdateCatalogEntry](../resources/qualityupdatecatalogentry.md) objects and their properties.|
|[Create qualityUpdateCatalogEntry](../api/windowsupdates-qualityupdatecatalogentry-create.md)|[qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md)|Create a new [qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md) object.|
|[Get qualityUpdateCatalogEntry](../api/windowsupdates-qualityupdatecatalogentry-get.md)|[qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md)|Read the properties and relationships of a [qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md) object.|
|[Update qualityUpdateCatalogEntry](../api/windowsupdates-qualityupdatecatalogentry-update.md)|[qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md)|Update the properties of a [qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md) object.|
|[Delete qualityUpdateCatalogEntry](../api/windowsupdates-qualityupdatecatalogentry-delete.md)|None|Deletes a [qualityUpdateCatalogEntry](../resources/windowsupdates-qualityupdatecatalogentry.md) object.|
|[List fixedIssues](../api/windowsupdates-qualityupdatecatalogentry-list-fixedissues.md)|[fixedIssueCatalogEntry](../resources/windowsupdates-fixedissuecatalogentry.md) collection|Get the fixedIssueCatalogEntry resources from the fixedIssues navigation property.|
|[Add fixedIssueCatalogEntry](../api/windowsupdates-qualityupdatecatalogentry-post-fixedissues.md)|[fixedIssueCatalogEntry](../resources/windowsupdates-fixedissuecatalogentry.md)|Add fixedIssues by posting to the fixedIssues collection.|
|[List patchedVulnerabilities](../api/windowsupdates-qualityupdatecatalogentry-list-patchedvulnerabilities.md)|[patchedVulnerabilityCatalogEntry](../resources/windowsupdates-patchedvulnerabilitycatalogentry.md) collection|Get the patchedVulnerabilityCatalogEntry resources from the patchedVulnerabilities navigation property.|
|[Add patchedVulnerabilityCatalogEntry](../api/windowsupdates-qualityupdatecatalogentry-post-patchedvulnerabilities.md)|[patchedVulnerabilityCatalogEntry](../resources/windowsupdates-patchedvulnerabilitycatalogentry.md)|Add patchedVulnerabilities by posting to the patchedVulnerabilities collection.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deployableUntilDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|display|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|
|isExpeditable|Boolean|**TODO: Add Description**|
|qualityUpdateClassification|qualityUpdateClassification|**TODO: Add Description**. Possible values are: `all`, `security`, `nonSecurity`.|
|rank|Int32|**TODO: Add Description**|
|releaseDate|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|fixedIssues|[fixedIssueCatalogEntry](../resources/windowsupdates-fixedissuecatalogentry.md) collection|**TODO: Add Description**|
|patchedVulnerabilities|[patchedVulnerabilityCatalogEntry](../resources/windowsupdates-patchedvulnerabilitycatalogentry.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.qualityUpdateCatalogEntry",
  "baseType": "microsoft.graph.windowsUpdates.softwareUpdateCatalogEntry",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.qualityUpdateCatalogEntry",
  "id": "String (identifier)",
  "displayName": "String",
  "releaseDate": "String (timestamp)",
  "deployableUntilDateTime": "String (timestamp)",
  "isExpeditable": "Boolean",
  "rank": "Integer",
  "display": "String",
  "qualityUpdateClassification": "String"
}
```

