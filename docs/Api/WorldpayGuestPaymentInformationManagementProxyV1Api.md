# Webgriffe\MagentoApiClient\WorldpayGuestPaymentInformationManagementProxyV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**worldpayGuestPaymentInformationManagementProxyV1SavePaymentInformationAndPlaceOrderPost**](WorldpayGuestPaymentInformationManagementProxyV1Api.md#worldpayGuestPaymentInformationManagementProxyV1SavePaymentInformationAndPlaceOrderPost) | **POST** /V1/worldpay-guest-carts/{cartId}/payment-information | 


# **worldpayGuestPaymentInformationManagementProxyV1SavePaymentInformationAndPlaceOrderPost**
> int worldpayGuestPaymentInformationManagementProxyV1SavePaymentInformationAndPlaceOrderPost($cartId, $body)



Proxy handler for guest place order

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\WorldpayGuestPaymentInformationManagementProxyV1Api();
$cartId = "cartId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body138(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body138 | 

try {
    $result = $api_instance->worldpayGuestPaymentInformationManagementProxyV1SavePaymentInformationAndPlaceOrderPost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling WorldpayGuestPaymentInformationManagementProxyV1Api->worldpayGuestPaymentInformationManagementProxyV1SavePaymentInformationAndPlaceOrderPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body138**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body138.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

