# CatalogInventoryDataStockItemInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**itemId** | **int** |  | [optional] 
**productId** | **int** |  | [optional] 
**stockId** | **int** | Stock identifier | [optional] 
**qty** | **float** |  | 
**isInStock** | **bool** | Stock Availability | 
**isQtyDecimal** | **bool** |  | 
**showDefaultNotificationMessage** | **bool** |  | 
**useConfigMinQty** | **bool** |  | 
**minQty** | **float** | Minimal quantity available for item status in stock | 
**useConfigMinSaleQty** | **int** |  | 
**minSaleQty** | **float** | Minimum Qty Allowed in Shopping Cart or NULL when there is no limitation | 
**useConfigMaxSaleQty** | **bool** |  | 
**maxSaleQty** | **float** | Maximum Qty Allowed in Shopping Cart data wrapper | 
**useConfigBackorders** | **bool** |  | 
**backorders** | **int** | Backorders status | 
**useConfigNotifyStockQty** | **bool** |  | 
**notifyStockQty** | **float** | Notify for Quantity Below data wrapper | 
**useConfigQtyIncrements** | **bool** |  | 
**qtyIncrements** | **float** | Quantity Increments data wrapper | 
**useConfigEnableQtyInc** | **bool** |  | 
**enableQtyIncrements** | **bool** | Whether Quantity Increments is enabled | 
**useConfigManageStock** | **bool** |  | 
**manageStock** | **bool** | Can Manage Stock | 
**lowStockDate** | **string** |  | 
**isDecimalDivided** | **bool** |  | 
**stockStatusChangedAuto** | **int** |  | 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogInventoryDataStockItemExtensionInterface**](CatalogInventoryDataStockItemExtensionInterface.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


