# Webgriffe\MagentoApiClient\CatalogProductMediaAttributeManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductMediaAttributeManagementV1GetListGet**](CatalogProductMediaAttributeManagementV1Api.md#catalogProductMediaAttributeManagementV1GetListGet) | **GET** /V1/products/media/types/{attributeSetName} | 


# **catalogProductMediaAttributeManagementV1GetListGet**
> \Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface[] catalogProductMediaAttributeManagementV1GetListGet($attributeSetName)



Retrieve the list of media attributes (fronted input type is media_image) assigned to the given attribute set.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductMediaAttributeManagementV1Api();
$attributeSetName = "attributeSetName_example"; // string | 

try {
    $result = $api_instance->catalogProductMediaAttributeManagementV1GetListGet($attributeSetName);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductMediaAttributeManagementV1Api->catalogProductMediaAttributeManagementV1GetListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attributeSetName** | **string**|  |

### Return type

[**\Webgriffe\MagentoApiClient\Model\CatalogDataProductAttributeInterface[]**](../Model/CatalogDataProductAttributeInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

