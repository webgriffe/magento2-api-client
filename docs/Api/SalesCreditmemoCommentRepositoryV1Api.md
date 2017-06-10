# Webgriffe\MagentoApiClient\SalesCreditmemoCommentRepositoryV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**salesCreditmemoCommentRepositoryV1SavePost**](SalesCreditmemoCommentRepositoryV1Api.md#salesCreditmemoCommentRepositoryV1SavePost) | **POST** /V1/creditmemo/{id}/comments | 


# **salesCreditmemoCommentRepositoryV1SavePost**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesDataCreditmemoCommentInterface salesCreditmemoCommentRepositoryV1SavePost($id, $body)



Performs persist operations for a specified entity.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\SalesCreditmemoCommentRepositoryV1Api();
$id = "id_example"; // string | 
$body = new \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body78(); // \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body78 | 

try {
    $result = $api_instance->salesCreditmemoCommentRepositoryV1SavePost($id, $body);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling SalesCreditmemoCommentRepositoryV1Api->salesCreditmemoCommentRepositoryV1SavePost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string**|  |
 **body** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body78**](../Model/\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\Body78.md)|  | [optional]

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesDataCreditmemoCommentInterface**](../Model/SalesDataCreditmemoCommentInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

