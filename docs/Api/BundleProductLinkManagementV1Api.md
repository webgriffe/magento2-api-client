# Webgriffe\MagentoApiClient\BundleProductLinkManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**bundleProductLinkManagementV1AddChildByProductSkuPost**](BundleProductLinkManagementV1Api.md#bundleProductLinkManagementV1AddChildByProductSkuPost) | **POST** /V1/bundle-products/{sku}/links/{optionId} | 
[**bundleProductLinkManagementV1GetChildrenGet**](BundleProductLinkManagementV1Api.md#bundleProductLinkManagementV1GetChildrenGet) | **GET** /V1/bundle-products/{productSku}/children | 
[**bundleProductLinkManagementV1RemoveChildDelete**](BundleProductLinkManagementV1Api.md#bundleProductLinkManagementV1RemoveChildDelete) | **DELETE** /V1/bundle-products/{sku}/options/{optionId}/children/{childSku} | 
[**bundleProductLinkManagementV1SaveChildPut**](BundleProductLinkManagementV1Api.md#bundleProductLinkManagementV1SaveChildPut) | **PUT** /V1/bundle-products/{sku}/links/{id} | 


# **bundleProductLinkManagementV1AddChildByProductSkuPost**
> int bundleProductLinkManagementV1AddChildByProductSkuPost($sku, $optionId, $body)



Add child product to specified Bundle option by product sku

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductLinkManagementV1Api();
$sku = "sku_example"; // string | 
$optionId = 56; // int | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body42(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body42 | 

try {
    $result = $api_instance->bundleProductLinkManagementV1AddChildByProductSkuPost($sku, $optionId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductLinkManagementV1Api->bundleProductLinkManagementV1AddChildByProductSkuPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **optionId** | **int**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body42**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body42.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **bundleProductLinkManagementV1GetChildrenGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\BundleDataLinkInterface[] bundleProductLinkManagementV1GetChildrenGet($productSku, $optionId)



Get all children for Bundle product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductLinkManagementV1Api();
$productSku = "productSku_example"; // string | 
$optionId = 56; // int | 

try {
    $result = $api_instance->bundleProductLinkManagementV1GetChildrenGet($productSku, $optionId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductLinkManagementV1Api->bundleProductLinkManagementV1GetChildrenGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **productSku** | **string**|  |
 **optionId** | **int**|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\BundleDataLinkInterface[]**](../Model/BundleDataLinkInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **bundleProductLinkManagementV1RemoveChildDelete**
> bool bundleProductLinkManagementV1RemoveChildDelete($sku, $optionId, $childSku)



Remove product from Bundle product option

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductLinkManagementV1Api();
$sku = "sku_example"; // string | 
$optionId = 56; // int | 
$childSku = "childSku_example"; // string | 

try {
    $result = $api_instance->bundleProductLinkManagementV1RemoveChildDelete($sku, $optionId, $childSku);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductLinkManagementV1Api->bundleProductLinkManagementV1RemoveChildDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **optionId** | **int**|  |
 **childSku** | **string**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **bundleProductLinkManagementV1SaveChildPut**
> bool bundleProductLinkManagementV1SaveChildPut($sku, $id, $body)





### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductLinkManagementV1Api();
$sku = "sku_example"; // string | 
$id = "id_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body43(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body43 | 

try {
    $result = $api_instance->bundleProductLinkManagementV1SaveChildPut($sku, $id, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductLinkManagementV1Api->bundleProductLinkManagementV1SaveChildPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **id** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body43**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body43.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

