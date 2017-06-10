# Webgriffe\MagentoApiClient\SalesInvoiceCommentRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**salesInvoiceCommentRepositoryV1SavePost**](SalesInvoiceCommentRepositoryV1Api.md#salesInvoiceCommentRepositoryV1SavePost) | **POST** /V1/invoices/comments | 


# **salesInvoiceCommentRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesDataInvoiceCommentInterface salesInvoiceCommentRepositoryV1SavePost($body)



Performs persist operations for a specified invoice comment.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesInvoiceCommentRepositoryV1Api();
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body76(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body76 | 

try {
    $result = $api_instance->salesInvoiceCommentRepositoryV1SavePost($body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesInvoiceCommentRepositoryV1Api->salesInvoiceCommentRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body76**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body76.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesDataInvoiceCommentInterface**](../Model/SalesDataInvoiceCommentInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

