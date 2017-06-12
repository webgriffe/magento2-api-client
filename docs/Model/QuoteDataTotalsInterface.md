# QuoteDataTotalsInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**grandTotal** | **float** | Grand total in quote currency | [optional] 
**baseGrandTotal** | **float** | Grand total in base currency | [optional] 
**subtotal** | **float** | Subtotal in quote currency | [optional] 
**baseSubtotal** | **float** | Subtotal in base currency | [optional] 
**discountAmount** | **float** | Discount amount in quote currency | [optional] 
**baseDiscountAmount** | **float** | Discount amount in base currency | [optional] 
**subtotalWithDiscount** | **float** | Subtotal in quote currency with applied discount | [optional] 
**baseSubtotalWithDiscount** | **float** | Subtotal in base currency with applied discount | [optional] 
**shippingAmount** | **float** | Shipping amount in quote currency | [optional] 
**baseShippingAmount** | **float** | Shipping amount in base currency | [optional] 
**shippingDiscountAmount** | **float** | Shipping discount amount in quote currency | [optional] 
**baseShippingDiscountAmount** | **float** | Shipping discount amount in base currency | [optional] 
**taxAmount** | **float** | Tax amount in quote currency | [optional] 
**baseTaxAmount** | **float** | Tax amount in base currency | [optional] 
**weeeTaxAppliedAmount** | **float** | Item weee tax applied amount in quote currency. | 
**shippingTaxAmount** | **float** | Shipping tax amount in quote currency | [optional] 
**baseShippingTaxAmount** | **float** | Shipping tax amount in base currency | [optional] 
**subtotalInclTax** | **float** | Subtotal including tax in quote currency | [optional] 
**baseSubtotalInclTax** | **float** | Subtotal including tax in base currency | [optional] 
**shippingInclTax** | **float** | Shipping including tax in quote currency | [optional] 
**baseShippingInclTax** | **float** | Shipping including tax in base currency | [optional] 
**baseCurrencyCode** | **string** | Base currency code | [optional] 
**quoteCurrencyCode** | **string** | Quote currency code | [optional] 
**couponCode** | **string** | Applied coupon code | [optional] 
**itemsQty** | **int** | Items qty | [optional] 
**items** | [**\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsItemInterface[]**](QuoteDataTotalsItemInterface.md) | Totals by items | [optional] 
**totalSegments** | [**\Webgriffe\MagentoApiClient\Model\QuoteDataTotalSegmentInterface[]**](QuoteDataTotalSegmentInterface.md) | Dynamically calculated totals | 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsExtensionInterface**](QuoteDataTotalsExtensionInterface.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


