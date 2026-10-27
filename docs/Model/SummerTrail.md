# SummerTrail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the trail. |
**name** | **string** | Display name of the trail. |
**slug** | **string** | URL-friendly name of the trail. |
**number** | **int** | Optional trail number. | [optional]
**activities** | [**\MtnManager\Model\SummerTrailActivity[]**](SummerTrailActivity.md) | Activities the trail is open to (e.g. hiking, mountain_biking,  on_leash_dogs). Can have multiple. |
**difficulty** | [**\MtnManager\Model\SummerTrailDifficulty**](SummerTrailDifficulty.md) | Difficulty rating of the trail (optional for summer trails). | [optional]
**difficulty_type** | [**\MtnManager\Model\SummerTrailDifficultyType**](SummerTrailDifficultyType.md) | The rating system the difficulty is shown in, which picks its icon:  &#x60;null&#x60; for the standard one, or a mountain-bike freeride / technical one. | [optional]
**status** | [**\MtnManager\Model\SummerTrailStatus**](SummerTrailStatus.md) | Current operational status (open, closed, or unknown). |
**condition_notes** | **string** | Notes about current conditions on this trail. |
**area_uuid** | **string** | UUID of the area this trail belongs to, if assigned. | [optional]
**area_name** | **string** | Name of the area this trail belongs to, if assigned. | [optional]
**area_display_order** | **int** | Display order of the area this trail belongs to, if assigned, for sorting purposes. | [optional]
**updated_at** | **\DateTime** | When this trail&#39;s information was last updated. |
**images** | [**\MtnManager\Model\EntityImage[]**](EntityImage.md) | Images attached to this trail, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
