# Webgriffe\MagentoApiClient\CustomerCustomerMetadataV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**customerCustomerMetadataV1GetAllAttributesMetadataGet**](CustomerCustomerMetadataV1Api.md#customerCustomerMetadataV1GetAllAttributesMetadataGet) | **GET** /V1/attributeMetadata/customer | 
[**customerCustomerMetadataV1GetAttributeMetadataGet**](CustomerCustomerMetadataV1Api.md#customerCustomerMetadataV1GetAttributeMetadataGet) | **GET** /V1/attributeMetadata/customer/attribute/{attributeCode} | 
[**customerCustomerMetadataV1GetAttributesGet**](CustomerCustomerMetadataV1Api.md#customerCustomerMetadataV1GetAttributesGet) | **GET** /V1/attributeMetadata/customer/form/{formCode} | 
[**customerCustomerMetadataV1GetCustomAttributesMetadataGet**](CustomerCustomerMetadataV1Api.md#customerCustomerMetadataV1GetCustomAttributesMetadataGet) | **GET** /V1/attributeMetadata/customer/custom | 


# **customerCustomerMetadataV1GetAllAttributesMetadataGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[] customerCustomerMetadataV1GetAllAttributesMetadataGet()



Get all attribute metadata.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerCustomerMetadataV1Api();

try {
    $result = $api_instance->customerCustomerMetadataV1GetAllAttributesMetadataGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerCustomerMetadataV1Api->customerCustomerMetadataV1GetAllAttributesMetadataGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[]**](../Model/CustomerDataAttributeMetadataInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerCustomerMetadataV1GetAttributeMetadataGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface customerCustomerMetadataV1GetAttributeMetadataGet($attributeCode)



Retrieve attribute metadata.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerCustomerMetadataV1Api();
$attributeCode = "attributeCode_example"; // string | 

try {
    $result = $api_instance->customerCustomerMetadataV1GetAttributeMetadataGet($attributeCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerCustomerMetadataV1Api->customerCustomerMetadataV1GetAttributeMetadataGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface**](../Model/CustomerDataAttributeMetadataInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerCustomerMetadataV1GetAttributesGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[] customerCustomerMetadataV1GetAttributesGet($formCode)



Retrieve all attributes filtered by form code

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerCustomerMetadataV1Api();
$formCode = "formCode_example"; // string | 

try {
    $result = $api_instance->customerCustomerMetadataV1GetAttributesGet($formCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerCustomerMetadataV1Api->customerCustomerMetadataV1GetAttributesGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **formCode** | **string**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[]**](../Model/CustomerDataAttributeMetadataInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **customerCustomerMetadataV1GetCustomAttributesMetadataGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[] customerCustomerMetadataV1GetCustomAttributesMetadataGet($dataInterfaceName)



Get custom attributes metadata for the given data interface.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CustomerCustomerMetadataV1Api();
$dataInterfaceName = "dataInterfaceName_example"; // string | 

try {
    $result = $api_instance->customerCustomerMetadataV1GetCustomAttributesMetadataGet($dataInterfaceName);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CustomerCustomerMetadataV1Api->customerCustomerMetadataV1GetCustomAttributesMetadataGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dataInterfaceName** | **string**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[]**](../Model/CustomerDataAttributeMetadataInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

