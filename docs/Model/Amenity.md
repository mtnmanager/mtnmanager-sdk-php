# Amenity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **string** | Description of the amenity. |
**uuid** | **string** | Unique identifier for the amenity. |
**name** | **string** | Display name of the amenity. |
**category** | [**\MtnManager\Model\AmenityCategory**](AmenityCategory.md) | Category classification (e.g. restaurant, lodge, ski_school). |
**website** | **string** | Website URL for the amenity, if available. |
**opens_at** | **string** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional]
**closes_at** | **string** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional]
**schedules** | [**\MtnManager\Model\Schedule[]**](Schedule.md) | Recurring operating schedules for this amenity (e.g. \&quot;Saturday &amp; Sunday,  9:00 a.m. to 4:00 p.m.\&quot;), with both human-readable and structured fields. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
