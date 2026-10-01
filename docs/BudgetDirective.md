# BudgetDirective

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LimitUsd** | Pointer to **NullableFloat32** | Self-imposed cap for the scope in USD (the operator&#39;s scope cap still applies). | [optional] 
**Scope** | **string** | Spend bucket name (a project, a customer, a batch). | 

## Methods

### NewBudgetDirective

`func NewBudgetDirective(scope string, ) *BudgetDirective`

NewBudgetDirective instantiates a new BudgetDirective object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBudgetDirectiveWithDefaults

`func NewBudgetDirectiveWithDefaults() *BudgetDirective`

NewBudgetDirectiveWithDefaults instantiates a new BudgetDirective object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimitUsd

`func (o *BudgetDirective) GetLimitUsd() float32`

GetLimitUsd returns the LimitUsd field if non-nil, zero value otherwise.

### GetLimitUsdOk

`func (o *BudgetDirective) GetLimitUsdOk() (*float32, bool)`

GetLimitUsdOk returns a tuple with the LimitUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitUsd

`func (o *BudgetDirective) SetLimitUsd(v float32)`

SetLimitUsd sets LimitUsd field to given value.

### HasLimitUsd

`func (o *BudgetDirective) HasLimitUsd() bool`

HasLimitUsd returns a boolean if a field has been set.

### SetLimitUsdNil

`func (o *BudgetDirective) SetLimitUsdNil(b bool)`

 SetLimitUsdNil sets the value for LimitUsd to be an explicit nil

### UnsetLimitUsd
`func (o *BudgetDirective) UnsetLimitUsd()`

UnsetLimitUsd ensures that no value is present for LimitUsd, not even an explicit nil
### GetScope

`func (o *BudgetDirective) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *BudgetDirective) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *BudgetDirective) SetScope(v string)`

SetScope sets Scope field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


