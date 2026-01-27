# MtnManager PHP SDK

SDK for interacting with the MtnManager API, providing real-time access to your ski resort’s public operational data.

For more information, please visit [https://mtnmanager.com](https://mtnmanager.com)

## Installation & Usage

### Requirements

PHP 8.1 and later.

### Composer

To install the bindings via [Composer](https://getcomposer.org/), add the following to `composer.json`:

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/mtnmanager/mtnmanager-sdk-php.git"
    }
  ],
  "require": {
    "mtnmanager/mtnmanager-sdk-php": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
<?php
require_once('/path/to/MtnManagerSDK/vendor/autoload.php');
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');




$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getFullReport();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getFullReport: ', $e->getMessage(), PHP_EOL;
}

```

## API Endpoints

All URIs are relative to *https://your-resort.mtnmanager.com*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*MtnManagerApi* | [**getFullReport**](docs/Api/MtnManagerApi.md#getfullreport) | **GET** /api/v1/report | Get full report
*MtnManagerApi* | [**getHours**](docs/Api/MtnManagerApi.md#gethours) | **GET** /api/v1/report/hours | Get operating hours
*MtnManagerApi* | [**getLifts**](docs/Api/MtnManagerApi.md#getlifts) | **GET** /api/v1/report/lifts | Get lifts
*MtnManagerApi* | [**getOverview**](docs/Api/MtnManagerApi.md#getoverview) | **GET** /api/v1/report/overview | Get overview
*MtnManagerApi* | [**getRuns**](docs/Api/MtnManagerApi.md#getruns) | **GET** /api/v1/report/runs | Get runs
*MtnManagerApi* | [**getSnow**](docs/Api/MtnManagerApi.md#getsnow) | **GET** /api/v1/report/snow | Get snow conditions
*MtnManagerApi* | [**getSummerTrails**](docs/Api/MtnManagerApi.md#getsummertrails) | **GET** /api/v1/report/summer-trails | Get summer trails
*MtnManagerApi* | [**getTerrainParks**](docs/Api/MtnManagerApi.md#getterrainparks) | **GET** /api/v1/report/terrain-parks | Get terrain parks
*MtnManagerApi* | [**getWeather**](docs/Api/MtnManagerApi.md#getweather) | **GET** /api/v1/report/weather | Get weather

## Models

- [CalendarDay](docs/Model/CalendarDay.md)
- [ClosureReason](docs/Model/ClosureReason.md)
- [CurrentWeather](docs/Model/CurrentWeather.md)
- [CurrentWeatherImperial](docs/Model/CurrentWeatherImperial.md)
- [CurrentWeatherMetric](docs/Model/CurrentWeatherMetric.md)
- [DailyForecast](docs/Model/DailyForecast.md)
- [DailyForecastImperial](docs/Model/DailyForecastImperial.md)
- [DailyForecastMetric](docs/Model/DailyForecastMetric.md)
- [DayOfWeek](docs/Model/DayOfWeek.md)
- [FeatureSize](docs/Model/FeatureSize.md)
- [FeatureType](docs/Model/FeatureType.md)
- [FullReport](docs/Model/FullReport.md)
- [HourlyForecast](docs/Model/HourlyForecast.md)
- [HourlyForecastImperial](docs/Model/HourlyForecastImperial.md)
- [HourlyForecastMetric](docs/Model/HourlyForecastMetric.md)
- [Lift](docs/Model/Lift.md)
- [LiftStatus](docs/Model/LiftStatus.md)
- [LiftType](docs/Model/LiftType.md)
- [OperatingHours](docs/Model/OperatingHours.md)
- [Overview](docs/Model/Overview.md)
- [ResortInfo](docs/Model/ResortInfo.md)
- [ResortStatus](docs/Model/ResortStatus.md)
- [Run](docs/Model/Run.md)
- [RunDifficulty](docs/Model/RunDifficulty.md)
- [RunStatus](docs/Model/RunStatus.md)
- [Schedule](docs/Model/Schedule.md)
- [SeasonType](docs/Model/SeasonType.md)
- [SnowMetrics](docs/Model/SnowMetrics.md)
- [SnowReport](docs/Model/SnowReport.md)
- [SummerTrail](docs/Model/SummerTrail.md)
- [SummerTrailDifficulty](docs/Model/SummerTrailDifficulty.md)
- [SummerTrailStatus](docs/Model/SummerTrailStatus.md)
- [SummerTrailType](docs/Model/SummerTrailType.md)
- [SurfaceCondition](docs/Model/SurfaceCondition.md)
- [TerrainPark](docs/Model/TerrainPark.md)
- [TerrainParkFeature](docs/Model/TerrainParkFeature.md)
- [TerrainParkFeatureStatus](docs/Model/TerrainParkFeatureStatus.md)
- [TerrainParkStatus](docs/Model/TerrainParkStatus.md)
- [UnitPreference](docs/Model/UnitPreference.md)
- [Weather](docs/Model/Weather.md)
- [WeatherConditionCode](docs/Model/WeatherConditionCode.md)

## Authorization
Endpoints do not require authorization.
