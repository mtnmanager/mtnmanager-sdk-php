# # SummerTrail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the trail. |
**name** | **string** | Display name of the trail. |
**slug** | **string** | URL-friendly name of the trail. |
**number** | **int** | Optional trail number. | [optional]
**trail_type** | [**\MtnManager\Model\SummerTrailType[]**](SummerTrailType.md) | Type of trail activity (e.g. hiking, mountain_biking). Can have multiple. |
**difficulty** | [**\MtnManager\Model\SummerTrailDifficulty**](SummerTrailDifficulty.md) |  | [optional]
**status** | [**\MtnManager\Model\SummerTrailStatus**](SummerTrailStatus.md) | Current operational status (open, closed, or unknown). |
**condition_notes** | **string** | Notes about current conditions on this trail. |
**area_uuid** | **string** | UUID of the area this trail belongs to, if assigned. | [optional]
**area_name** | **string** | Name of the area this trail belongs to, if assigned. | [optional]
**area_display_order** | **int** | Display order of the area this trail belongs to, if assigned, for sorting purposes. | [optional]
**updated_at** | **\DateTime** | When this trail&#39;s information was last updated. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
