# Webgriffe\MagentoApiClient\GiftMessageGuestCartRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**giftMessageGuestCartRepositoryV1GetGet**](GiftMessageGuestCartRepositoryV1Api.md#giftMessageGuestCartRepositoryV1GetGet) | **GET** /V1/guest-carts/{cartId}/gift-message | 
[**giftMessageGuestCartRepositoryV1SavePost**](GiftMessageGuestCartRepositoryV1Api.md#giftMessageGuestCartRepositoryV1SavePost) | **POST** /V1/guest-carts/{cartId}/gift-message | 


# **giftMessageGuestCartRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftMessageDataMessageInterface giftMessageGuestCartRepositoryV1GetGet($cartId)



Return the gift message for a specified order.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftMessageGuestCartRepositoryV1Api();
$cartId = "cartId_example"; // string | The shopping cart ID.

try {
    $result = $api_instance->giftMessageGuestCartRepositoryV1GetGet($cartId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftMessageGuestCartRepositoryV1Api->giftMessageGuestCartRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The shopping cart ID. |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftMessageDataMessageInterface**](../Model/GiftMessageDataMessageInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftMessageGuestCartRepositoryV1SavePost**
> bool giftMessageGuestCartRepositoryV1SavePost($cartId, $body)



Set the gift message for an entire order.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftMessageGuestCartRepositoryV1Api();
$cartId = "cartId_example"; // string | The cart ID.
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body127(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body127 | 

try {
    $result = $api_instance->giftMessageGuestCartRepositoryV1SavePost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftMessageGuestCartRepositoryV1Api->giftMessageGuestCartRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body127**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body127.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

