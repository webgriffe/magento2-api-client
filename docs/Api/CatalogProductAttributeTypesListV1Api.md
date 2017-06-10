# Webgriffe\MagentoApiClient\CatalogProductAttributeTypesListV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductAttributeTypesListV1GetItemsGet**](CatalogProductAttributeTypesListV1Api.md#catalogProductAttributeTypesListV1GetItemsGet) | **GET** /V1/products/attributes/types | 


# **catalogProductAttributeTypesListV1GetItemsGet**
> \Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeTypeInterface[] catalogProductAttributeTypesListV1GetItemsGet()



Retrieve list of product attribute types

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductAttributeTypesListV1Api();

try {
    $result = $api_instance->catalogProductAttributeTypesListV1GetItemsGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductAttributeTypesListV1Api->catalogProductAttributeTypesListV1GetItemsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeTypeInterface[]**](../Model/CatalogDataProductAttributeTypeInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

