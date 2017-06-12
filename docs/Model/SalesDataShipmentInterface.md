# SalesDataShipmentInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**billingAddressId** | **int** | Billing address ID. | [optional] 
**createdAt** | **string** | Created-at timestamp. | [optional] 
**customerId** | **int** | Customer ID. | [optional] 
**emailSent** | **int** | Email-sent flag value. | [optional] 
**entityId** | **int** | Shipment ID. | [optional] 
**incrementId** | **string** | Increment ID. | [optional] 
**orderId** | **int** | Order ID. | 
**packages** | [**\Webgriffe\MagentoApiClient\Model\SalesDataShipmentPackageInterface[]**](SalesDataShipmentPackageInterface.md) | Array of packages, if any. Otherwise, null. | [optional] 
**shipmentStatus** | **int** | Shipment status. | [optional] 
**shippingAddressId** | **int** | Shipping address ID. | [optional] 
**shippingLabel** | **string** | Shipping label. | [optional] 
**storeId** | **int** | Store ID. | [optional] 
**totalQty** | **float** | Total quantity. | [optional] 
**totalWeight** | **float** | Total weight. | [optional] 
**updatedAt** | **string** | Updated-at timestamp. | [optional] 
**items** | [**\Webgriffe\MagentoApiClient\Model\SalesDataShipmentItemInterface[]**](SalesDataShipmentItemInterface.md) | Array of items. | 
**tracks** | [**\Webgriffe\MagentoApiClient\Model\SalesDataShipmentTrackInterface[]**](SalesDataShipmentTrackInterface.md) | Array of tracks. | 
**comments** | [**\Webgriffe\MagentoApiClient\Model\SalesDataShipmentCommentInterface[]**](SalesDataShipmentCommentInterface.md) | Array of comments. | 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Model\SalesDataShipmentExtensionInterface**](SalesDataShipmentExtensionInterface.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


