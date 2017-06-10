# SalesRuleDataRuleInterface

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ruleId** | **int** | Rule id | [optional] 
**name** | **string** | Rule name | [optional] 
**storeLabels** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataRuleLabelInterface[]**](SalesRuleDataRuleLabelInterface.md) | Display label | [optional] 
**description** | **string** | Description | [optional] 
**websiteIds** | **int[]** | A list of websites the rule applies to | 
**customerGroupIds** | **int[]** | Ids of customer groups that the rule applies to | 
**fromDate** | **string** | The start date when the coupon is active | [optional] 
**toDate** | **string** | The end date when the coupon is active | [optional] 
**usesPerCustomer** | **int** | Number of uses per customer | 
**isActive** | **bool** | The coupon is active | 
**condition** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataConditionInterface**](SalesRuleDataConditionInterface.md) |  | [optional] 
**actionCondition** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataConditionInterface**](SalesRuleDataConditionInterface.md) |  | [optional] 
**stopRulesProcessing** | **bool** | To stop rule processing | 
**isAdvanced** | **bool** | Is this field needed | 
**productIds** | **int[]** | Product ids | [optional] 
**sortOrder** | **int** | Sort order | 
**simpleAction** | **string** | Simple action of the rule | [optional] 
**discountAmount** | **float** | Discount amount | 
**discountQty** | **float** | Maximum qty discount is applied | [optional] 
**discountStep** | **int** | Discount step | 
**applyToShipping** | **bool** | The rule applies to shipping | 
**timesUsed** | **int** | How many times the rule has been used | 
**isRss** | **bool** | Whether the rule is in RSS | 
**couponType** | **string** | Coupon type | 
**useAutoGeneration** | **bool** | To auto generate coupon | 
**usesPerCoupon** | **int** | Limit of uses per coupon | 
**simpleFreeShipping** | **string** | To grant free shipping | [optional] 
**extensionAttributes** | [**\Webgriffe\MagentoApiClient\Webgriffe\MagentoApiClient\Model\SalesRuleDataRuleExtensionInterface**](SalesRuleDataRuleExtensionInterface.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


