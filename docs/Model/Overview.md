# # Overview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | [**\MtnManager\Model\ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. |
**opens_at** | **string** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional]
**closes_at** | **string** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. | [optional]
**season** | [**\MtnManager\Model\SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). |
**news** | **string** | Written news — daily update, announcements, etc. (Markdown source). |
**news_html** | **string** | Written news — daily update, announcements, etc. (rendered as HTML from Markdown). |
**news_updated_at** | **\DateTime** | When the written news was last updated. |
**open_runs** | **int** | Number of runs currently open.  Not included if the runs status feature is disabled. | [optional]
**groomed_runs** | **int** | Number of runs groomed within the last 24 hours.  Not included if the runs grooming feature is disabled. | [optional]
**total_runs** | **int** | Total number of runs at the resort. |
**runs_updated_at** | **\DateTime** | When the most recent update to run status was made. |
**open_lifts** | **int** | Number of lifts currently open.  Not included if the lifts status feature is disabled. | [optional]
**total_lifts** | **int** | Total number of lifts at the resort. |
**lifts_updated_at** | **\DateTime** | When the most recent update to lift status was made. |
**open_summer_trails** | **int** | Number of summer trails currently open.  Not included if the summer trails status feature is disabled. | [optional]
**total_summer_trails** | **int** | Total number of summer trails at the resort. |
**summer_trails_updated_at** | **\DateTime** | When the most recent update to summer trail status was made. |
**open_terrain_parks** | **int** | Number of terrain parks currently open.  Not included if the terrain parks status feature is disabled. | [optional]
**total_terrain_parks** | **int** | Total number of terrain parks at the resort. |
**terrain_parks_updated_at** | **\DateTime** | When the most recent update to terrain park status was made. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
