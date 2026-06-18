# TerrainParkFeature

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the feature. |
**name** | **string** | Display name of the feature. |
**slug** | **string** | URL-friendly name of the run. |
**number** | **int** | Optional feature number. | [optional]
**feature_type** | [**\MtnManager\Model\FeatureType**](FeatureType.md) | Type of feature (jump, box, rail, other). |
**size** | [**\MtnManager\Model\FeatureSize**](FeatureSize.md) | Optional size rating of the feature (S, M, L, XL). | [optional]
**status** | [**\MtnManager\Model\TerrainParkFeatureStatus**](TerrainParkFeatureStatus.md) | Current operational status (open, closed, or unknown).  &#x60;unknown&#x60; unless the terrain park feature status is enabled. |
**images** | [**\MtnManager\Model\EntityImage[]**](EntityImage.md) | Images attached to this feature, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
