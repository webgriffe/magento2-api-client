# Webgriffe\MagentoApiClient\QuoteGuestShipmentEstimationV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteGuestShipmentEstimationV1EstimateByExtendedAddressPost**](QuoteGuestShipmentEstimationV1Api.md#quoteGuestShipmentEstimationV1EstimateByExtendedAddressPost) | **POST** /V1/guest-carts/{cartId}/estimate-shipping-methods | 


# **quoteGuestShipmentEstimationV1EstimateByExtendedAddressPost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataShippingMethodInterface[] quoteGuestShipmentEstimationV1EstimateByExtendedAddressPost($cartId, $body)



Estimate shipping by address and return list of available shipping methods

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestShipmentEstimationV1Api();
$cartId = "cartId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body56(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body56 | 

try {
    $result = $api_instance->quoteGuestShipmentEstimationV1EstimateByExtendedAddressPost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestShipmentEstimationV1Api->quoteGuestShipmentEstimationV1EstimateByExtendedAddressPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body56**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body56.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataShippingMethodInterface[]**](../Model/QuoteDataShippingMethodInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

