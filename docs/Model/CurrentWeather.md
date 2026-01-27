# # CurrentWeather

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**imperial** | [**\MtnManager\Model\CurrentWeatherImperial**](CurrentWeatherImperial.md) | Measurements in imperial units |
**metric** | [**\MtnManager\Model\CurrentWeatherMetric**](CurrentWeatherMetric.md) | Measurements in metric units |
**condition** | **string** | Human-readable weather condition |
**condition_code** | [**\MtnManager\Model\WeatherConditionCode**](WeatherConditionCode.md) | Weather condition code |
**wind_direction** | **int** | Wind direction in degrees (0-360) | [optional]
**wind_direction_cardinal** | **string** | Wind direction as cardinal direction (N, NE, E, SE, S, SW, W, NW) | [optional]
**timestamp** | **\DateTime** | Timestamp of observation |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
