# Webgriffe\MagentoApiClient\CatalogProductWebsiteLinkRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductWebsiteLinkRepositoryV1DeleteByIdDelete**](CatalogProductWebsiteLinkRepositoryV1Api.md#catalogProductWebsiteLinkRepositoryV1DeleteByIdDelete) | **DELETE** /V1/products/{sku}/websites/{websiteId} | 
[**catalogProductWebsiteLinkRepositoryV1SavePost**](CatalogProductWebsiteLinkRepositoryV1Api.md#catalogProductWebsiteLinkRepositoryV1SavePost) | **POST** /V1/products/{sku}/websites | 
[**catalogProductWebsiteLinkRepositoryV1SavePut**](CatalogProductWebsiteLinkRepositoryV1Api.md#catalogProductWebsiteLinkRepositoryV1SavePut) | **PUT** /V1/products/{sku}/websites | 


# **catalogProductWebsiteLinkRepositoryV1DeleteByIdDelete**
> bool catalogProductWebsiteLinkRepositoryV1DeleteByIdDelete($sku, $websiteId)



Remove the website assignment from the product by product sku

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductWebsiteLinkRepositoryV1Api();
$sku = "sku_example"; // string | 
$websiteId = 56; // int | 

try {
    $result = $api_instance->catalogProductWebsiteLinkRepositoryV1DeleteByIdDelete($sku, $websiteId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductWebsiteLinkRepositoryV1Api->catalogProductWebsiteLinkRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **websiteId** | **int**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductWebsiteLinkRepositoryV1SavePost**
> bool catalogProductWebsiteLinkRepositoryV1SavePost($sku, $body)



Assign a product to the website

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductWebsiteLinkRepositoryV1Api();
$sku = "sku_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Model\Body40(); // \Webgriffe\MagentoApiClient\Model\Body40 | 

try {
    $result = $api_instance->catalogProductWebsiteLinkRepositoryV1SavePost($sku, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductWebsiteLinkRepositoryV1Api->catalogProductWebsiteLinkRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body40**](../Model/\Webgriffe\MagentoApiClient\Model\Body40.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductWebsiteLinkRepositoryV1SavePut**
> bool catalogProductWebsiteLinkRepositoryV1SavePut($sku, $body)



Assign a product to the website

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductWebsiteLinkRepositoryV1Api();
$sku = "sku_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Model\Body39(); // \Webgriffe\MagentoApiClient\Model\Body39 | 

try {
    $result = $api_instance->catalogProductWebsiteLinkRepositoryV1SavePut($sku, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductWebsiteLinkRepositoryV1Api->catalogProductWebsiteLinkRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body39**](../Model/\Webgriffe\MagentoApiClient\Model\Body39.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

