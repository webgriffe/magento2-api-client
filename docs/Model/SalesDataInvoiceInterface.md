# SalesDataInvoiceInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**baseCurrencyCode** | **string** | Base currency code. | [optional] 
**baseDiscountAmount** | **float** | Base discount amount. | [optional] 
**baseGrandTotal** | **float** | Base grand total. | [optional] 
**baseDiscountTaxCompensationAmount** | **float** | Base discount tax compensation amount. | [optional] 
**baseShippingAmount** | **float** | Base shipping amount. | [optional] 
**baseShippingDiscountTaxCompensationAmnt** | **float** | Base shipping discount tax compensation amount. | [optional] 
**baseShippingInclTax** | **float** | Base shipping including tax. | [optional] 
**baseShippingTaxAmount** | **float** | Base shipping tax amount. | [optional] 
**baseSubtotal** | **float** | Base subtotal. | [optional] 
**baseSubtotalInclTax** | **float** | Base subtotal including tax. | [optional] 
**baseTaxAmount** | **float** | Base tax amount. | [optional] 
**baseTotalRefunded** | **float** | Base total refunded. | [optional] 
**baseToGlobalRate** | **float** | Base-to-global rate. | [optional] 
**baseToOrderRate** | **float** | Base-to-order rate. | [optional] 
**billingAddressId** | **int** | Billing address ID. | [optional] 
**canVoidFlag** | **int** | Can void flag value. | [optional] 
**createdAt** | **string** | Created-at timestamp. | [optional] 
**discountAmount** | **float** | Discount amount. | [optional] 
**discountDescription** | **string** | Discount description. | [optional] 
**emailSent** | **int** | Email-sent flag value. | [optional] 
**entityId** | **int** | Invoice ID. | [optional] 
**globalCurrencyCode** | **string** | Global currency code. | [optional] 
**grandTotal** | **float** | Grand total. | [optional] 
**discountTaxCompensationAmount** | **float** | Discount tax compensation amount. | [optional] 
**incrementId** | **string** | Increment ID. | [optional] 
**isUsedForRefund** | **int** | Is-used-for-refund flag value. | [optional] 
**orderCurrencyCode** | **string** | Order currency code. | [optional] 
**orderId** | **int** | Order ID. | 
**shippingAddressId** | **int** | Shipping address ID. | [optional] 
**shippingAmount** | **float** | Shipping amount. | [optional] 
**shippingDiscountTaxCompensationAmount** | **float** | Shipping discount tax compensation amount. | [optional] 
**shippingInclTax** | **float** | Shipping including tax. | [optional] 
**shippingTaxAmount** | **float** | Shipping tax amount. | [optional] 
**state** | **int** | State. | [optional] 
**storeCurrencyCode** | **string** | Store currency code. | [optional] 
**storeId** | **int** | Store ID. | [optional] 
**storeToBaseRate** | **float** | Store-to-base rate. | [optional] 
**storeToOrderRate** | **float** | Store-to-order rate. | [optional] 
**subtotal** | **float** | Subtotal. | [optional] 
**subtotalInclTax** | **float** | Subtotal including tax. | [optional] 
**taxAmount** | **float** | Tax amount. | [optional] 
**totalQty** | **float** | Total quantity. | 
**transactionId** | **string** | Transaction ID. | [optional] 
**updatedAt** | **string** | Updated-at timestamp. | [optional] 
**items** | [**\Webgriffe\MagentoApiClient\Model\SalesDataInvoiceItemInterface[]**](SalesDataInvoiceItemInterface.md) | Array of invoice items. | 
**comments** | [**\Webgriffe\MagentoApiClient\Model\SalesDataInvoiceCommentInterface[]**](SalesDataInvoiceCommentInterface.md) | Array of any invoice comments. Otherwise, null. | [optional] 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Model\SalesDataInvoiceExtensionInterface**](SalesDataInvoiceExtensionInterface.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


