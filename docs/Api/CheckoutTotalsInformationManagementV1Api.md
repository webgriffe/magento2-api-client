# Webgriffe\MagentoApiClient\CheckoutTotalsInformationManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**checkoutTotalsInformationManagementV1CalculatePost**](CheckoutTotalsInformationManagementV1Api.md#checkoutTotalsInformationManagementV1CalculatePost) | **POST** /V1/carts/{cartId}/totals-information | 
[**checkoutTotalsInformationManagementV1CalculatePost_0**](CheckoutTotalsInformationManagementV1Api.md#checkoutTotalsInformationManagementV1CalculatePost_0) | **POST** /V1/carts/mine/totals-information | 


# **checkoutTotalsInformationManagementV1CalculatePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface checkoutTotalsInformationManagementV1CalculatePost($cartId, $body)



Calculate quote totals based on address and shipping method.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CheckoutTotalsInformationManagementV1Api();
$cartId = 56; // int | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body97(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body97 | 

try {
    $result = $api_instance->checkoutTotalsInformationManagementV1CalculatePost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CheckoutTotalsInformationManagementV1Api->checkoutTotalsInformationManagementV1CalculatePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **int**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body97**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body97.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface**](../Model/QuoteDataTotalsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **checkoutTotalsInformationManagementV1CalculatePost_0**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface checkoutTotalsInformationManagementV1CalculatePost_0($body)



Calculate quote totals based on address and shipping method.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CheckoutTotalsInformationManagementV1Api();
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body98(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body98 | 

try {
    $result = $api_instance->checkoutTotalsInformationManagementV1CalculatePost_0($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CheckoutTotalsInformationManagementV1Api->checkoutTotalsInformationManagementV1CalculatePost_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body98**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body98.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface**](../Model/QuoteDataTotalsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

