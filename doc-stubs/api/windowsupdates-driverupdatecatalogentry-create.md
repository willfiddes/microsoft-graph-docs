---
title: "Create driverUpdateCatalogEntry"
description: "Create a new driverUpdateCatalogEntry object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create driverUpdateCatalogEntry
Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) object.

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
POST ** Collection URI for microsoft.graph.windowsUpdates.driverUpdateCatalogEntry not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) object.

The following table shows the properties that are required when you create the [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|
|displayName|String|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|releaseDate|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|deployableUntilDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [catalogEntry](../resources/windowsupdates-catalogentry.md)|
|description|String|**TODO: Add Description**|
|driverClass|String|**TODO: Add Description**|
|provider|String|**TODO: Add Description**|
|manufacturer|String|**TODO: Add Description**|
|version|String|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [driverUpdateCatalogEntry](../resources/windowsupdates-driverupdatecatalogentry.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_driverupdatecatalogentry_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.windowsUpdates.driverUpdateCatalogEntry not found
Content-Type: application/json
Content-length: 335

{
  "@odata.type": "#microsoft.graph.windowsUpdates.driverUpdateCatalogEntry",
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


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.windowsUpdates.driverUpdateCatalogEntry"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.windowsUpdates.driverUpdateCatalogEntry",
  "id": "52f0b9db-b9db-52f0-dbb9-f052dbb9f052",
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

