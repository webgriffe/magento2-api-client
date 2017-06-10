# Webgriffe\MagentoApiClient\GiftRegistryGuestCartShippingMethodManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**giftRegistryGuestCartShippingMethodManagementV1EstimateByRegistryIdPost**](GiftRegistryGuestCartShippingMethodManagementV1Api.md#giftRegistryGuestCartShippingMethodManagementV1EstimateByRegistryIdPost) | **POST** /V1/guest-giftregistry/{cartId}/estimate-shipping-methods | 


# **giftRegistryGuestCartShippingMethodManagementV1EstimateByRegistryIdPost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataShippingMethodInterface[] giftRegistryGuestCartShippingMethodManagementV1EstimateByRegistryIdPost($cartId, $body)



Estimate shipping

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftRegistryGuestCartShippingMethodManagementV1Api();
$cartId = "cartId_example"; // string | The shopping cart ID.
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body122(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body122 | 

try {
    $result = $api_instance->giftRegistryGuestCartShippingMethodManagementV1EstimateByRegistryIdPost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftRegistryGuestCartShippingMethodManagementV1Api->giftRegistryGuestCartShippingMethodManagementV1EstimateByRegistryIdPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The shopping cart ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body122**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body122.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataShippingMethodInterface[]**](../Model/QuoteDataShippingMethodInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

