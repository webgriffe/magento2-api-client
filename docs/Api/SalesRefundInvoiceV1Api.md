# Webgriffe\MagentoApiClient\SalesRefundInvoiceV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**salesRefundInvoiceV1ExecutePost**](SalesRefundInvoiceV1Api.md#salesRefundInvoiceV1ExecutePost) | **POST** /V1/invoice/{invoiceId}/refund | 


# **salesRefundInvoiceV1ExecutePost**
> int salesRefundInvoiceV1ExecutePost($invoiceId, $body)



Create refund for invoice

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesRefundInvoiceV1Api();
$invoiceId = 56; // int | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body77(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body77 | 

try {
    $result = $api_instance->salesRefundInvoiceV1ExecutePost($invoiceId, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesRefundInvoiceV1Api->salesRefundInvoiceV1ExecutePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **invoiceId** | **int**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body77**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body77.md)|  | [optional]

### Return type

**int**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

