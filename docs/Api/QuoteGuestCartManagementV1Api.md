# Webgriffe\MagentoApiClient\QuoteGuestCartManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteGuestCartManagementV1AssignCustomerPut**](QuoteGuestCartManagementV1Api.md#quoteGuestCartManagementV1AssignCustomerPut) | **PUT** /V1/guest-carts/{cartId} | 
[**quoteGuestCartManagementV1CreateEmptyCartPost**](QuoteGuestCartManagementV1Api.md#quoteGuestCartManagementV1CreateEmptyCartPost) | **POST** /V1/guest-carts | 
[**quoteGuestCartManagementV1PlaceOrderPut**](QuoteGuestCartManagementV1Api.md#quoteGuestCartManagementV1PlaceOrderPut) | **PUT** /V1/guest-carts/{cartId}/order | 


# **quoteGuestCartManagementV1AssignCustomerPut**
> bool quoteGuestCartManagementV1AssignCustomerPut($cartId, $body)



Assign a specified customer to a specified shopping cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartManagementV1Api();
$cartId = "cartId_example"; // string | The cart ID.
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body50(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body50 | 

try {
    $result = $api_instance->quoteGuestCartManagementV1AssignCustomerPut($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartManagementV1Api->quoteGuestCartManagementV1AssignCustomerPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body50**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body50.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteGuestCartManagementV1CreateEmptyCartPost**
> string quoteGuestCartManagementV1CreateEmptyCartPost()



Enable an customer or guest user to create an empty cart and quote for an anonymous customer.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartManagementV1Api();

try {
    $result = $api_instance->quoteGuestCartManagementV1CreateEmptyCartPost();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartManagementV1Api->quoteGuestCartManagementV1CreateEmptyCartPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteGuestCartManagementV1PlaceOrderPut**
> int quoteGuestCartManagementV1PlaceOrderPut($cartId, $body)



Place an order for a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteGuestCartManagementV1Api();
$cartId = "cartId_example"; // string | The cart ID.
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body51(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body51 | 

try {
    $result = $api_instance->quoteGuestCartManagementV1PlaceOrderPut($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteGuestCartManagementV1Api->quoteGuestCartManagementV1PlaceOrderPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **string**| The cart ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body51**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body51.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

