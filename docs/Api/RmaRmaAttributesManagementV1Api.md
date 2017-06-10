# Webgriffe\MagentoApiClient\RmaRmaAttributesManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**rmaRmaAttributesManagementV1GetAllAttributesMetadataGet**](RmaRmaAttributesManagementV1Api.md#rmaRmaAttributesManagementV1GetAllAttributesMetadataGet) | **GET** /V1/returnsAttributeMetadata | 
[**rmaRmaAttributesManagementV1GetAttributeMetadataGet**](RmaRmaAttributesManagementV1Api.md#rmaRmaAttributesManagementV1GetAttributeMetadataGet) | **GET** /V1/returnsAttributeMetadata/{attributeCode} | 
[**rmaRmaAttributesManagementV1GetAttributesGet**](RmaRmaAttributesManagementV1Api.md#rmaRmaAttributesManagementV1GetAttributesGet) | **GET** /V1/returnsAttributeMetadata/form/{formCode} | 
[**rmaRmaAttributesManagementV1GetCustomAttributesMetadataGet**](RmaRmaAttributesManagementV1Api.md#rmaRmaAttributesManagementV1GetCustomAttributesMetadataGet) | **GET** /V1/returnsAttributeMetadata/custom | 


# **rmaRmaAttributesManagementV1GetAllAttributesMetadataGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[] rmaRmaAttributesManagementV1GetAllAttributesMetadataGet()



Get all attribute metadata.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\RmaRmaAttributesManagementV1Api();

try {
    $result = $api_instance->rmaRmaAttributesManagementV1GetAllAttributesMetadataGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RmaRmaAttributesManagementV1Api->rmaRmaAttributesManagementV1GetAllAttributesMetadataGet: ', $e->getMessage(), PHP_EOL;
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

# **rmaRmaAttributesManagementV1GetAttributeMetadataGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface rmaRmaAttributesManagementV1GetAttributeMetadataGet($attributeCode)



Retrieve attribute metadata.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\RmaRmaAttributesManagementV1Api();
$attributeCode = "attributeCode_example"; // string | 

try {
    $result = $api_instance->rmaRmaAttributesManagementV1GetAttributeMetadataGet($attributeCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RmaRmaAttributesManagementV1Api->rmaRmaAttributesManagementV1GetAttributeMetadataGet: ', $e->getMessage(), PHP_EOL;
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

# **rmaRmaAttributesManagementV1GetAttributesGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CustomerDataAttributeMetadataInterface[] rmaRmaAttributesManagementV1GetAttributesGet($formCode)



Retrieve all attributes filtered by form code

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\RmaRmaAttributesManagementV1Api();
$formCode = "formCode_example"; // string | 

try {
    $result = $api_instance->rmaRmaAttributesManagementV1GetAttributesGet($formCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RmaRmaAttributesManagementV1Api->rmaRmaAttributesManagementV1GetAttributesGet: ', $e->getMessage(), PHP_EOL;
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

# **rmaRmaAttributesManagementV1GetCustomAttributesMetadataGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\FrameworkMetadataObjectInterface[] rmaRmaAttributesManagementV1GetCustomAttributesMetadataGet($dataObjectClassName)



Get custom attribute metadata for the given Data object's attribute set

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\RmaRmaAttributesManagementV1Api();
$dataObjectClassName = "dataObjectClassName_example"; // string | Data object class name

try {
    $result = $api_instance->rmaRmaAttributesManagementV1GetCustomAttributesMetadataGet($dataObjectClassName);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RmaRmaAttributesManagementV1Api->rmaRmaAttributesManagementV1GetCustomAttributesMetadataGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dataObjectClassName** | **string**| Data object class name | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\FrameworkMetadataObjectInterface[]**](../Model/FrameworkMetadataObjectInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

