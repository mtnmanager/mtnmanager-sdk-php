# TrailMapSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** |  |
**name** | **string** |  |
**season** | [**\MtnManager\Model\SeasonType**](SeasonType.md) |  |
**display_order** | **int** |  |
**version** | **int** | Monotonically incremented on every update. Clients can compare this  against a cached value to decide whether to reload the trail map. |
**hosted_url** | **string** |  |
**geo_bounds** | [**\MtnManager\Model\GeoBounds**](GeoBounds.md) | Lat/lng bounding box of this map&#39;s georeferenced area, plus the  centroid of its control points (used for tie-breaking when multiple  maps cover the same point). Omitted when the map has no georeferencing. | [optional]
**entity_uuids** | **string[]** | Deduplicated UUIDs of every entity (lift, run, terrain park,  summer trail, amenity, parking lot) referenced by this map&#39;s elements. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
