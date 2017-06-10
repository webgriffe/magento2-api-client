# Webgriffe\MagentoApiClient\GiftRegistryShippingMethodManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**giftRegistryShippingMethodManagementV1EstimateByRegistryIdPost**](GiftRegistryShippingMethodManagementV1Api.md#giftRegistryShippingMethodManagementV1EstimateByRegistryIdPost) | **POST** /V1/giftregistry/mine/estimate-shipping-methods | 


# **giftRegistryShippingMethodManagementV1EstimateByRegistryIdPost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataShippingMethodInterface[] giftRegistryShippingMethodManagementV1EstimateByRegistryIdPost($body)



Estimate shipping

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftRegistryShippingMethodManagementV1Api();
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body121(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body121 | 

try {
    $result = $api_instance->giftRegistryShippingMethodManagementV1EstimateByRegistryIdPost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftRegistryShippingMethodManagementV1Api->giftRegistryShippingMethodManagementV1EstimateByRegistryIdPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body121**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body121.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataShippingMethodInterface[]**](../Model/QuoteDataShippingMethodInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

