# Webgriffe\MagentoApiClient\CheckoutGuestTotalsInformationManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**checkoutGuestTotalsInformationManagementV1CalculatePost**](CheckoutGuestTotalsInformationManagementV1Api.md#checkoutGuestTotalsInformationManagementV1CalculatePost) | **POST** /V1/guest-carts/{cartId}/totals-information | 


# **checkoutGuestTotalsInformationManagementV1CalculatePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface checkoutGuestTotalsInformationManagementV1CalculatePost($cartId, $body)



Calculate quote totals based on address and shipping method.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CheckoutGuestTotalsInformationManagementV1Api();
$cartId = "cartId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body99(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body99 | 

try {
    $result = $api_instance->checkoutGuestTotalsInformationManagementV1CalculatePost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CheckoutGuestTotalsInformationManagementV1Api->checkoutGuestTotalsInformationManagementV1CalculatePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body99**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body99.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface**](../Model/QuoteDataTotalsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

