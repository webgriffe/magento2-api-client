# Webgriffe\MagentoApiClient\QuoteCartTotalRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteCartTotalRepositoryV1GetGet**](QuoteCartTotalRepositoryV1Api.md#quoteCartTotalRepositoryV1GetGet) | **GET** /V1/carts/{cartId}/totals | 
[**quoteCartTotalRepositoryV1GetGet_0**](QuoteCartTotalRepositoryV1Api.md#quoteCartTotalRepositoryV1GetGet_0) | **GET** /V1/carts/mine/totals | 


# **quoteCartTotalRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface quoteCartTotalRepositoryV1GetGet($cartId)



Returns quote totals data for a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartTotalRepositoryV1Api();
$cartId = 56; // int | The cart ID.

try {
    $result = $api_instance->quoteCartTotalRepositoryV1GetGet($cartId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartTotalRepositoryV1Api->quoteCartTotalRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **int**| The cart ID. |

### Return type

[**\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface**](../Model/QuoteDataTotalsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartTotalRepositoryV1GetGet_0**
> \Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface quoteCartTotalRepositoryV1GetGet_0()



Returns quote totals data for a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartTotalRepositoryV1Api();

try {
    $result = $api_instance->quoteCartTotalRepositoryV1GetGet_0();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartTotalRepositoryV1Api->quoteCartTotalRepositoryV1GetGet_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Webgriffe\MagentoApiClient\Model\QuoteDataTotalsInterface**](../Model/QuoteDataTotalsInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

