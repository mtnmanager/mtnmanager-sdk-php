# # HourlyForecast

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**timestamp** | **\DateTime** | Forecast timestamp |
**imperial** | [**\MtnManager\Model\HourlyForecastImperial**](HourlyForecastImperial.md) | Measurements in imperial units |
**metric** | [**\MtnManager\Model\HourlyForecastMetric**](HourlyForecastMetric.md) | Measurements in metric units |
**condition** | **string** | Human-readable condition |
**condition_code** | [**\MtnManager\Model\WeatherConditionCode**](WeatherConditionCode.md) | Weather condition code |
**precipitation_probability** | **int** | Probability of precipitation (0-100%) | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
