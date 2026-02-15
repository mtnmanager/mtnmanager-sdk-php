# # CalendarDay

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**date** | **\DateTime** | Calendar date (YYYY-MM-DD). |
**day_of_week** | [**\MtnManager\Model\DayOfWeek**](DayOfWeek.md) | Day of the week. |
**is_open** | **bool** | Whether the resort is open on this day. |
**opens_at** | **string** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. | [optional]
**closes_at** | **string** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. | [optional]
**closure_reason** | [**\MtnManager\Model\ClosureReason**](ClosureReason.md) |  | [optional]
**special_event** | **string** | Special event for this day. | [optional]
**amenities** | [**\MtnManager\Model\AmenityCalendarEntry[]**](AmenityCalendarEntry.md) | Per-amenity hours for this day. Only included when amenity hours are configured. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
