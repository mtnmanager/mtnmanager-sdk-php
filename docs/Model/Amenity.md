# Amenity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **string** | Description of the amenity. |
**uuid** | **string** | Unique identifier for the amenity. |
**name** | **string** | Display name of the amenity. |
**category** | [**\MtnManager\Model\AmenityCategory**](AmenityCategory.md) | Category classification (e.g. restaurant, lodge, ski_school). |
**website** | **string** | Website URL for the amenity, if available. |
**has_operating_hours** | **bool** | Whether this amenity reports operating hours. When false, clients should  not expect &#x60;opens_at&#x60;, &#x60;closes_at&#x60;, or &#x60;schedules&#x60; to ever be populated. |
**opens_at** | **string** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional]
**closes_at** | **string** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. | [optional]
**schedules** | [**\MtnManager\Model\Schedule[]**](Schedule.md) | Recurring operating schedules for this amenity (e.g. \&quot;Saturday &amp; Sunday,  9:00 a.m. to 4:00 p.m.\&quot;), with both human-readable and structured fields. |
**images** | [**\MtnManager\Model\EntityImage[]**](EntityImage.md) | Images attached to this amenity, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
