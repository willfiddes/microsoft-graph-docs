---
title: "azureADDevice resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# azureADDevice resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [updatableAsset](../resources/updatableasset.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List azureADDevices](../api/azureaddevice-list.md)|[azureADDevice](../resources/windowsupdates-azureaddevice.md) collection|Get a list of the [azureADDevice](../resources/azureaddevice.md) objects and their properties.|
|[Create azureADDevice](../api/windowsupdates-azureaddevice-create.md)|[azureADDevice](../resources/windowsupdates-azureaddevice.md)|Create a new [azureADDevice](../resources/windowsupdates-azureaddevice.md) object.|
|[Get azureADDevice](../api/windowsupdates-azureaddevice-get.md)|[azureADDevice](../resources/windowsupdates-azureaddevice.md)|Read the properties and relationships of an [azureADDevice](../resources/windowsupdates-azureaddevice.md) object.|
|[Update azureADDevice](../api/windowsupdates-azureaddevice-update.md)|[azureADDevice](../resources/windowsupdates-azureaddevice.md)|Update the properties of an [azureADDevice](../resources/windowsupdates-azureaddevice.md) object.|
|[Delete azureADDevice](../api/windowsupdates-azureaddevice-delete.md)|None|Deletes an [azureADDevice](../resources/windowsupdates-azureaddevice.md) object.|
|[addMembers](../api/windowsupdates-azureaddevice-addmembers.md)|None|**TODO: Add Description**|
|[addMembersById](../api/windowsupdates-azureaddevice-addmembersbyid.md)|None|**TODO: Add Description**|
|[removeMembers](../api/windowsupdates-azureaddevice-removemembers.md)|None|**TODO: Add Description**|
|[removeMembersById](../api/windowsupdates-azureaddevice-removemembersbyid.md)|None|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|enrollments|[updatableAssetEnrollment](../resources/windowsupdates-updatableassetenrollment.md) collection|**TODO: Add Description**|
|errors|[updatableAssetError](../resources/windowsupdates-updatableasseterror.md) collection|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.azureADDevice",
  "baseType": "microsoft.graph.windowsUpdates.updatableAsset",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.azureADDevice",
  "id": "String (identifier)",
  "errors": [
    {
      "@odata.type": "microsoft.graph.windowsUpdates.azureADDeviceRegistrationError"
    }
  ],
  "enrollments": [
    {
      "@odata.type": "microsoft.graph.windowsUpdates.updateManagementEnrollment"
    }
  ]
}
```

