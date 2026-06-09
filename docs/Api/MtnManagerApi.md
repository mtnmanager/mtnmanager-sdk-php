# MtnManager\MtnManagerApi



All URIs are relative to https://your-resort.mtnmanager.com, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**getAmenities()**](MtnManagerApi.md#getAmenities) | **GET** /api/v1/report/amenities | Get amenities |
| [**getFullReport()**](MtnManagerApi.md#getFullReport) | **GET** /api/v1/report | Get full report |
| [**getHours()**](MtnManagerApi.md#getHours) | **GET** /api/v1/report/hours | Get operating hours |
| [**getLifts()**](MtnManagerApi.md#getLifts) | **GET** /api/v1/report/lifts | Get lifts |
| [**getOverview()**](MtnManagerApi.md#getOverview) | **GET** /api/v1/report/overview | Get overview |
| [**getParkingLots()**](MtnManagerApi.md#getParkingLots) | **GET** /api/v1/report/parking-lots | Get parking lots |
| [**getRuns()**](MtnManagerApi.md#getRuns) | **GET** /api/v1/report/runs | Get runs |
| [**getSnow()**](MtnManagerApi.md#getSnow) | **GET** /api/v1/report/snow | Get snow conditions |
| [**getSummerTrails()**](MtnManagerApi.md#getSummerTrails) | **GET** /api/v1/report/summer-trails | Get summer trails |
| [**getTerrainParks()**](MtnManagerApi.md#getTerrainParks) | **GET** /api/v1/report/terrain-parks | Get terrain parks |
| [**getTrailMaps()**](MtnManagerApi.md#getTrailMaps) | **GET** /api/v1/report/trail-maps | Get trail maps |
| [**getWeather()**](MtnManagerApi.md#getWeather) | **GET** /api/v1/report/weather | Get weather |


## `getAmenities()`

```php
getAmenities($accept_language): \MtnManager\Model\Amenity[]
```

Get amenities

### Example

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

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**\MtnManager\Model\Amenity[]**](../Model/Amenity.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `getFullReport()`

```php
getFullReport($accept_language): \MtnManager\Model\FullReport
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getFullReport($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getFullReport: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getHours($accept_language): \MtnManager\Model\OperatingHours
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getHours($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getHours: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getLifts($accept_language): \MtnManager\Model\Lift[]
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getLifts($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getLifts: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getOverview($accept_language): \MtnManager\Model\Overview
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getOverview($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getOverview: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getParkingLots($accept_language): \MtnManager\Model\ParkingLot[]
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getParkingLots($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getParkingLots: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getRuns($accept_language): \MtnManager\Model\Run[]
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getRuns($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getRuns: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getSnow($accept_language): \MtnManager\Model\SnowReport[]
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getSnow($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getSnow: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getSummerTrails($accept_language): \MtnManager\Model\SummerTrail[]
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getSummerTrails($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getSummerTrails: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getTerrainParks($accept_language): \MtnManager\Model\TerrainPark[]
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getTerrainParks($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getTerrainParks: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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

## `getTrailMaps()`

```php
getTrailMaps($accept_language): \MtnManager\Model\TrailMapSummary[]
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getTrailMaps($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getTrailMaps: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
getWeather($accept_language): \MtnManager\Model\Weather
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
$accept_language = fr-CA; // string | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.

try {
    $result = $apiInstance->getWeather($accept_language);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MtnManagerApi->getWeather: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **accept_language** | **string**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

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
