# # TerrainPark

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the terrain park. |
**name** | **string** | Display name of the terrain park. |
**slug** | **string** | URL-friendly name of the terrain park. |
**number** | **int** | Optional terrain park number. | [optional]
**status** | [**\MtnManager\Model\TerrainParkStatus**](TerrainParkStatus.md) | Current operational status (open, closed, or unknown). |
**condition_notes** | **string** | Notes about current conditions in this terrain park. |
**area_uuid** | **string** | UUID of the area this terrain park belongs to, if assigned. | [optional]
**area_name** | **string** | Name of the area this terrain park belongs to, if assigned. | [optional]
**area_display_order** | **int** | Display order of the area this terrain park belongs to, if assigned, for sorting purposes. | [optional]
**features** | [**\MtnManager\Model\TerrainParkFeature[]**](TerrainParkFeature.md) | Features within this terrain park (jumps, boxes, rails, etc.). |
**updated_at** | **\DateTime** | When this terrain park or any of its features was last updated. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
