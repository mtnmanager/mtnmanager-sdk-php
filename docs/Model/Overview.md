# Overview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | [**\MtnManager\Model\ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. |
**opens_at** | **string** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional]
**closes_at** | **string** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional]
**season** | [**\MtnManager\Model\SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). |
**news** | [**\MtnManager\Model\OverviewNews**](OverviewNews.md) | Written news — daily update, announcements, etc. |
**runs** | [**\MtnManager\Model\OverviewRuns**](OverviewRuns.md) | Run statistics: counts, acres, and last-updated timestamp. |
**lifts** | [**\MtnManager\Model\OverviewLifts**](OverviewLifts.md) | Lift statistics: counts and last-updated timestamp. |
**summer_trails** | [**\MtnManager\Model\OverviewSummerTrails**](OverviewSummerTrails.md) | Summer trail statistics: counts and last-updated timestamp. |
**terrain_parks** | [**\MtnManager\Model\OverviewTerrainParks**](OverviewTerrainParks.md) | Terrain park statistics: counts and last-updated timestamp. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
