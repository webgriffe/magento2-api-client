# Webgriffe\MagentoApiClient\CatalogProductCustomOptionTypeListV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductCustomOptionTypeListV1GetItemsGet**](CatalogProductCustomOptionTypeListV1Api.md#catalogProductCustomOptionTypeListV1GetItemsGet) | **GET** /V1/products/options/types | 


# **catalogProductCustomOptionTypeListV1GetItemsGet**
> \Webgriffe\MagentoApiClient\Model\CatalogDataProductCustomOptionTypeInterface[] catalogProductCustomOptionTypeListV1GetItemsGet()



Get custom option types

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductCustomOptionTypeListV1Api();

try {
    $result = $api_instance->catalogProductCustomOptionTypeListV1GetItemsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductCustomOptionTypeListV1Api->catalogProductCustomOptionTypeListV1GetItemsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Webgriffe\MagentoApiClient\Model\CatalogDataProductCustomOptionTypeInterface[]**](../Model/CatalogDataProductCustomOptionTypeInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

