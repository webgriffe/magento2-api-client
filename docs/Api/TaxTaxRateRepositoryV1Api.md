# Webgriffe\MagentoApiClient\TaxTaxRateRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**taxTaxRateRepositoryV1DeleteByIdDelete**](TaxTaxRateRepositoryV1Api.md#taxTaxRateRepositoryV1DeleteByIdDelete) | **DELETE** /V1/taxRates/{rateId} | 
[**taxTaxRateRepositoryV1GetGet**](TaxTaxRateRepositoryV1Api.md#taxTaxRateRepositoryV1GetGet) | **GET** /V1/taxRates/{rateId} | 
[**taxTaxRateRepositoryV1GetListGet**](TaxTaxRateRepositoryV1Api.md#taxTaxRateRepositoryV1GetListGet) | **GET** /V1/taxRates/search | 
[**taxTaxRateRepositoryV1SavePost**](TaxTaxRateRepositoryV1Api.md#taxTaxRateRepositoryV1SavePost) | **POST** /V1/taxRates | 
[**taxTaxRateRepositoryV1SavePut**](TaxTaxRateRepositoryV1Api.md#taxTaxRateRepositoryV1SavePut) | **PUT** /V1/taxRates | 


# **taxTaxRateRepositoryV1DeleteByIdDelete**
> bool taxTaxRateRepositoryV1DeleteByIdDelete($rateId)



Delete tax rate

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\TaxTaxRateRepositoryV1Api();
$rateId = 56; // int | 

try {
    $result = $api_instance->taxTaxRateRepositoryV1DeleteByIdDelete($rateId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TaxTaxRateRepositoryV1Api->taxTaxRateRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rateId** | **int**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **taxTaxRateRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Model\TaxDataTaxRateInterface taxTaxRateRepositoryV1GetGet($rateId)



Get tax rate

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\TaxTaxRateRepositoryV1Api();
$rateId = 56; // int | 

try {
    $result = $api_instance->taxTaxRateRepositoryV1GetGet($rateId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TaxTaxRateRepositoryV1Api->taxTaxRateRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rateId** | **int**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\TaxDataTaxRateInterface**](../Model/TaxDataTaxRateInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **taxTaxRateRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Model\TaxDataTaxRateSearchResultsInterface taxTaxRateRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage)



Search TaxRates This call returns an array of objects, but detailed information about each object’s attributes might not be included. See http://devdocs.magento.com/codelinks/attributes.html#TaxRateRepositoryInterface to determine which call to use to get detailed information about all attributes for an object.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\TaxTaxRateRepositoryV1Api();
$searchCriteriaFilterGroupsFiltersField = "searchCriteriaFilterGroupsFiltersField_example"; // string | Field
$searchCriteriaFilterGroupsFiltersValue = "searchCriteriaFilterGroupsFiltersValue_example"; // string | Value
$searchCriteriaFilterGroupsFiltersConditionType = "searchCriteriaFilterGroupsFiltersConditionType_example"; // string | Condition type
$searchCriteriaSortOrdersField = "searchCriteriaSortOrdersField_example"; // string | Sorting field.
$searchCriteriaSortOrdersDirection = "searchCriteriaSortOrdersDirection_example"; // string | Sorting direction.
$searchCriteriaPageSize = 56; // int | Page size.
$searchCriteriaCurrentPage = 56; // int | Current page.

try {
    $result = $api_instance->taxTaxRateRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TaxTaxRateRepositoryV1Api->taxTaxRateRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
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

[**\Webgriffe\MagentoApiClient\Model\TaxDataTaxRateSearchResultsInterface**](../Model/TaxDataTaxRateSearchResultsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **taxTaxRateRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Model\TaxDataTaxRateInterface taxTaxRateRepositoryV1SavePost($body)



Create or update tax rate

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\TaxTaxRateRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Model\Body113(); // \Webgriffe\MagentoApiClient\Model\Body113 | 

try {
    $result = $api_instance->taxTaxRateRepositoryV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TaxTaxRateRepositoryV1Api->taxTaxRateRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body113**](../Model/\Webgriffe\MagentoApiClient\Model\Body113.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\TaxDataTaxRateInterface**](../Model/TaxDataTaxRateInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **taxTaxRateRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Model\TaxDataTaxRateInterface taxTaxRateRepositoryV1SavePut($body)



Create or update tax rate

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\TaxTaxRateRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Model\Body112(); // \Webgriffe\MagentoApiClient\Model\Body112 | 

try {
    $result = $api_instance->taxTaxRateRepositoryV1SavePut($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TaxTaxRateRepositoryV1Api->taxTaxRateRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body112**](../Model/\Webgriffe\MagentoApiClient\Model\Body112.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\TaxDataTaxRateInterface**](../Model/TaxDataTaxRateInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

