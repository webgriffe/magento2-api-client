# Webgriffe\MagentoApiClient\CatalogCategoryManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogCategoryManagementV1GetTreeGet**](CatalogCategoryManagementV1Api.md#catalogCategoryManagementV1GetTreeGet) | **GET** /V1/categories | 
[**catalogCategoryManagementV1MovePut**](CatalogCategoryManagementV1Api.md#catalogCategoryManagementV1MovePut) | **PUT** /V1/categories/{categoryId}/move | 


# **catalogCategoryManagementV1GetTreeGet**
> \Webgriffe\MagentoApiClient\Model\CatalogDataCategoryTreeInterface catalogCategoryManagementV1GetTreeGet($rootCategoryId, $depth)



Retrieve list of categories

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogCategoryManagementV1Api();
$rootCategoryId = 56; // int | 
$depth = 56; // int | 

try {
    $result = $api_instance->catalogCategoryManagementV1GetTreeGet($rootCategoryId, $depth);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogCategoryManagementV1Api->catalogCategoryManagementV1GetTreeGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rootCategoryId** | **int**|  | [optional]
 **depth** | **int**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\CatalogDataCategoryTreeInterface**](../Model/CatalogDataCategoryTreeInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogCategoryManagementV1MovePut**
> bool catalogCategoryManagementV1MovePut($categoryId, $body)



Move category

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogCategoryManagementV1Api();
$categoryId = 56; // int | 
$body = new \Webgriffe\MagentoApiClient\Model\Body32(); // \Webgriffe\MagentoApiClient\Model\Body32 | 

try {
    $result = $api_instance->catalogCategoryManagementV1MovePut($categoryId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogCategoryManagementV1Api->catalogCategoryManagementV1MovePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **categoryId** | **int**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body32**](../Model/\Webgriffe\MagentoApiClient\Model\Body32.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

