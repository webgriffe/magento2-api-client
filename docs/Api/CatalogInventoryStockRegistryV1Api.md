# Webgriffe\MagentoApiClient\CatalogInventoryStockRegistryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogInventoryStockRegistryV1GetLowStockItemsGet**](CatalogInventoryStockRegistryV1Api.md#catalogInventoryStockRegistryV1GetLowStockItemsGet) | **GET** /V1/stockItems/lowStock/ | 
[**catalogInventoryStockRegistryV1GetStockItemBySkuGet**](CatalogInventoryStockRegistryV1Api.md#catalogInventoryStockRegistryV1GetStockItemBySkuGet) | **GET** /V1/stockItems/{productSku} | 
[**catalogInventoryStockRegistryV1GetStockStatusBySkuGet**](CatalogInventoryStockRegistryV1Api.md#catalogInventoryStockRegistryV1GetStockStatusBySkuGet) | **GET** /V1/stockStatuses/{productSku} | 
[**catalogInventoryStockRegistryV1UpdateStockItemBySkuPut**](CatalogInventoryStockRegistryV1Api.md#catalogInventoryStockRegistryV1UpdateStockItemBySkuPut) | **PUT** /V1/products/{productSku}/stockItems/{itemId} | 


# **catalogInventoryStockRegistryV1GetLowStockItemsGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogInventoryDataStockStatusCollectionInterface catalogInventoryStockRegistryV1GetLowStockItemsGet($scopeId, $qty, $currentPage, $pageSize)



Retrieves a list of SKU's with low inventory qty

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogInventoryStockRegistryV1Api();
$scopeId = 56; // int | 
$qty = 3.4; // float | 
$currentPage = 56; // int | 
$pageSize = 56; // int | 

try {
    $result = $api_instance->catalogInventoryStockRegistryV1GetLowStockItemsGet($scopeId, $qty, $currentPage, $pageSize);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogInventoryStockRegistryV1Api->catalogInventoryStockRegistryV1GetLowStockItemsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **scopeId** | **int**|  |
 **qty** | **float**|  |
 **currentPage** | **int**|  | [optional]
 **pageSize** | **int**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogInventoryDataStockStatusCollectionInterface**](../Model/CatalogInventoryDataStockStatusCollectionInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogInventoryStockRegistryV1GetStockItemBySkuGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogInventoryDataStockItemInterface catalogInventoryStockRegistryV1GetStockItemBySkuGet($productSku, $scopeId)





### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogInventoryStockRegistryV1Api();
$productSku = "productSku_example"; // string | 
$scopeId = 56; // int | 

try {
    $result = $api_instance->catalogInventoryStockRegistryV1GetStockItemBySkuGet($productSku, $scopeId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogInventoryStockRegistryV1Api->catalogInventoryStockRegistryV1GetStockItemBySkuGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productSku** | **string**|  |
 **scopeId** | **int**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogInventoryDataStockItemInterface**](../Model/CatalogInventoryDataStockItemInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogInventoryStockRegistryV1GetStockStatusBySkuGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogInventoryDataStockStatusInterface catalogInventoryStockRegistryV1GetStockStatusBySkuGet($productSku, $scopeId)





### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogInventoryStockRegistryV1Api();
$productSku = "productSku_example"; // string | 
$scopeId = 56; // int | 

try {
    $result = $api_instance->catalogInventoryStockRegistryV1GetStockStatusBySkuGet($productSku, $scopeId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogInventoryStockRegistryV1Api->catalogInventoryStockRegistryV1GetStockStatusBySkuGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productSku** | **string**|  |
 **scopeId** | **int**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogInventoryDataStockStatusInterface**](../Model/CatalogInventoryDataStockStatusInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogInventoryStockRegistryV1UpdateStockItemBySkuPut**
> int catalogInventoryStockRegistryV1UpdateStockItemBySkuPut($productSku, $itemId, $body)





### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogInventoryStockRegistryV1Api();
$productSku = "productSku_example"; // string | 
$itemId = "itemId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body41(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body41 | 

try {
    $result = $api_instance->catalogInventoryStockRegistryV1UpdateStockItemBySkuPut($productSku, $itemId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogInventoryStockRegistryV1Api->catalogInventoryStockRegistryV1UpdateStockItemBySkuPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productSku** | **string**|  |
 **itemId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body41**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body41.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

