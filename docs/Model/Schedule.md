# # Schedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**days_string** | **string** | Human-readable description of which days this schedule applies to.  Examples: \&quot;Daily\&quot;, \&quot;Saturday &amp; Sunday\&quot;, \&quot;Monday, Wednesday, and Friday\&quot; |
**days_of_week** | [**\MtnManager\Model\DayOfWeek[]**](DayOfWeek.md) | Array of days of the week this schedule applies to.  For programmatic use. |
**time_string** | **string** | Human-readable time range.  Example: \&quot;9:00 a.m. to 4:00 p.m.\&quot; |
**opens_at** | **string** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. |
**closes_at** | **string** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. |
**in_effect** | **bool** | Whether this schedule is currently in effect.  &#x60;false&#x60; for upcoming schedules that haven&#39;t started yet. |
**effective_string** | **string** | Human-readable date range when this schedule is effective.  Example: \&quot;November 1, 2024 to April 15, 2025\&quot; |
**effective_from** | **\DateTime** | Start date of the effective period (YYYY-MM-DD). |
**effective_to** | **\DateTime** | End date of the effective period (YYYY-MM-DD). |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
