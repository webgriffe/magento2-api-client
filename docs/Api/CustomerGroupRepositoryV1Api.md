# Webgriffe\MagentoApiClient\CustomerGroupRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**customerGroupRepositoryV1DeleteByIdDelete**](CustomerGroupRepositoryV1Api.md#customerGroupRepositoryV1DeleteByIdDelete) | **DELETE** /V1/customerGroups/{id} | 
[**customerGroupRepositoryV1GetByIdGet**](CustomerGroupRepositoryV1Api.md#customerGroupRepositoryV1GetByIdGet) | **GET** /V1/customerGroups/{id} | 
[**customerGroupRepositoryV1GetListGet**](CustomerGroupRepositoryV1Api.md#customerGroupRepositoryV1GetListGet) | **GET** /V1/customerGroups/search | 
[**customerGroupRepositoryV1SavePost**](CustomerGroupRepositoryV1Api.md#customerGroupRepositoryV1SavePost) | **POST** /V1/customerGroups | 
[**customerGroupRepositoryV1SavePut**](CustomerGroupRepositoryV1Api.md#customerGroupRepositoryV1SavePut) | **PUT** /V1/customerGroups/{id} | 


# **customerGroupRepositoryV1DeleteByIdDelete**
> bool customerGroupRepositoryV1DeleteByIdDelete($id)



Delete customer group by ID.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupRepositoryV1Api();
$id = 56; // int | 

try {
    $result = $api_instance->customerGroupRepositoryV1DeleteByIdDelete($id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupRepositoryV1Api->customerGroupRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
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

# **customerGroupRepositoryV1GetByIdGet**
> \Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface customerGroupRepositoryV1GetByIdGet($id)



Get customer group by group ID.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupRepositoryV1Api();
$id = 56; // int | 

try {
    $result = $api_instance->customerGroupRepositoryV1GetByIdGet($id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupRepositoryV1Api->customerGroupRepositoryV1GetByIdGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface**](../Model/CustomerDataGroupInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerGroupRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Model\CustomerDataGroupSearchResultsInterface customerGroupRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage)



Retrieve customer groups. The list of groups can be filtered to exclude the NOT_LOGGED_IN group using the first parameter and/or it can be filtered by tax class. This call returns an array of objects, but detailed information about each object’s attributes might not be included. See http://devdocs.magento.com/codelinks/attributes.html#GroupRepositoryInterface to determine which call to use to get detailed information about all attributes for an object.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupRepositoryV1Api();
$searchCriteriaFilterGroupsFiltersField = "searchCriteriaFilterGroupsFiltersField_example"; // string | Field
$searchCriteriaFilterGroupsFiltersValue = "searchCriteriaFilterGroupsFiltersValue_example"; // string | Value
$searchCriteriaFilterGroupsFiltersConditionType = "searchCriteriaFilterGroupsFiltersConditionType_example"; // string | Condition type
$searchCriteriaSortOrdersField = "searchCriteriaSortOrdersField_example"; // string | Sorting field.
$searchCriteriaSortOrdersDirection = "searchCriteriaSortOrdersDirection_example"; // string | Sorting direction.
$searchCriteriaPageSize = 56; // int | Page size.
$searchCriteriaCurrentPage = 56; // int | Current page.

try {
    $result = $api_instance->customerGroupRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupRepositoryV1Api->customerGroupRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
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

[**\Webgriffe\MagentoApiClient\Model\CustomerDataGroupSearchResultsInterface**](../Model/CustomerDataGroupSearchResultsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerGroupRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface customerGroupRepositoryV1SavePost($body)



Save customer group.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Model\Body3(); // \Webgriffe\MagentoApiClient\Model\Body3 | 

try {
    $result = $api_instance->customerGroupRepositoryV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupRepositoryV1Api->customerGroupRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body3**](../Model/\Webgriffe\MagentoApiClient\Model\Body3.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface**](../Model/CustomerDataGroupInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerGroupRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface customerGroupRepositoryV1SavePut($id, $body)



Save customer group.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupRepositoryV1Api();
$id = "id_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Model\Body2(); // \Webgriffe\MagentoApiClient\Model\Body2 | 

try {
    $result = $api_instance->customerGroupRepositoryV1SavePut($id, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupRepositoryV1Api->customerGroupRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body2**](../Model/\Webgriffe\MagentoApiClient\Model\Body2.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface**](../Model/CustomerDataGroupInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

