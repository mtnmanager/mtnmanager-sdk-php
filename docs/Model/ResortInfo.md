# ResortInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the resort. |
**name** | **string** | Display name of the resort. |
**slug** | **string** | URL-friendly identifier for the resort, used in account subdomain. |
**timezone** | **string** | IANA timezone identifier for the resort&#39;s local time. |
**region** | [**\MtnManager\Model\Region**](Region.md) | Region, affects difficulty icon style. |
**unit_preference** | [**\MtnManager\Model\UnitPreference**](UnitPreference.md) | Preferred unit system for measurements (metric or imperial). |
**logo_url** | **string** | Full public URL to the resort&#39;s logo image. &#x60;null&#x60; if no logo is set. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
