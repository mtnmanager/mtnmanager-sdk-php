# # Lift

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the lift. |
**name** | **string** | Display name of the lift. |
**slug** | **string** | URL-friendly name of the lift. |
**number** | **int** | Optional lift number. | [optional]
**lift_type** | [**\MtnManager\Model\LiftType**](LiftType.md) | Type of lift (e.g. gondola, quad). |
**high_speed** | **bool** | Whether this is a high-speed/detachable lift. |
**bubble** | **bool** | Whether the lift has a bubble/cover for weather protection. |
**heated** | **bool** | Whether the lift has heated seats. |
**status** | [**\MtnManager\Model\LiftStatus**](LiftStatus.md) | Current operational status (open, closed, on_hold, or unknown). |
**wait_time_minutes** | **int** | Current estimated wait time in minutes, if available. | [optional]
**area_uuid** | **string** | UUID of the area this lift belongs to, if assigned. | [optional]
**area_name** | **string** | Name of the area this lift belongs to, if assigned. | [optional]
**area_display_order** | **int** | Display order of the area this lift belongs to, if assigned, for sorting purposes. | [optional]
**updated_at** | **\DateTime** | When this lift&#39;s information was last updated. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
