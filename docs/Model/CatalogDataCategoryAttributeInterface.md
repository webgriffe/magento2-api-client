# CatalogDataCategoryAttributeInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**isWysiwygEnabled** | **bool** | WYSIWYG flag | [optional] 
**isHtmlAllowedOnFront** | **bool** | The HTML tags are allowed on the frontend | [optional] 
**usedForSortBy** | **bool** | It is used for sorting in product listing | [optional] 
**isFilterable** | **bool** | It used in layered navigation | [optional] 
**isFilterableInSearch** | **bool** | It is used in search results layered navigation | [optional] 
**isUsedInGrid** | **bool** | It is used in catalog product grid | [optional] 
**isVisibleInGrid** | **bool** | It is visible in catalog product grid | [optional] 
**isFilterableInGrid** | **bool** | It is filterable in catalog product grid | [optional] 
**position** | **int** | Position | [optional] 
**applyTo** | **string[]** | Apply to value for the element | [optional] 
**isSearchable** | **string** | The attribute can be used in Quick Search | [optional] 
**isVisibleInAdvancedSearch** | **string** | The attribute can be used in Advanced Search | [optional] 
**isComparable** | **string** | The attribute can be compared on the frontend | [optional] 
**isUsedForPromoRules** | **string** | The attribute can be used for promo rules | [optional] 
**isVisibleOnFront** | **string** | The attribute is visible on the frontend | [optional] 
**usedInProductListing** | **string** | The attribute can be used in product listing | [optional] 
**isVisible** | **bool** | Attribute is visible on frontend. | [optional] 
**scope** | **string** | Attribute scope | [optional] 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\CatalogDataEavAttributeExtensionInterface**](CatalogDataEavAttributeExtensionInterface.md) |  | [optional] 
**attributeId** | **int** | Id of the attribute. | [optional] 
**attributeCode** | **string** | Code of the attribute. | 
**frontendInput** | **string** | HTML for input element. | 
**entityTypeId** | **string** | Entity type id | [optional] 
**isRequired** | **bool** | Attribute is required. | 
**options** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\EavDataAttributeOptionInterface[]**](EavDataAttributeOptionInterface.md) | Options of the attribute (key &#x3D;&gt; value pairs for select) | [optional] 
**isUserDefined** | **bool** | Current attribute has been defined by a user. | [optional] 
**defaultFrontendLabel** | **string** | Frontend label for default store | [optional] 
**frontendLabels** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\EavDataAttributeFrontendLabelInterface[]**](EavDataAttributeFrontendLabelInterface.md) | Frontend label for each store | 
**note** | **string** | The note attribute for the element. | [optional] 
**backendType** | **string** | Backend type. | [optional] 
**backendModel** | **string** | Backend model | [optional] 
**sourceModel** | **string** | Source model | [optional] 
**defaultValue** | **string** | Default value for the element. | [optional] 
**isUnique** | **string** | This is a unique attribute | [optional] 
**frontendClass** | **string** | Frontend class of attribute | [optional] 
**validationRules** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\EavDataAttributeValidationRuleInterface[]**](EavDataAttributeValidationRuleInterface.md) | Validation rules. | [optional] 
**customAttributes** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\FrameworkAttributeInterface[]**](FrameworkAttributeInterface.md) | Custom attributes values. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


