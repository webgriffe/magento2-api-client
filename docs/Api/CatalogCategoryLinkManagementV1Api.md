# Webgriffe\MagentoApiClient\CatalogCategoryLinkManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogCategoryLinkManagementV1GetAssignedProductsGet**](CatalogCategoryLinkManagementV1Api.md#catalogCategoryLinkManagementV1GetAssignedProductsGet) | **GET** /V1/categories/{categoryId}/products | 


# **catalogCategoryLinkManagementV1GetAssignedProductsGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataCategoryProductLinkInterface[] catalogCategoryLinkManagementV1GetAssignedProductsGet($categoryId)



Get products assigned to category

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogCategoryLinkManagementV1Api();
$categoryId = 56; // int | 

try {
    $result = $api_instance->catalogCategoryLinkManagementV1GetAssignedProductsGet($categoryId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogCategoryLinkManagementV1Api->catalogCategoryLinkManagementV1GetAssignedProductsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **categoryId** | **int**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataCategoryProductLinkInterface[]**](../Model/CatalogDataCategoryProductLinkInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

