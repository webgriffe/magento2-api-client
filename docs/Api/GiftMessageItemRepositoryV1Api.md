# Webgriffe\MagentoApiClient\GiftMessageItemRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**giftMessageItemRepositoryV1GetGet**](GiftMessageItemRepositoryV1Api.md#giftMessageItemRepositoryV1GetGet) | **GET** /V1/carts/{cartId}/gift-message/{itemId} | 
[**giftMessageItemRepositoryV1GetGet_0**](GiftMessageItemRepositoryV1Api.md#giftMessageItemRepositoryV1GetGet_0) | **GET** /V1/carts/mine/gift-message/{itemId} | 
[**giftMessageItemRepositoryV1SavePost**](GiftMessageItemRepositoryV1Api.md#giftMessageItemRepositoryV1SavePost) | **POST** /V1/carts/{cartId}/gift-message/{itemId} | 
[**giftMessageItemRepositoryV1SavePost_0**](GiftMessageItemRepositoryV1Api.md#giftMessageItemRepositoryV1SavePost_0) | **POST** /V1/carts/mine/gift-message/{itemId} | 


# **giftMessageItemRepositoryV1GetGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftMessageDataMessageInterface giftMessageItemRepositoryV1GetGet($cartId, $itemId)



Return the gift message for a specified item in a specified shopping cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftMessageItemRepositoryV1Api();
$cartId = 56; // int | The shopping cart ID.
$itemId = 56; // int | The item ID.

try {
    $result = $api_instance->giftMessageItemRepositoryV1GetGet($cartId, $itemId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftMessageItemRepositoryV1Api->giftMessageItemRepositoryV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **int**| The shopping cart ID. |
 **itemId** | **int**| The item ID. |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftMessageDataMessageInterface**](../Model/GiftMessageDataMessageInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftMessageItemRepositoryV1GetGet_0**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftMessageDataMessageInterface giftMessageItemRepositoryV1GetGet_0($itemId)



Return the gift message for a specified item in a specified shopping cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftMessageItemRepositoryV1Api();
$itemId = 56; // int | The item ID.

try {
    $result = $api_instance->giftMessageItemRepositoryV1GetGet_0($itemId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftMessageItemRepositoryV1Api->giftMessageItemRepositoryV1GetGet_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **itemId** | **int**| The item ID. |

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\GiftMessageDataMessageInterface**](../Model/GiftMessageDataMessageInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftMessageItemRepositoryV1SavePost**
> bool giftMessageItemRepositoryV1SavePost($cartId, $itemId, $body)



Set the gift message for a specified item in a specified shopping cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftMessageItemRepositoryV1Api();
$cartId = 56; // int | The cart ID.
$itemId = 56; // int | The item ID.
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body125(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body125 | 

try {
    $result = $api_instance->giftMessageItemRepositoryV1SavePost($cartId, $itemId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftMessageItemRepositoryV1Api->giftMessageItemRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **int**| The cart ID. |
 **itemId** | **int**| The item ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body125**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body125.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftMessageItemRepositoryV1SavePost_0**
> bool giftMessageItemRepositoryV1SavePost_0($itemId, $body)



Set the gift message for a specified item in a specified shopping cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftMessageItemRepositoryV1Api();
$itemId = 56; // int | The item ID.
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body126(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body126 | 

try {
    $result = $api_instance->giftMessageItemRepositoryV1SavePost_0($itemId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftMessageItemRepositoryV1Api->giftMessageItemRepositoryV1SavePost_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **itemId** | **int**| The item ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body126**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body126.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

