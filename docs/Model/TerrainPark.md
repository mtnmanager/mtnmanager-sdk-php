# TerrainPark

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the terrain park. |
**name** | **string** | Display name of the terrain park. |
**slug** | **string** | URL-friendly name of the terrain park. |
**number** | **int** | Optional terrain park number. | [optional]
**status** | [**\MtnManager\Model\TerrainParkStatus**](TerrainParkStatus.md) | Current operational status (open, closed, or unknown). |
**last_groomed** | **\DateTime** | When the terrain park was last groomed.  &#x60;null&#x60; if not groomed this season (since the snow year began: Aug 1, or  Jan 1 in the southern hemisphere), or if the terrain park grooming feature  is disabled. | [optional]
**groomed_today** | **bool** | Whether the terrain park has been groomed since the resort last closed  (or, for a resort with no operating hours set, within the last 24 hours). |
**snow_since_groomed_cm** | **int** | New snow (cm) reported since &#x60;last_groomed&#x60;. Absent unless the park  was groomed within the last 24 hours and the resort keeps a snow report. | [optional]
**snow_since_groomed_in** | **int** | New snow (inches) reported since &#x60;last_groomed&#x60;; see  &#x60;snow_since_groomed_cm&#x60;. | [optional]
**condition_notes** | **string** | Notes about current conditions in this terrain park. |
**area_uuid** | **string** | UUID of the area this terrain park belongs to, if assigned. | [optional]
**area_name** | **string** | Name of the area this terrain park belongs to, if assigned. | [optional]
**area_display_order** | **int** | Display order of the area this terrain park belongs to, if assigned, for sorting purposes. | [optional]
**features** | [**\MtnManager\Model\TerrainParkFeature[]**](TerrainParkFeature.md) | Features within this terrain park (jumps, boxes, rails, etc.). |
**updated_at** | **\DateTime** | When this terrain park or any of its features was last updated. |
**images** | [**\MtnManager\Model\EntityImage[]**](EntityImage.md) | Images attached to this terrain park, ordered for display. Each includes  a ThumbHash for rendering a blurred placeholder while the image loads. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
