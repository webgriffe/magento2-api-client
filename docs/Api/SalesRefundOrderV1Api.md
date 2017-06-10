# Webgriffe\MagentoApiClient\SalesRefundOrderV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**salesRefundOrderV1ExecutePost**](SalesRefundOrderV1Api.md#salesRefundOrderV1ExecutePost) | **POST** /V1/order/{orderId}/refund | 


# **salesRefundOrderV1ExecutePost**
> int salesRefundOrderV1ExecutePost($orderId, $body)



Create offline refund for order

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesRefundOrderV1Api();
$orderId = 56; // int | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body81(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body81 | 

try {
    $result = $api_instance->salesRefundOrderV1ExecutePost($orderId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesRefundOrderV1Api->salesRefundOrderV1ExecutePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderId** | **int**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body81**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body81.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

