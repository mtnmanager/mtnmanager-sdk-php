# # ParkingLot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | Unique identifier for the parking lot. |
**name** | **string** | Display name of the parking lot. |
**slug** | **string** | URL-friendly name of the parking lot. |
**status** | [**\MtnManager\Model\ParkingLotStatus**](ParkingLotStatus.md) | Current status (open, closed, or full). |
**capacity** | **int** | Maximum vehicle capacity, if set. | [optional]
**shuttle** | **bool** | Whether shuttle service is available from this lot. |
**paid** | **bool** | Whether parking is paid/requires payment. |
**reservation_required** | **bool** | Whether a reservation is required to park here. |
**updated_at** | **\DateTime** | When this parking lot&#39;s information was last updated. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
