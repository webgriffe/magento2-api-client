# Webgriffe\MagentoApiClient\BundleProductOptionRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**bundleProductOptionRepositoryV1DeleteByIdDelete**](BundleProductOptionRepositoryV1Api.md#bundleProductOptionRepositoryV1DeleteByIdDelete) | **DELETE** /V1/bundle-products/{sku}/options/{optionId} | 
[**bundleProductOptionRepositoryV1GetGet**](BundleProductOptionRepositoryV1Api.md#bundleProductOptionRepositoryV1GetGet) | **GET** /V1/bundle-products/{sku}/options/{optionId} | 
[**bundleProductOptionRepositoryV1GetListGet**](BundleProductOptionRepositoryV1Api.md#bundleProductOptionRepositoryV1GetListGet) | **GET** /V1/bundle-products/{sku}/options/all | 


# **bundleProductOptionRepositoryV1DeleteByIdDelete**
> bool bundleProductOptionRepositoryV1DeleteByIdDelete($sku, $optionId)



Remove bundle option

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductOptionRepositoryV1Api();
$sku = "sku_example"; // string | 
$optionId = 56; // int | 

try {
    $result = $api_instance->bundleProductOptionRepositoryV1DeleteByIdDelete($sku, $optionId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductOptionRepositoryV1Api->bundleProductOptionRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **optionId** | **int**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **bundleProductOptionRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Model\BundleDataOptionInterface bundleProductOptionRepositoryV1GetGet($sku, $optionId)



Get option for bundle product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductOptionRepositoryV1Api();
$sku = "sku_example"; // string | 
$optionId = 56; // int | 

try {
    $result = $api_instance->bundleProductOptionRepositoryV1GetGet($sku, $optionId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductOptionRepositoryV1Api->bundleProductOptionRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **optionId** | **int**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\BundleDataOptionInterface**](../Model/BundleDataOptionInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **bundleProductOptionRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Model\BundleDataOptionInterface[] bundleProductOptionRepositoryV1GetListGet($sku)



Get all options for bundle product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\BundleProductOptionRepositoryV1Api();
$sku = "sku_example"; // string | 

try {
    $result = $api_instance->bundleProductOptionRepositoryV1GetListGet($sku);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling BundleProductOptionRepositoryV1Api->bundleProductOptionRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\BundleDataOptionInterface[]**](../Model/BundleDataOptionInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

