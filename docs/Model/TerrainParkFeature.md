# # TerrainParkFeature

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the feature. |
**name** | **string** | Display name of the feature. |
**slug** | **string** | URL-friendly name of the run. |
**number** | **int** | Optional feature number. | [optional]
**feature_type** | [**\MtnManager\Model\FeatureType**](FeatureType.md) | Type of feature (jump, box, rail, other). |
**size** | [**\MtnManager\Model\FeatureSize**](FeatureSize.md) |  | [optional]
**status** | [**\MtnManager\Model\TerrainParkFeatureStatus**](TerrainParkFeatureStatus.md) | Current operational status (open, closed, or unknown).  &#x60;unknown&#x60; unless the terrain park feature status is enabled. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
