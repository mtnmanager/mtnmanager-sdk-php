# # OperatingHours

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**schedules** | [**\MtnManager\Model\Schedule[]**](Schedule.md) | Recurring operating schedules currently in effect or upcoming.  Excludes single-day overrides and past schedules. |
**calendar_days** | [**\MtnManager\Model\CalendarDay[]**](CalendarDay.md) | List of all days the resort is open (or a closure override).  Ordered chronologically, spanning from the earliest scheduled date  to the latest scheduled date in the currently defined operating hours. |
**amenity_schedules** | [**\MtnManager\Model\AmenitySchedule[]**](AmenitySchedule.md) | Per-amenity operating schedules. Only included when amenity hours are configured. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
