# Webgriffe\MagentoApiClient\CatalogProductRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductRepositoryV1DeleteByIdDelete**](CatalogProductRepositoryV1Api.md#catalogProductRepositoryV1DeleteByIdDelete) | **DELETE** /V1/products/{sku} | 
[**catalogProductRepositoryV1GetGet**](CatalogProductRepositoryV1Api.md#catalogProductRepositoryV1GetGet) | **GET** /V1/products/{sku} | 
[**catalogProductRepositoryV1GetListGet**](CatalogProductRepositoryV1Api.md#catalogProductRepositoryV1GetListGet) | **GET** /V1/products | 
[**catalogProductRepositoryV1SavePost**](CatalogProductRepositoryV1Api.md#catalogProductRepositoryV1SavePost) | **POST** /V1/products | 
[**catalogProductRepositoryV1SavePut**](CatalogProductRepositoryV1Api.md#catalogProductRepositoryV1SavePut) | **PUT** /V1/products/{sku} | 


# **catalogProductRepositoryV1DeleteByIdDelete**
> bool catalogProductRepositoryV1DeleteByIdDelete($sku)





### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductRepositoryV1Api();
$sku = "sku_example"; // string | 

try {
    $result = $api_instance->catalogProductRepositoryV1DeleteByIdDelete($sku);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductRepositoryV1Api->catalogProductRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductInterface catalogProductRepositoryV1GetGet($sku, $editMode, $storeId, $forceReload)



Get info about product by product SKU

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductRepositoryV1Api();
$sku = "sku_example"; // string | 
$editMode = true; // bool | 
$storeId = 56; // int | 
$forceReload = true; // bool | 

try {
    $result = $api_instance->catalogProductRepositoryV1GetGet($sku, $editMode, $storeId, $forceReload);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductRepositoryV1Api->catalogProductRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **editMode** | **bool**|  | [optional]
 **storeId** | **int**|  | [optional]
 **forceReload** | **bool**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductInterface**](../Model/CatalogDataProductInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductSearchResultsInterface catalogProductRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage)



Get product list

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductRepositoryV1Api();
$searchCriteriaFilterGroupsFiltersField = "searchCriteriaFilterGroupsFiltersField_example"; // string | Field
$searchCriteriaFilterGroupsFiltersValue = "searchCriteriaFilterGroupsFiltersValue_example"; // string | Value
$searchCriteriaFilterGroupsFiltersConditionType = "searchCriteriaFilterGroupsFiltersConditionType_example"; // string | Condition type
$searchCriteriaSortOrdersField = "searchCriteriaSortOrdersField_example"; // string | Sorting field.
$searchCriteriaSortOrdersDirection = "searchCriteriaSortOrdersDirection_example"; // string | Sorting direction.
$searchCriteriaPageSize = 56; // int | Page size.
$searchCriteriaCurrentPage = 56; // int | Current page.

try {
    $result = $api_instance->catalogProductRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductRepositoryV1Api->catalogProductRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchCriteriaFilterGroupsFiltersField** | **string**| Field | [optional]
 **searchCriteriaFilterGroupsFiltersValue** | **string**| Value | [optional]
 **searchCriteriaFilterGroupsFiltersConditionType** | **string**| Condition type | [optional]
 **searchCriteriaSortOrdersField** | **string**| Sorting field. | [optional]
 **searchCriteriaSortOrdersDirection** | **string**| Sorting direction. | [optional]
 **searchCriteriaPageSize** | **int**| Page size. | [optional]
 **searchCriteriaCurrentPage** | **int**| Current page. | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductSearchResultsInterface**](../Model/CatalogDataProductSearchResultsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductInterface catalogProductRepositoryV1SavePost($body)



Create product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body18(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body18 | 

try {
    $result = $api_instance->catalogProductRepositoryV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductRepositoryV1Api->catalogProductRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body18**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body18.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductInterface**](../Model/CatalogDataProductInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductInterface catalogProductRepositoryV1SavePut($sku, $body)



Create product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductRepositoryV1Api();
$sku = "sku_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body19(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body19 | 

try {
    $result = $api_instance->catalogProductRepositoryV1SavePut($sku, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductRepositoryV1Api->catalogProductRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body19**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body19.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductInterface**](../Model/CatalogDataProductInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

