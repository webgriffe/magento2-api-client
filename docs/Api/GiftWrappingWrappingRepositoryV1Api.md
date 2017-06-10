# Webgriffe\MagentoApiClient\GiftWrappingWrappingRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**giftWrappingWrappingRepositoryV1DeleteByIdDelete**](GiftWrappingWrappingRepositoryV1Api.md#giftWrappingWrappingRepositoryV1DeleteByIdDelete) | **DELETE** /V1/gift-wrappings/{id} | 
[**giftWrappingWrappingRepositoryV1GetGet**](GiftWrappingWrappingRepositoryV1Api.md#giftWrappingWrappingRepositoryV1GetGet) | **GET** /V1/gift-wrappings/{id} | 
[**giftWrappingWrappingRepositoryV1GetListGet**](GiftWrappingWrappingRepositoryV1Api.md#giftWrappingWrappingRepositoryV1GetListGet) | **GET** /V1/gift-wrappings | 
[**giftWrappingWrappingRepositoryV1SavePost**](GiftWrappingWrappingRepositoryV1Api.md#giftWrappingWrappingRepositoryV1SavePost) | **POST** /V1/gift-wrappings | 
[**giftWrappingWrappingRepositoryV1SavePut**](GiftWrappingWrappingRepositoryV1Api.md#giftWrappingWrappingRepositoryV1SavePut) | **PUT** /V1/gift-wrappings/{wrappingId} | 


# **giftWrappingWrappingRepositoryV1DeleteByIdDelete**
> bool giftWrappingWrappingRepositoryV1DeleteByIdDelete($id)



Delete gift wrapping

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftWrappingWrappingRepositoryV1Api();
$id = 56; // int | 

try {
    $result = $api_instance->giftWrappingWrappingRepositoryV1DeleteByIdDelete($id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftWrappingWrappingRepositoryV1Api->giftWrappingWrappingRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftWrappingWrappingRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingInterface giftWrappingWrappingRepositoryV1GetGet($id, $storeId)



Return data object for specified wrapping ID and store.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftWrappingWrappingRepositoryV1Api();
$id = 56; // int | 
$storeId = 56; // int | 

try {
    $result = $api_instance->giftWrappingWrappingRepositoryV1GetGet($id, $storeId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftWrappingWrappingRepositoryV1Api->giftWrappingWrappingRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  |
 **storeId** | **int**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingInterface**](../Model/GiftWrappingDataWrappingInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftWrappingWrappingRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingSearchResultsInterface giftWrappingWrappingRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage)



Return list of gift wrapping data objects based on search criteria

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftWrappingWrappingRepositoryV1Api();
$searchCriteriaFilterGroupsFiltersField = "searchCriteriaFilterGroupsFiltersField_example"; // string | Field
$searchCriteriaFilterGroupsFiltersValue = "searchCriteriaFilterGroupsFiltersValue_example"; // string | Value
$searchCriteriaFilterGroupsFiltersConditionType = "searchCriteriaFilterGroupsFiltersConditionType_example"; // string | Condition type
$searchCriteriaSortOrdersField = "searchCriteriaSortOrdersField_example"; // string | Sorting field.
$searchCriteriaSortOrdersDirection = "searchCriteriaSortOrdersDirection_example"; // string | Sorting direction.
$searchCriteriaPageSize = 56; // int | Page size.
$searchCriteriaCurrentPage = 56; // int | Current page.

try {
    $result = $api_instance->giftWrappingWrappingRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftWrappingWrappingRepositoryV1Api->giftWrappingWrappingRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
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

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingSearchResultsInterface**](../Model/GiftWrappingDataWrappingSearchResultsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftWrappingWrappingRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingInterface giftWrappingWrappingRepositoryV1SavePost($body)



Create/Update new gift wrapping with data object values

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftWrappingWrappingRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body129(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body129 | 

try {
    $result = $api_instance->giftWrappingWrappingRepositoryV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftWrappingWrappingRepositoryV1Api->giftWrappingWrappingRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body129**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body129.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingInterface**](../Model/GiftWrappingDataWrappingInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftWrappingWrappingRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingInterface giftWrappingWrappingRepositoryV1SavePut($wrappingId, $body)



Create/Update new gift wrapping with data object values

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftWrappingWrappingRepositoryV1Api();
$wrappingId = "wrappingId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body130(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body130 | 

try {
    $result = $api_instance->giftWrappingWrappingRepositoryV1SavePut($wrappingId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftWrappingWrappingRepositoryV1Api->giftWrappingWrappingRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **wrappingId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body130**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body130.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftWrappingDataWrappingInterface**](../Model/GiftWrappingDataWrappingInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

