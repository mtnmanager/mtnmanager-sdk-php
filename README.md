# MtnManager PHP SDK

SDK for interacting with the MtnManager API, providing real-time access to your ski resort’s public operational data.

For more information, please visit [https://docs.mtnmanager.com/developer/](https://docs.mtnmanager.com/developer/)

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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getAmenities($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getAmenities: ', $e->getMessage(), PHP_EOL;
}

```

## API Endpoints

All URIs are relative to *https://your-resort.mtnmanager.com*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*MtnManagerApi* | [**getAmenities**](docs/Api/MtnManagerApi.md#getamenities) | **GET** /api/v1/report/amenities | Get amenities
*MtnManagerApi* | [**getFullReport**](docs/Api/MtnManagerApi.md#getfullreport) | **GET** /api/v1/report | Get full report
*MtnManagerApi* | [**getHours**](docs/Api/MtnManagerApi.md#gethours) | **GET** /api/v1/report/hours | Get operating hours
*MtnManagerApi* | [**getLifts**](docs/Api/MtnManagerApi.md#getlifts) | **GET** /api/v1/report/lifts | Get lifts
*MtnManagerApi* | [**getMobileApp**](docs/Api/MtnManagerApi.md#getmobileapp) | **GET** /api/v1/report/mobile-app | Get mobile app data
*MtnManagerApi* | [**getOverview**](docs/Api/MtnManagerApi.md#getoverview) | **GET** /api/v1/report/overview | Get overview
*MtnManagerApi* | [**getParkingLots**](docs/Api/MtnManagerApi.md#getparkinglots) | **GET** /api/v1/report/parking-lots | Get parking lots
*MtnManagerApi* | [**getRuns**](docs/Api/MtnManagerApi.md#getruns) | **GET** /api/v1/report/runs | Get runs
*MtnManagerApi* | [**getSnow**](docs/Api/MtnManagerApi.md#getsnow) | **GET** /api/v1/report/snow | Get snow conditions
*MtnManagerApi* | [**getSummerTrails**](docs/Api/MtnManagerApi.md#getsummertrails) | **GET** /api/v1/report/summer-trails | Get summer trails
*MtnManagerApi* | [**getTerrainParks**](docs/Api/MtnManagerApi.md#getterrainparks) | **GET** /api/v1/report/terrain-parks | Get terrain parks
*MtnManagerApi* | [**getTrailMap**](docs/Api/MtnManagerApi.md#gettrailmap) | **GET** /api/v1/report/trail-map/{uuid} | Get trail map
*MtnManagerApi* | [**getTrailMaps**](docs/Api/MtnManagerApi.md#gettrailmaps) | **GET** /api/v1/report/trail-maps | Get trail maps
*MtnManagerApi* | [**getWeather**](docs/Api/MtnManagerApi.md#getweather) | **GET** /api/v1/report/weather | Get weather

## Models

- [Amenity](docs/Model/Amenity.md)
- [AmenityCalendarEntry](docs/Model/AmenityCalendarEntry.md)
- [AmenityCategory](docs/Model/AmenityCategory.md)
- [AmenitySchedule](docs/Model/AmenitySchedule.md)
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
- [GeoBounds](docs/Model/GeoBounds.md)
- [GeoControlPoint](docs/Model/GeoControlPoint.md)
- [GeoPoint](docs/Model/GeoPoint.md)
- [HourlyForecast](docs/Model/HourlyForecast.md)
- [HourlyForecastImperial](docs/Model/HourlyForecastImperial.md)
- [HourlyForecastMetric](docs/Model/HourlyForecastMetric.md)
- [LabelOffset](docs/Model/LabelOffset.md)
- [Lift](docs/Model/Lift.md)
- [LiftStatus](docs/Model/LiftStatus.md)
- [LiftType](docs/Model/LiftType.md)
- [MarkerIcon](docs/Model/MarkerIcon.md)
- [MobileAppBanner](docs/Model/MobileAppBanner.md)
- [MobileAppResponse](docs/Model/MobileAppResponse.md)
- [OperatingHours](docs/Model/OperatingHours.md)
- [Overview](docs/Model/Overview.md)
- [OverviewLifts](docs/Model/OverviewLifts.md)
- [OverviewNews](docs/Model/OverviewNews.md)
- [OverviewRuns](docs/Model/OverviewRuns.md)
- [OverviewSummerTrails](docs/Model/OverviewSummerTrails.md)
- [OverviewTerrainParks](docs/Model/OverviewTerrainParks.md)
- [ParkingLot](docs/Model/ParkingLot.md)
- [ParkingLotStatus](docs/Model/ParkingLotStatus.md)
- [PathUuid](docs/Model/PathUuid.md)
- [Region](docs/Model/Region.md)
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
- [TrailMap](docs/Model/TrailMap.md)
- [TrailMapElement](docs/Model/TrailMapElement.md)
- [TrailMapElementOneOf](docs/Model/TrailMapElementOneOf.md)
- [TrailMapElementOneOf1](docs/Model/TrailMapElementOneOf1.md)
- [TrailMapElementOneOf2](docs/Model/TrailMapElementOneOf2.md)
- [TrailMapElementOneOf3](docs/Model/TrailMapElementOneOf3.md)
- [TrailMapElementOneOf4](docs/Model/TrailMapElementOneOf4.md)
- [TrailMapElementOneOf5](docs/Model/TrailMapElementOneOf5.md)
- [TrailMapElementOneOf6](docs/Model/TrailMapElementOneOf6.md)
- [TrailMapSummary](docs/Model/TrailMapSummary.md)
- [UnitPreference](docs/Model/UnitPreference.md)
- [Weather](docs/Model/Weather.md)
- [WeatherConditionCode](docs/Model/WeatherConditionCode.md)

## Authorization
Endpoints do not require authorization.
