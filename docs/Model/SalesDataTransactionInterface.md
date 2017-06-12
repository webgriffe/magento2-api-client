# SalesDataTransactionInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transactionId** | **int** | Transaction ID. | 
**parentId** | **int** | The parent ID for the transaction. Otherwise, null. | [optional] 
**orderId** | **int** | Order ID. | 
**paymentId** | **int** | Payment ID. | 
**txnId** | **string** | Transaction business ID. | 
**parentTxnId** | **string** | Parent transaction business ID. | 
**txnType** | **string** | Transaction type. | 
**isClosed** | **int** | Is-closed flag value. | 
**additionalInformation** | **string[]** | Array of additional information. Otherwise, null. | [optional] 
**createdAt** | **string** | Created-at timestamp. | 
**childTransactions** | [**\Webgriffe\MagentoApiClient\Model\SalesDataTransactionInterface[]**](SalesDataTransactionInterface.md) | Array of child transactions. | 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Model\SalesDataTransactionExtensionInterface**](SalesDataTransactionExtensionInterface.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


