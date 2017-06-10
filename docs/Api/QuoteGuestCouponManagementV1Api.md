# Webgriffe\MagentoApiClient\QuoteGuestCouponManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteGuestCouponManagementV1GetGet**](QuoteGuestCouponManagementV1Api.md#quoteGuestCouponManagementV1GetGet) | **GET** /V1/guest-carts/{cartId}/coupons | 
[**quoteGuestCouponManagementV1RemoveDelete**](QuoteGuestCouponManagementV1Api.md#quoteGuestCouponManagementV1RemoveDelete) | **DELETE** /V1/guest-carts/{cartId}/coupons | 
[**quoteGuestCouponManagementV1SetPut**](QuoteGuestCouponManagementV1Api.md#quoteGuestCouponManagementV1SetPut) | **PUT** /V1/guest-carts/{cartId}/coupons/{couponCode} | 


# **quoteGuestCouponManagementV1GetGet**
> string quoteGuestCouponManagementV1GetGet($cartId)



Return information for a coupon in a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCouponManagementV1Api();
$cartId = "cartId_example"; // string | The cart ID.

try {
    $result = $api_instance->quoteGuestCouponManagementV1GetGet($cartId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCouponManagementV1Api->quoteGuestCouponManagementV1GetGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteGuestCouponManagementV1RemoveDelete**
> bool quoteGuestCouponManagementV1RemoveDelete($cartId)



Delete a coupon from a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCouponManagementV1Api();
$cartId = "cartId_example"; // string | The cart ID.

try {
    $result = $api_instance->quoteGuestCouponManagementV1RemoveDelete($cartId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCouponManagementV1Api->quoteGuestCouponManagementV1RemoveDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteGuestCouponManagementV1SetPut**
> bool quoteGuestCouponManagementV1SetPut($cartId, $couponCode)



Add a coupon by code to a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCouponManagementV1Api();
$cartId = "cartId_example"; // string | The cart ID.
$couponCode = "couponCode_example"; // string | The coupon code data.

try {
    $result = $api_instance->quoteGuestCouponManagementV1SetPut($cartId, $couponCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCouponManagementV1Api->quoteGuestCouponManagementV1SetPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |
 **couponCode** | **string**| The coupon code data. |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

