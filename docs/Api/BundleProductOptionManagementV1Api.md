# Webgriffe\MagentoApiClient\BundleProductOptionManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**bundleProductOptionManagementV1SavePost**](BundleProductOptionManagementV1Api.md#bundleProductOptionManagementV1SavePost) | **POST** /V1/bundle-products/options/add | 
[**bundleProductOptionManagementV1SavePut**](BundleProductOptionManagementV1Api.md#bundleProductOptionManagementV1SavePut) | **PUT** /V1/bundle-products/options/{optionId} | 


# **bundleProductOptionManagementV1SavePost**
> int bundleProductOptionManagementV1SavePost($body)



Add new option for bundle product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductOptionManagementV1Api();
$body = new \Webgriffe\MagentoApiClient\Model\Body44(); // \Webgriffe\MagentoApiClient\Model\Body44 | 

try {
    $result = $api_instance->bundleProductOptionManagementV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductOptionManagementV1Api->bundleProductOptionManagementV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body44**](../Model/\Webgriffe\MagentoApiClient\Model\Body44.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **bundleProductOptionManagementV1SavePut**
> int bundleProductOptionManagementV1SavePut($optionId, $body)



Add new option for bundle product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductOptionManagementV1Api();
$optionId = "optionId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Model\Body45(); // \Webgriffe\MagentoApiClient\Model\Body45 | 

try {
    $result = $api_instance->bundleProductOptionManagementV1SavePut($optionId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductOptionManagementV1Api->bundleProductOptionManagementV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **optionId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body45**](../Model/\Webgriffe\MagentoApiClient\Model\Body45.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

