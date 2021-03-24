---
title: "windowsDeploymentSettings resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# windowsDeploymentSettings resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [deploymentSettings](../resources/deploymentsettings.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|monitoring|[monitoringSettings](../resources/windowsupdates-monitoringsettings.md)|**TODO: Add Description** Inherited from [deploymentSettings](../resources/windowsupdates-deploymentsettings.md)|
|rollout|[rolloutSettings](../resources/windowsupdates-rolloutsettings.md)|**TODO: Add Description** Inherited from [deploymentSettings](../resources/windowsupdates-deploymentsettings.md)|
|userExperience|[userExperienceSettings](../resources/windowsupdates-userexperiencesettings.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsUpdates.windowsDeploymentSettings"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.windowsDeploymentSettings",
  "rollout": {
    "@odata.type": "microsoft.graph.windowsUpdates.rolloutSettings"
  },
  "monitoring": {
    "@odata.type": "microsoft.graph.windowsUpdates.monitoringSettings"
  },
  "userExperience": {
    "@odata.type": "microsoft.graph.windowsUpdates.userExperienceSettings"
  }
}
```

