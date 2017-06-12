# Webgriffe\MagentoApiClient\CatalogProductAttributeRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductAttributeRepositoryV1DeleteByIdDelete**](CatalogProductAttributeRepositoryV1Api.md#catalogProductAttributeRepositoryV1DeleteByIdDelete) | **DELETE** /V1/products/attributes/{attributeCode} | 
[**catalogProductAttributeRepositoryV1GetGet**](CatalogProductAttributeRepositoryV1Api.md#catalogProductAttributeRepositoryV1GetGet) | **GET** /V1/products/attributes/{attributeCode} | 
[**catalogProductAttributeRepositoryV1GetListGet**](CatalogProductAttributeRepositoryV1Api.md#catalogProductAttributeRepositoryV1GetListGet) | **GET** /V1/products/attributes | 
[**catalogProductAttributeRepositoryV1SavePost**](CatalogProductAttributeRepositoryV1Api.md#catalogProductAttributeRepositoryV1SavePost) | **POST** /V1/products/attributes | 
[**catalogProductAttributeRepositoryV1SavePut**](CatalogProductAttributeRepositoryV1Api.md#catalogProductAttributeRepositoryV1SavePut) | **PUT** /V1/products/attributes/{attributeCode} | 


# **catalogProductAttributeRepositoryV1DeleteByIdDelete**
> bool catalogProductAttributeRepositoryV1DeleteByIdDelete($attributeCode)



Delete Attribute by id

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeRepositoryV1Api();
$attributeCode = "attributeCode_example"; // string | 

try {
    $result = $api_instance->catalogProductAttributeRepositoryV1DeleteByIdDelete($attributeCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeRepositoryV1Api->catalogProductAttributeRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductAttributeRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface catalogProductAttributeRepositoryV1GetGet($attributeCode)



Retrieve specific attribute

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeRepositoryV1Api();
$attributeCode = "attributeCode_example"; // string | 

try {
    $result = $api_instance->catalogProductAttributeRepositoryV1GetGet($attributeCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeRepositoryV1Api->catalogProductAttributeRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface**](../Model/CatalogDataProductAttributeInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductAttributeRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeSearchResultsInterface catalogProductAttributeRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage)



Retrieve all attributes for entity type

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeRepositoryV1Api();
$searchCriteriaFilterGroupsFiltersField = "searchCriteriaFilterGroupsFiltersField_example"; // string | Field
$searchCriteriaFilterGroupsFiltersValue = "searchCriteriaFilterGroupsFiltersValue_example"; // string | Value
$searchCriteriaFilterGroupsFiltersConditionType = "searchCriteriaFilterGroupsFiltersConditionType_example"; // string | Condition type
$searchCriteriaSortOrdersField = "searchCriteriaSortOrdersField_example"; // string | Sorting field.
$searchCriteriaSortOrdersDirection = "searchCriteriaSortOrdersDirection_example"; // string | Sorting direction.
$searchCriteriaPageSize = 56; // int | Page size.
$searchCriteriaCurrentPage = 56; // int | Current page.

try {
    $result = $api_instance->catalogProductAttributeRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeRepositoryV1Api->catalogProductAttributeRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
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

[**\Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeSearchResultsInterface**](../Model/CatalogDataProductAttributeSearchResultsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductAttributeRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface catalogProductAttributeRepositoryV1SavePost($body)



Save attribute data

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Model\Body21(); // \Webgriffe\MagentoApiClient\Model\Body21 | 

try {
    $result = $api_instance->catalogProductAttributeRepositoryV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeRepositoryV1Api->catalogProductAttributeRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body21**](../Model/\Webgriffe\MagentoApiClient\Model\Body21.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface**](../Model/CatalogDataProductAttributeInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductAttributeRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface catalogProductAttributeRepositoryV1SavePut($attributeCode, $body)



Save attribute data

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeRepositoryV1Api();
$attributeCode = "attributeCode_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Model\Body20(); // \Webgriffe\MagentoApiClient\Model\Body20 | 

try {
    $result = $api_instance->catalogProductAttributeRepositoryV1SavePut($attributeCode, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeRepositoryV1Api->catalogProductAttributeRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body20**](../Model/\Webgriffe\MagentoApiClient\Model\Body20.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface**](../Model/CatalogDataProductAttributeInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

