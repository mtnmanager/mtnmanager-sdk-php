# MtnManager\MtnManagerApi



All URIs are relative to https://your-resort.mtnmanager.com, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**getFullReport()**](MtnManagerApi.md#getFullReport) | **GET** /api/v1/report | Get full report |
| [**getHours()**](MtnManagerApi.md#getHours) | **GET** /api/v1/report/hours | Get operating hours |
| [**getLifts()**](MtnManagerApi.md#getLifts) | **GET** /api/v1/report/lifts | Get lifts |
| [**getOverview()**](MtnManagerApi.md#getOverview) | **GET** /api/v1/report/overview | Get overview |
| [**getParkingLots()**](MtnManagerApi.md#getParkingLots) | **GET** /api/v1/report/parking-lots | Get parking lots |
| [**getRuns()**](MtnManagerApi.md#getRuns) | **GET** /api/v1/report/runs | Get runs |
| [**getSnow()**](MtnManagerApi.md#getSnow) | **GET** /api/v1/report/snow | Get snow conditions |
| [**getSummerTrails()**](MtnManagerApi.md#getSummerTrails) | **GET** /api/v1/report/summer-trails | Get summer trails |
| [**getTerrainParks()**](MtnManagerApi.md#getTerrainParks) | **GET** /api/v1/report/terrain-parks | Get terrain parks |
| [**getTrailMap()**](MtnManagerApi.md#getTrailMap) | **GET** /api/v1/report/trail-map/{uuid} | Get trail map |
| [**getTrailMaps()**](MtnManagerApi.md#getTrailMaps) | **GET** /api/v1/report/trail-maps | Get trail maps |
| [**getWeather()**](MtnManagerApi.md#getWeather) | **GET** /api/v1/report/weather | Get weather |


## `getFullReport()`

```php
getFullReport(): \MtnManager\Model\FullReport
```

Get full report

### Example

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

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\FullReport**](../Model/FullReport.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getHours()`

```php
getHours(): \MtnManager\Model\OperatingHours
```

Get operating hours

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getHours();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getHours: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\OperatingHours**](../Model/OperatingHours.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getLifts()`

```php
getLifts(): \MtnManager\Model\Lift[]
```

Get lifts

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getLifts();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getLifts: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\Lift[]**](../Model/Lift.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getOverview()`

```php
getOverview(): \MtnManager\Model\Overview
```

Get overview

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getOverview();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getOverview: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\Overview**](../Model/Overview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getParkingLots()`

```php
getParkingLots(): \MtnManager\Model\ParkingLot[]
```

Get parking lots

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getParkingLots();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getParkingLots: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\ParkingLot[]**](../Model/ParkingLot.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getRuns()`

```php
getRuns(): \MtnManager\Model\Run[]
```

Get runs

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getRuns();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getRuns: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\Run[]**](../Model/Run.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getSnow()`

```php
getSnow(): \MtnManager\Model\SnowReport[]
```

Get snow conditions

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getSnow();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getSnow: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\SnowReport[]**](../Model/SnowReport.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getSummerTrails()`

```php
getSummerTrails(): \MtnManager\Model\SummerTrail[]
```

Get summer trails

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getSummerTrails();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getSummerTrails: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\SummerTrail[]**](../Model/SummerTrail.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getTerrainParks()`

```php
getTerrainParks(): \MtnManager\Model\TerrainPark[]
```

Get terrain parks

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getTerrainParks();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getTerrainParks: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\TerrainPark[]**](../Model/TerrainPark.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getTrailMap()`

```php
getTrailMap($uuid): \MtnManager\Model\TrailMap
```

Get trail map

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$uuid = 'uuid_example'; // string | Resource UUID

try {
    $result = $apiInstance->getTrailMap($uuid);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getTrailMap: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **uuid** | **string**| Resource UUID | |

### Return type

[**\MtnManager\Model\TrailMap**](../Model/TrailMap.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getTrailMaps()`

```php
getTrailMaps(): \MtnManager\Model\TrailMapSummary[]
```

Get trail maps

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getTrailMaps();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getTrailMaps: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\TrailMapSummary[]**](../Model/TrailMapSummary.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getWeather()`

```php
getWeather(): \MtnManager\Model\Weather
```

Get weather

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new MtnManager\Api\MtnManagerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->getWeather();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getWeather: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\MtnManager\Model\Weather**](../Model/Weather.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
