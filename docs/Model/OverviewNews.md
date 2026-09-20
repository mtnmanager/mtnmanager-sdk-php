# OverviewNews

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Stable identifier of this news feed. |
**name** | **string** | The name the resort gave this news feed, for telling several apart.  May be &#x60;null&#x60; on the primary news feed. | [optional]
**is_primary** | **bool** | Whether this is the resort&#39;s primary news feed. Exactly one news is. |
**raw** | **string** | Markdown source. Images the resort uploaded point at their public URLs,  so any Markdown renderer can display them. |
**html** | **string** | Rendered HTML (from Markdown) |
**updated_at** | **\DateTime** | When the news was last updated. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
