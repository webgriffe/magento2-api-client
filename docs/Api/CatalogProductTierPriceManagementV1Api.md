# Webgriffe\MagentoApiClient\CatalogProductTierPriceManagementV1Api

All URIs are relative to *http://t213.vg/rest/default*

Method | HTTP request | Description
------------- | ------------- | -------------
[**catalogProductTierPriceManagementV1AddPost**](CatalogProductTierPriceManagementV1Api.md#catalogProductTierPriceManagementV1AddPost) | **POST** /V1/products/{sku}/group-prices/{customerGroupId}/tiers/{qty}/price/{price} | 
[**catalogProductTierPriceManagementV1GetListGet**](CatalogProductTierPriceManagementV1Api.md#catalogProductTierPriceManagementV1GetListGet) | **GET** /V1/products/{sku}/group-prices/{customerGroupId}/tiers | 
[**catalogProductTierPriceManagementV1RemoveDelete**](CatalogProductTierPriceManagementV1Api.md#catalogProductTierPriceManagementV1RemoveDelete) | **DELETE** /V1/products/{sku}/group-prices/{customerGroupId}/tiers/{qty} | 


# **catalogProductTierPriceManagementV1AddPost**
> bool catalogProductTierPriceManagementV1AddPost($sku, $customerGroupId, $price, $qty)



Create tier price for product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductTierPriceManagementV1Api();
$sku = "sku_example"; // string | 
$customerGroupId = "customerGroupId_example"; // string | 'all' can be used to specify 'ALL GROUPS'
$price = 3.4; // float | 
$qty = 3.4; // float | 

try {
    $result = $api_instance->catalogProductTierPriceManagementV1AddPost($sku, $customerGroupId, $price, $qty);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductTierPriceManagementV1Api->catalogProductTierPriceManagementV1AddPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **customerGroupId** | **string**| &#39;all&#39; can be used to specify &#39;ALL GROUPS&#39; |
 **price** | **float**|  |
 **qty** | **float**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductTierPriceManagementV1GetListGet**
> \Webgriffe\MagentoApiClient\Model\CatalogDataProductTierPriceInterface[] catalogProductTierPriceManagementV1GetListGet($sku, $customerGroupId)



Get tier price of product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductTierPriceManagementV1Api();
$sku = "sku_example"; // string | 
$customerGroupId = "customerGroupId_example"; // string | 'all' can be used to specify 'ALL GROUPS'

try {
    $result = $api_instance->catalogProductTierPriceManagementV1GetListGet($sku, $customerGroupId);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductTierPriceManagementV1Api->catalogProductTierPriceManagementV1GetListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **customerGroupId** | **string**| &#39;all&#39; can be used to specify &#39;ALL GROUPS&#39; |

### Return type

[**\Webgriffe\MagentoApiClient\Model\CatalogDataProductTierPriceInterface[]**](../Model/CatalogDataProductTierPriceInterface.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **catalogProductTierPriceManagementV1RemoveDelete**
> bool catalogProductTierPriceManagementV1RemoveDelete($sku, $customerGroupId, $qty)



Remove tier price from product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Webgriffe\MagentoApiClient\Api\CatalogProductTierPriceManagementV1Api();
$sku = "sku_example"; // string | 
$customerGroupId = "customerGroupId_example"; // string | 'all' can be used to specify 'ALL GROUPS'
$qty = 3.4; // float | 

try {
    $result = $api_instance->catalogProductTierPriceManagementV1RemoveDelete($sku, $customerGroupId, $qty);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling CatalogProductTierPriceManagementV1Api->catalogProductTierPriceManagementV1RemoveDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sku** | **string**|  |
 **customerGroupId** | **string**| &#39;all&#39; can be used to specify &#39;ALL GROUPS&#39; |
 **qty** | **float**|  |

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

