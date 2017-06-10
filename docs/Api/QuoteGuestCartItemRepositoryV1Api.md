# Webgriffe\MagentoApiClient\QuoteGuestCartItemRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteGuestCartItemRepositoryV1DeleteByIdDelete**](QuoteGuestCartItemRepositoryV1Api.md#quoteGuestCartItemRepositoryV1DeleteByIdDelete) | **DELETE** /V1/guest-carts/{cartId}/items/{itemId} | 
[**quoteGuestCartItemRepositoryV1GetListGet**](QuoteGuestCartItemRepositoryV1Api.md#quoteGuestCartItemRepositoryV1GetListGet) | **GET** /V1/guest-carts/{cartId}/items | 
[**quoteGuestCartItemRepositoryV1SavePost**](QuoteGuestCartItemRepositoryV1Api.md#quoteGuestCartItemRepositoryV1SavePost) | **POST** /V1/guest-carts/{cartId}/items | 
[**quoteGuestCartItemRepositoryV1SavePut**](QuoteGuestCartItemRepositoryV1Api.md#quoteGuestCartItemRepositoryV1SavePut) | **PUT** /V1/guest-carts/{cartId}/items/{itemId} | 


# **quoteGuestCartItemRepositoryV1DeleteByIdDelete**
> bool quoteGuestCartItemRepositoryV1DeleteByIdDelete($cartId, $itemId)



Remove the specified item from the specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartItemRepositoryV1Api();
$cartId = "cartId_example"; // string | The cart ID.
$itemId = 56; // int | The item ID of the item to be removed.

try {
    $result = $api_instance->quoteGuestCartItemRepositoryV1DeleteByIdDelete($cartId, $itemId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartItemRepositoryV1Api->quoteGuestCartItemRepositoryV1DeleteByIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |
 **itemId** | **int**| The item ID of the item to be removed. |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteGuestCartItemRepositoryV1GetListGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartItemInterface[] quoteGuestCartItemRepositoryV1GetListGet($cartId)



List items that are assigned to a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartItemRepositoryV1Api();
$cartId = "cartId_example"; // string | The cart ID.

try {
    $result = $api_instance->quoteGuestCartItemRepositoryV1GetListGet($cartId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartItemRepositoryV1Api->quoteGuestCartItemRepositoryV1GetListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartItemInterface[]**](../Model/QuoteDataCartItemInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteGuestCartItemRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartItemInterface quoteGuestCartItemRepositoryV1SavePost($cartId, $body)



Add the specified item to the specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartItemRepositoryV1Api();
$cartId = "cartId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body61(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body61 | 

try {
    $result = $api_instance->quoteGuestCartItemRepositoryV1SavePost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartItemRepositoryV1Api->quoteGuestCartItemRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body61**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body61.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartItemInterface**](../Model/QuoteDataCartItemInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteGuestCartItemRepositoryV1SavePut**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartItemInterface quoteGuestCartItemRepositoryV1SavePut($cartId, $itemId, $body)



Add the specified item to the specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartItemRepositoryV1Api();
$cartId = "cartId_example"; // string | 
$itemId = "itemId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body62(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body62 | 

try {
    $result = $api_instance->quoteGuestCartItemRepositoryV1SavePut($cartId, $itemId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartItemRepositoryV1Api->quoteGuestCartItemRepositoryV1SavePut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **itemId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body62**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body62.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\QuoteDataCartItemInterface**](../Model/QuoteDataCartItemInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

