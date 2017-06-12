# Webgriffe\MagentoApiClient\CatalogCategoryAttributeOptionManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogCategoryAttributeOptionManagementV1GetItemsGet**](CatalogCategoryAttributeOptionManagementV1Api.md#catalogCategoryAttributeOptionManagementV1GetItemsGet) | **GET** /V1/categories/attributes/{attributeCode}/options | 


# **catalogCategoryAttributeOptionManagementV1GetItemsGet**
> \Webgriffe\MagentoApiClient\Model\EavDataAttributeOptionInterface[] catalogCategoryAttributeOptionManagementV1GetItemsGet($attributeCode)



Retrieve list of attribute options

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogCategoryAttributeOptionManagementV1Api();
$attributeCode = "attributeCode_example"; // string | 

try {
    $result = $api_instance->catalogCategoryAttributeOptionManagementV1GetItemsGet($attributeCode);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogCategoryAttributeOptionManagementV1Api->catalogCategoryAttributeOptionManagementV1GetItemsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeCode** | **string**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\EavDataAttributeOptionInterface[]**](../Model/EavDataAttributeOptionInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

