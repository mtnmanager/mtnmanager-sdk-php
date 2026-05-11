# TrailMap

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** |  |
**name** | **string** |  |
**slug** | **string** |  |
**season** | [**\MtnManager\Model\SeasonType**](SeasonType.md) |  |
**display_order** | **int** |  |
**version** | **int** | Monotonically incremented on every update. Clients can compare this  against a cached value to decide whether to reload the trail map. |
**background_image_url** | **string** |  |
**resort** | [**\MtnManager\Model\ResortInfo**](ResortInfo.md) |  |
**elements** | [**\MtnManager\Model\TrailMapElement[]**](TrailMapElement.md) |  |
**geo_control_points** | [**\MtnManager\Model\GeoControlPoint[]**](GeoControlPoint.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
