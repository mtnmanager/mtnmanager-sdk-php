# # Run

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the run. |
**name** | **string** | Display name of the run. |
**slug** | **string** | URL-friendly name of the run. |
**number** | **int** | Optional run number. | [optional]
**difficulty** | [**\MtnManager\Model\RunDifficulty**](RunDifficulty.md) | Difficulty rating of the run. |
**status** | [**\MtnManager\Model\RunStatus**](RunStatus.md) | Current operational status (open, closed, or unknown). |
**last_groomed** | **\DateTime** | When the run was last groomed.  &#x60;null&#x60; if never groomed, or if the runs grooming feature is disabled. | [optional]
**groomed_today** | **bool** | Whether the run was groomed within the last 24 hours. |
**snowmaking** | **bool** | Whether the run has snowmaking capabilities. |
**night_skiing** | **bool** | Whether the run is available for night skiing. |
**condition_notes** | **string** | Notes about current conditions on this run. |
**area_uuid** | **string** | UUID of the area this run belongs to, if assigned. | [optional]
**area_name** | **string** | Name of the area this run belongs to, if assigned. | [optional]
**area_display_order** | **int** | Display order of the area this run belongs to, if assigned, for sorting purposes. | [optional]
**updated_at** | **\DateTime** | When this run&#39;s information was last updated. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
