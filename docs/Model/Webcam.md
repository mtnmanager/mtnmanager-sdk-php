# Webcam

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** |  |
**name** | **string** |  |
**area_uuid** | **string** |  | [optional]
**area_name** | **string** |  | [optional]
**area_display_order** | **int** |  | [optional]
**latest_image_url** | **string** | URL of the newest frame (refreshes within ~60s via the edge cache). |
**latest_daylight_image_url** | **string** | URL of the last daylight frame. |
**latest_thumb_url** | **string** |  |
**latest_daylight_thumb_url** | **string** |  |
**latest_thumbhash** | **string** | ThumbHash of the &#x60;latest&#x60; frame (standard base64) — a compact blur  placeholder to render while the image loads. Empty string until the first  frame (or on cameras predating the feature). |
**latest_daylight_thumbhash** | **string** | ThumbHash of the &#x60;latest-daylight&#x60; frame (standard base64). Empty string  until the first daylight frame. |
**has_history** | **bool** | Whether this camera archives frames — i.e. whether its history endpoint  returns anything. When &#x60;false&#x60;, don&#39;t call the history API for it. |
**elevation_ft** | **int** | Camera elevation in both units; omitted when unset. | [optional]
**elevation_m** | **int** |  | [optional]
**last_frame_at** | **string** | Time of the most recently published frame; omitted until the first frame. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
