# Webgriffe\MagentoApiClient\GiftCardAccountGuestGiftCardAccountManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**giftCardAccountGuestGiftCardAccountManagementV1AddGiftCardPost**](GiftCardAccountGuestGiftCardAccountManagementV1Api.md#giftCardAccountGuestGiftCardAccountManagementV1AddGiftCardPost) | **POST** /V1/carts/guest-carts/{cartId}/giftCards | 
[**giftCardAccountGuestGiftCardAccountManagementV1CheckGiftCardGet**](GiftCardAccountGuestGiftCardAccountManagementV1Api.md#giftCardAccountGuestGiftCardAccountManagementV1CheckGiftCardGet) | **GET** /V1/carts/guest-carts/{cartId}/checkGiftCard/{giftCardCode} | 
[**giftCardAccountGuestGiftCardAccountManagementV1DeleteByQuoteIdDelete**](GiftCardAccountGuestGiftCardAccountManagementV1Api.md#giftCardAccountGuestGiftCardAccountManagementV1DeleteByQuoteIdDelete) | **DELETE** /V1/carts/guest-carts/{cartId}/giftCards/{giftCardCode} | 


# **giftCardAccountGuestGiftCardAccountManagementV1AddGiftCardPost**
> bool giftCardAccountGuestGiftCardAccountManagementV1AddGiftCardPost($cartId, $body)





### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftCardAccountGuestGiftCardAccountManagementV1Api();
$cartId = "cartId_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Model\Body120(); // \Webgriffe\MagentoApiClient\Model\Body120 | 

try {
    $result = $api_instance->giftCardAccountGuestGiftCardAccountManagementV1AddGiftCardPost($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftCardAccountGuestGiftCardAccountManagementV1Api->giftCardAccountGuestGiftCardAccountManagementV1AddGiftCardPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body120**](../Model/\Webgriffe\MagentoApiClient\Model\Body120.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftCardAccountGuestGiftCardAccountManagementV1CheckGiftCardGet**
> float giftCardAccountGuestGiftCardAccountManagementV1CheckGiftCardGet($cartId, $giftCardCode)





### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftCardAccountGuestGiftCardAccountManagementV1Api();
$cartId = "cartId_example"; // string | 
$giftCardCode = "giftCardCode_example"; // string | 

try {
    $result = $api_instance->giftCardAccountGuestGiftCardAccountManagementV1CheckGiftCardGet($cartId, $giftCardCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftCardAccountGuestGiftCardAccountManagementV1Api->giftCardAccountGuestGiftCardAccountManagementV1CheckGiftCardGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **giftCardCode** | **string**|  |

### Return type

**float**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **giftCardAccountGuestGiftCardAccountManagementV1DeleteByQuoteIdDelete**
> bool giftCardAccountGuestGiftCardAccountManagementV1DeleteByQuoteIdDelete($cartId, $giftCardCode)



Remove GiftCard Account entity

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\GiftCardAccountGuestGiftCardAccountManagementV1Api();
$cartId = "cartId_example"; // string | 
$giftCardCode = "giftCardCode_example"; // string | 

try {
    $result = $api_instance->giftCardAccountGuestGiftCardAccountManagementV1DeleteByQuoteIdDelete($cartId, $giftCardCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling GiftCardAccountGuestGiftCardAccountManagementV1Api->giftCardAccountGuestGiftCardAccountManagementV1DeleteByQuoteIdDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**|  |
 **giftCardCode** | **string**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

