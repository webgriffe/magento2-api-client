# Webgriffe\MagentoApiClient\QuoteCartRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteCartRepositoryV1GetGet**](QuoteCartRepositoryV1Api.md#quoteCartRepositoryV1GetGet) | **GET** /V1/carts/{cartId} | 
[**quoteCartRepositoryV1GetListGet**](QuoteCartRepositoryV1Api.md#quoteCartRepositoryV1GetListGet) | **GET** /V1/carts/search | 
[**quoteCartRepositoryV1SavePut**](QuoteCartRepositoryV1Api.md#quoteCartRepositoryV1SavePut) | **PUT** /V1/carts/mine | 


# **quoteCartRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartInterface quoteCartRepositoryV1GetGet($cartId)



Enables an administrative user to return information for a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartRepositoryV1Api();
$cartId = 56; // int | 

try {
    $result = $api_instance->quoteCartRepositoryV1GetGet($cartId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartRepositoryV1Api->quoteCartRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **int**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartInterface**](../Model/QuoteDataCartInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartSearchResultsInterface quoteCartRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage)



Enables administrative users to list carts that match specified search criteria. This call returns an array of objects, but detailed information about each object’s attributes might not be included.  See http://devdocs.magento.com/codelinks/attributes.html#CartRepositoryInterface to determine which call to use to get detailed information about all attributes for an object.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartRepositoryV1Api();
$searchCriteriaFilterGroupsFiltersField = "searchCriteriaFilterGroupsFiltersField_example"; // string | Field
$searchCriteriaFilterGroupsFiltersValue = "searchCriteriaFilterGroupsFiltersValue_example"; // string | Value
$searchCriteriaFilterGroupsFiltersConditionType = "searchCriteriaFilterGroupsFiltersConditionType_example"; // string | Condition type
$searchCriteriaSortOrdersField = "searchCriteriaSortOrdersField_example"; // string | Sorting field.
$searchCriteriaSortOrdersDirection = "searchCriteriaSortOrdersDirection_example"; // string | Sorting direction.
$searchCriteriaPageSize = 56; // int | Page size.
$searchCriteriaCurrentPage = 56; // int | Current page.

try {
    $result = $api_instance->quoteCartRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartRepositoryV1Api->quoteCartRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
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

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartSearchResultsInterface**](../Model/QuoteDataCartSearchResultsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\ErrorResponse quoteCartRepositoryV1SavePut($body)



Save quote

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body47(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body47 | 

try {
    $result = $api_instance->quoteCartRepositoryV1SavePut($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartRepositoryV1Api->quoteCartRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body47**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body47.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\ErrorResponse**](../Model/ErrorResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

