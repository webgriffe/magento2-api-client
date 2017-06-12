# Webgriffe\MagentoApiClient\CustomerGroupManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**customerGroupManagementV1GetDefaultGroupGet**](CustomerGroupManagementV1Api.md#customerGroupManagementV1GetDefaultGroupGet) | **GET** /V1/customerGroups/default/{storeId} | 
[**customerGroupManagementV1GetDefaultGroupGet_0**](CustomerGroupManagementV1Api.md#customerGroupManagementV1GetDefaultGroupGet_0) | **GET** /V1/customerGroups/default | 
[**customerGroupManagementV1IsReadonlyGet**](CustomerGroupManagementV1Api.md#customerGroupManagementV1IsReadonlyGet) | **GET** /V1/customerGroups/{id}/permissions | 


# **customerGroupManagementV1GetDefaultGroupGet**
> \Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface customerGroupManagementV1GetDefaultGroupGet($storeId)



Get default customer group.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupManagementV1Api();
$storeId = 56; // int | 

try {
    $result = $api_instance->customerGroupManagementV1GetDefaultGroupGet($storeId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupManagementV1Api->customerGroupManagementV1GetDefaultGroupGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **storeId** | **int**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface**](../Model/CustomerDataGroupInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerGroupManagementV1GetDefaultGroupGet_0**
> \Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface customerGroupManagementV1GetDefaultGroupGet_0($storeId)



Get default customer group.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupManagementV1Api();
$storeId = 56; // int | 

try {
    $result = $api_instance->customerGroupManagementV1GetDefaultGroupGet_0($storeId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupManagementV1Api->customerGroupManagementV1GetDefaultGroupGet_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **storeId** | **int**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Model\CustomerDataGroupInterface**](../Model/CustomerDataGroupInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerGroupManagementV1IsReadonlyGet**
> bool customerGroupManagementV1IsReadonlyGet($id)



Check if customer group can be deleted.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerGroupManagementV1Api();
$id = 56; // int | 

try {
    $result = $api_instance->customerGroupManagementV1IsReadonlyGet($id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerGroupManagementV1Api->customerGroupManagementV1IsReadonlyGet: ', $e->getMessage(), PHP_EOL;
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

