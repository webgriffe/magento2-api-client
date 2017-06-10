# Webgriffe\MagentoApiClient\SalesRuleCouponRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**salesRuleCouponRepositoryV1DeleteByIdDelete**](SalesRuleCouponRepositoryV1Api.md#salesRuleCouponRepositoryV1DeleteByIdDelete) | **DELETE** /V1/coupons/{couponId} | 
[**salesRuleCouponRepositoryV1GetByIdGet**](SalesRuleCouponRepositoryV1Api.md#salesRuleCouponRepositoryV1GetByIdGet) | **GET** /V1/coupons/{couponId} | 
[**salesRuleCouponRepositoryV1GetListGet**](SalesRuleCouponRepositoryV1Api.md#salesRuleCouponRepositoryV1GetListGet) | **GET** /V1/coupons/search | 
[**salesRuleCouponRepositoryV1SavePost**](SalesRuleCouponRepositoryV1Api.md#salesRuleCouponRepositoryV1SavePost) | **POST** /V1/coupons | 
[**salesRuleCouponRepositoryV1SavePut**](SalesRuleCouponRepositoryV1Api.md#salesRuleCouponRepositoryV1SavePut) | **PUT** /V1/coupons/{couponId} | 


# **salesRuleCouponRepositoryV1DeleteByIdDelete**
> bool salesRuleCouponRepositoryV1DeleteByIdDelete($couponId)



Delete coupon by coupon id.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesRuleCouponRepositoryV1Api();
$couponId = 56; // int | 

try {
    $result = $api_instance->salesRuleCouponRepositoryV1DeleteByIdDelete($couponId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesRuleCouponRepositoryV1Api->salesRuleCouponRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **couponId** | **int**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **salesRuleCouponRepositoryV1GetByIdGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponInterface salesRuleCouponRepositoryV1GetByIdGet($couponId)



Get coupon by coupon id.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesRuleCouponRepositoryV1Api();
$couponId = 56; // int | 

try {
    $result = $api_instance->salesRuleCouponRepositoryV1GetByIdGet($couponId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesRuleCouponRepositoryV1Api->salesRuleCouponRepositoryV1GetByIdGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **couponId** | **int**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponInterface**](../Model/SalesRuleDataCouponInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **salesRuleCouponRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponSearchResultInterface salesRuleCouponRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage)



Retrieve a coupon using the specified search criteria. This call returns an array of objects, but detailed information about each object’s attributes might not be included. See http://devdocs.magento.com/codelinks/attributes.html#CouponRepositoryInterface to determine which call to use to get detailed information about all attributes for an object.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesRuleCouponRepositoryV1Api();
$searchCriteriaFilterGroupsFiltersField = "searchCriteriaFilterGroupsFiltersField_example"; // string | Field
$searchCriteriaFilterGroupsFiltersValue = "searchCriteriaFilterGroupsFiltersValue_example"; // string | Value
$searchCriteriaFilterGroupsFiltersConditionType = "searchCriteriaFilterGroupsFiltersConditionType_example"; // string | Condition type
$searchCriteriaSortOrdersField = "searchCriteriaSortOrdersField_example"; // string | Sorting field.
$searchCriteriaSortOrdersDirection = "searchCriteriaSortOrdersDirection_example"; // string | Sorting direction.
$searchCriteriaPageSize = 56; // int | Page size.
$searchCriteriaCurrentPage = 56; // int | Current page.

try {
    $result = $api_instance->salesRuleCouponRepositoryV1GetListGet($searchCriteriaFilterGroupsFiltersField, $searchCriteriaFilterGroupsFiltersValue, $searchCriteriaFilterGroupsFiltersConditionType, $searchCriteriaSortOrdersField, $searchCriteriaSortOrdersDirection, $searchCriteriaPageSize, $searchCriteriaCurrentPage);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesRuleCouponRepositoryV1Api->salesRuleCouponRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
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

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponSearchResultInterface**](../Model/SalesRuleDataCouponSearchResultInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **salesRuleCouponRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponInterface salesRuleCouponRepositoryV1SavePost($body)



Save a coupon.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesRuleCouponRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body90(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body90 | 

try {
    $result = $api_instance->salesRuleCouponRepositoryV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesRuleCouponRepositoryV1Api->salesRuleCouponRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body90**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body90.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponInterface**](../Model/SalesRuleDataCouponInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **salesRuleCouponRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponInterface salesRuleCouponRepositoryV1SavePut($couponId, $body)



Save a coupon.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesRuleCouponRepositoryV1Api();
$couponId = "couponId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body89(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body89 | 

try {
    $result = $api_instance->salesRuleCouponRepositoryV1SavePut($couponId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesRuleCouponRepositoryV1Api->salesRuleCouponRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **couponId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body89**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body89.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataCouponInterface**](../Model/SalesRuleDataCouponInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

