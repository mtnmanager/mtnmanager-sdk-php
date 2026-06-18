# Weather

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**area_uuid** | **string** | The area this weather belongs to, or omitted for resort-wide weather. | [optional]
**area_name** | **string** | The area&#39;s name, or omitted for resort-wide weather. | [optional]
**area_display_order** | **int** | The area&#39;s display order, or omitted for resort-wide weather. | [optional]
**current** | [**\MtnManager\Model\CurrentWeather**](CurrentWeather.md) | Current weather conditions |
**hourly_forecast** | [**\MtnManager\Model\HourlyForecast[]**](HourlyForecast.md) | Hourly forecast for next 24 hours (including current hour) |
**daily_forecast** | [**\MtnManager\Model\DailyForecast[]**](DailyForecast.md) | Daily forecast for next 7 days (including today) |
**attribution** | **string** | Data source attribution |
**updated_at** | **\DateTime** | When this data was last updated |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
