# Webgriffe\MagentoApiClient\CatalogProductAttributeOptionManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductAttributeOptionManagementV1AddPost**](CatalogProductAttributeOptionManagementV1Api.md#catalogProductAttributeOptionManagementV1AddPost) | **POST** /V1/products/attributes/{attributeCode}/options | 
[**catalogProductAttributeOptionManagementV1DeleteDelete**](CatalogProductAttributeOptionManagementV1Api.md#catalogProductAttributeOptionManagementV1DeleteDelete) | **DELETE** /V1/products/attributes/{attributeCode}/options/{optionId} | 
[**catalogProductAttributeOptionManagementV1GetItemsGet**](CatalogProductAttributeOptionManagementV1Api.md#catalogProductAttributeOptionManagementV1GetItemsGet) | **GET** /V1/products/attributes/{attributeCode}/options | 


# **catalogProductAttributeOptionManagementV1AddPost**
> bool catalogProductAttributeOptionManagementV1AddPost($attributeCode, $body)



Add option to attribute

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeOptionManagementV1Api();
$attributeCode = "attributeCode_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Model\Body27(); // \Webgriffe\MagentoApiClient\Model\Body27 | 

try {
    $result = $api_instance->catalogProductAttributeOptionManagementV1AddPost($attributeCode, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeOptionManagementV1Api->catalogProductAttributeOptionManagementV1AddPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body27**](../Model/\Webgriffe\MagentoApiClient\Model\Body27.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductAttributeOptionManagementV1DeleteDelete**
> bool catalogProductAttributeOptionManagementV1DeleteDelete($attributeCode, $optionId)



Delete option from attribute

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeOptionManagementV1Api();
$attributeCode = "attributeCode_example"; // string | 
$optionId = "optionId_example"; // string | 

try {
    $result = $api_instance->catalogProductAttributeOptionManagementV1DeleteDelete($attributeCode, $optionId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeOptionManagementV1Api->catalogProductAttributeOptionManagementV1DeleteDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |
 **optionId** | **string**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductAttributeOptionManagementV1GetItemsGet**
> \Webgriffe\MagentoApiClient\Model\EavDataAttributeOptionInterface[] catalogProductAttributeOptionManagementV1GetItemsGet($attributeCode)



Retrieve list of attribute options

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeOptionManagementV1Api();
$attributeCode = "attributeCode_example"; // string | 

try {
    $result = $api_instance->catalogProductAttributeOptionManagementV1GetItemsGet($attributeCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeOptionManagementV1Api->catalogProductAttributeOptionManagementV1GetItemsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\EavDataAttributeOptionInterface[]**](../Model/EavDataAttributeOptionInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

