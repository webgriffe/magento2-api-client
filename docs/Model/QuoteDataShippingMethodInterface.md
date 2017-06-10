# QuoteDataShippingMethodInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**carrierCode** | **string** | Shipping carrier code. | 
**methodCode** | **string** | Shipping method code. | 
**carrierTitle** | **string** | Shipping carrier title. Otherwise, null. | [optional] 
**methodTitle** | **string** | Shipping method title. Otherwise, null. | [optional] 
**amount** | **float** | Shipping amount in store currency. | 
**baseAmount** | **float** | Shipping amount in base currency. | 
**available** | **bool** | The value of the availability flag for the current shipping method. | 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataShippingMethodExtensionInterface**](QuoteDataShippingMethodExtensionInterface.md) |  | [optional] 
**errorMessage** | **string** | Shipping Error message. | 
**priceExclTax** | **float** | Shipping price excl tax. | 
**priceInclTax** | **float** | Shipping price incl tax. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


