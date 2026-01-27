# # SnowReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for this snow report. |
**area_uuid** | **string** | UUID of the area this report covers, if area-specific.  &#x60;null&#x60; for resort-wide reports. | [optional]
**area_name** | **string** | Name of the area this report covers, if area-specific. | [optional]
**area_display_order** | **int** | Display order of the area this report covers, if area-specific, for sorting purposes. | [optional]
**base_depth_cm** | **int** | Current base depth in centimeters.  Not included if the base depth feature is disabled. | [optional]
**base_depth_in** | **int** | Current base depth in inches.  Not included if the base depth feature is disabled. | [optional]
**surface_condition** | [**\MtnManager\Model\SurfaceCondition**](SurfaceCondition.md) |  | [optional]
**secondary_surface_condition** | [**\MtnManager\Model\SurfaceCondition**](SurfaceCondition.md) |  | [optional]
**condition_notes** | **string** | Additional notes about current snow conditions, e.g. groomer&#39;s notes |
**snowfall_cm** | [**\MtnManager\Model\SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in centimeters. |
**snowfall_in** | [**\MtnManager\Model\SnowMetrics**](SnowMetrics.md) | Snowfall accumulation metrics in inches. |
**reported_at** | **\DateTime** | When this snow report was last updated. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
