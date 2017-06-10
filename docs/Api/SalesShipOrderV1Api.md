# Webgriffe\MagentoApiClient\SalesShipOrderV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**salesShipOrderV1ExecutePost**](SalesShipOrderV1Api.md#salesShipOrderV1ExecutePost) | **POST** /V1/order/{orderId}/ship | 


# **salesShipOrderV1ExecutePost**
> int salesShipOrderV1ExecutePost($orderId, $body)



Creates new Shipment for given Order.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesShipOrderV1Api();
$orderId = 56; // int | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body85(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body85 | 

try {
    $result = $api_instance->salesShipOrderV1ExecutePost($orderId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesShipOrderV1Api->salesShipOrderV1ExecutePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orderId** | **int**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body85**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body85.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

