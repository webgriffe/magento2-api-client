# Webgriffe\MagentoApiClient\QuoteGuestCartTotalRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteGuestCartTotalRepositoryV1GetGet**](QuoteGuestCartTotalRepositoryV1Api.md#quoteGuestCartTotalRepositoryV1GetGet) | **GET** /V1/guest-carts/{cartId}/totals | 


# **quoteGuestCartTotalRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface quoteGuestCartTotalRepositoryV1GetGet($cartId)



Return quote totals data for a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartTotalRepositoryV1Api();
$cartId = "cartId_example"; // string | The cart ID.

try {
    $result = $api_instance->quoteGuestCartTotalRepositoryV1GetGet($cartId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartTotalRepositoryV1Api->quoteGuestCartTotalRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface**](../Model/QuoteDataTotalsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

