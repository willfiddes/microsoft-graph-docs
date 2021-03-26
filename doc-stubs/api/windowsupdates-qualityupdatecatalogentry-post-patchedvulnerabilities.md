---
title: "Add patchedVulnerabilityCatalogEntry"
description: "Add patchedVulnerabilities by posting to the patchedVulnerabilities collection."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Add patchedVulnerabilityCatalogEntry
Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Add patchedVulnerabilities by posting to the patchedVulnerabilities collection.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST /qualityUpdateCatalogEntry/patchedVulnerabilities/$ref
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [patchedVulnerabilityCatalogEntry](../resources/windowsupdates-patchedvulnerabilitycatalogentry.md) object.

The following table shows the properties that are required when you create the [patchedVulnerabilityCatalogEntry](../resources/windowsupdates-patchedvulnerabilitycatalogentry.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|
|severity|patchedVulnerabilitySeverity|**TODO: Add Description**. Possible values are: `none`, `low`, `moderate`, `important`, `critical`.|
|impact|patchedVulnerabilityImpact|**TODO: Add Description**. Possible values are: `none`, `remoteCodeExecution`, `elevationOfPrivilege`, `denialOfService`, `securityFeatureBypass`, `informationDisclosure`, `repudiation`, `tampering`, `spoofing`, `defenseInDepth`, `notAVulnerability`.|



## Response

If successful, this method returns a `204 No Content` response code and a [patchedVulnerabilityCatalogEntry](../resources/windowsupdates-patchedvulnerabilitycatalogentry.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_patchedvulnerabilitycatalogentry_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/qualityUpdateCatalogEntry/patchedVulnerabilities/$ref
Content-Type: application/json
Content-length: 137

{
  "@odata.type": "#microsoft.graph.windowsUpdates.patchedVulnerabilityCatalogEntry",
  "severity": "String",
  "impact": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.windowsUpdates.patchedVulnerabilityCatalogEntry"
}
-->
``` http
HTTP/1.1 204 No Content
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.windowsUpdates.patchedVulnerabilityCatalogEntry",
  "id": "26ea501a-501a-26ea-1a50-ea261a50ea26",
  "severity": "String",
  "impact": "String"
}
```

