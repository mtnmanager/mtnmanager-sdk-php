# # DailyForecast

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**date** | **\DateTime** | Date of forecast (YYYY-MM-DD format) |
**imperial** | [**\MtnManager\Model\DailyForecastImperial**](DailyForecastImperial.md) | Measurements in imperial units |
**metric** | [**\MtnManager\Model\DailyForecastMetric**](DailyForecastMetric.md) | Measurements in metric units |
**condition** | **string** | Human-readable condition |
**condition_code** | [**\MtnManager\Model\WeatherConditionCode**](WeatherConditionCode.md) | Condition code |
**precipitation_probability** | **int** | Probability of precipitation (0-100%) | [optional]
**sunrise** | **\DateTime** | Sunrise time |
**sunset** | **\DateTime** | Sunset time |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
