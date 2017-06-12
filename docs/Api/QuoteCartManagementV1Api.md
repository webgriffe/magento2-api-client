# Webgriffe\MagentoApiClient\QuoteCartManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**quoteCartManagementV1AssignCustomerPut**](QuoteCartManagementV1Api.md#quoteCartManagementV1AssignCustomerPut) | **PUT** /V1/carts/{cartId} | 
[**quoteCartManagementV1CreateEmptyCartForCustomerPost**](QuoteCartManagementV1Api.md#quoteCartManagementV1CreateEmptyCartForCustomerPost) | **POST** /V1/carts/mine | 
[**quoteCartManagementV1CreateEmptyCartForCustomerPost_0**](QuoteCartManagementV1Api.md#quoteCartManagementV1CreateEmptyCartForCustomerPost_0) | **POST** /V1/customers/{customerId}/carts | 
[**quoteCartManagementV1CreateEmptyCartPost**](QuoteCartManagementV1Api.md#quoteCartManagementV1CreateEmptyCartPost) | **POST** /V1/carts/ | 
[**quoteCartManagementV1GetCartForCustomerGet**](QuoteCartManagementV1Api.md#quoteCartManagementV1GetCartForCustomerGet) | **GET** /V1/carts/mine | 
[**quoteCartManagementV1PlaceOrderPut**](QuoteCartManagementV1Api.md#quoteCartManagementV1PlaceOrderPut) | **PUT** /V1/carts/mine/order | 
[**quoteCartManagementV1PlaceOrderPut_0**](QuoteCartManagementV1Api.md#quoteCartManagementV1PlaceOrderPut_0) | **PUT** /V1/carts/{cartId}/order | 


# **quoteCartManagementV1AssignCustomerPut**
> bool quoteCartManagementV1AssignCustomerPut($cartId, $body)



Assigns a specified customer to a specified shopping cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartManagementV1Api();
$cartId = 56; // int | The cart ID.
$body = new \Webgriffe\MagentoApiClient\Model\Body46(); // \Webgriffe\MagentoApiClient\Model\Body46 | 

try {
    $result = $api_instance->quoteCartManagementV1AssignCustomerPut($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartManagementV1Api->quoteCartManagementV1AssignCustomerPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **int**| The cart ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body46**](../Model/\Webgriffe\MagentoApiClient\Model\Body46.md)|  | [optional]

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartManagementV1CreateEmptyCartForCustomerPost**
> int quoteCartManagementV1CreateEmptyCartForCustomerPost()



Creates an empty cart and quote for a specified customer.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartManagementV1Api();

try {
    $result = $api_instance->quoteCartManagementV1CreateEmptyCartForCustomerPost();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartManagementV1Api->quoteCartManagementV1CreateEmptyCartForCustomerPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartManagementV1CreateEmptyCartForCustomerPost_0**
> int quoteCartManagementV1CreateEmptyCartForCustomerPost_0($customerId)



Creates an empty cart and quote for a specified customer.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartManagementV1Api();
$customerId = 56; // int | The customer ID.

try {
    $result = $api_instance->quoteCartManagementV1CreateEmptyCartForCustomerPost_0($customerId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartManagementV1Api->quoteCartManagementV1CreateEmptyCartForCustomerPost_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customerId** | **int**| The customer ID. |

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartManagementV1CreateEmptyCartPost**
> int quoteCartManagementV1CreateEmptyCartPost()



Creates an empty cart and quote for a guest.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartManagementV1Api();

try {
    $result = $api_instance->quoteCartManagementV1CreateEmptyCartPost();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartManagementV1Api->quoteCartManagementV1CreateEmptyCartPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartManagementV1GetCartForCustomerGet**
> \Webgriffe\MagentoApiClient\Model\QuoteDataCartInterface quoteCartManagementV1GetCartForCustomerGet()



Returns information for the cart for a specified customer.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartManagementV1Api();

try {
    $result = $api_instance->quoteCartManagementV1GetCartForCustomerGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartManagementV1Api->quoteCartManagementV1GetCartForCustomerGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Webgriffe\MagentoApiClient\Model\QuoteDataCartInterface**](../Model/QuoteDataCartInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartManagementV1PlaceOrderPut**
> int quoteCartManagementV1PlaceOrderPut($body)



Places an order for a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartManagementV1Api();
$body = new \Webgriffe\MagentoApiClient\Model\Body48(); // \Webgriffe\MagentoApiClient\Model\Body48 | 

try {
    $result = $api_instance->quoteCartManagementV1PlaceOrderPut($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartManagementV1Api->quoteCartManagementV1PlaceOrderPut: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body48**](../Model/\Webgriffe\MagentoApiClient\Model\Body48.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **quoteCartManagementV1PlaceOrderPut_0**
> int quoteCartManagementV1PlaceOrderPut_0($cartId, $body)



Places an order for a specified cart.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\QuoteCartManagementV1Api();
$cartId = 56; // int | The cart ID.
$body = new \Webgriffe\MagentoApiClient\Model\Body49(); // \Webgriffe\MagentoApiClient\Model\Body49 | 

try {
    $result = $api_instance->quoteCartManagementV1PlaceOrderPut_0($cartId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling QuoteCartManagementV1Api->quoteCartManagementV1PlaceOrderPut_0: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cartId** | **int**| The cart ID. |
 **body** | [**\Webgriffe\MagentoApiClient\Model\Body49**](../Model/\Webgriffe\MagentoApiClient\Model\Body49.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

