# RoutingDirective

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Budget** | Pointer to [**NullableBudgetDirective**](BudgetDirective.md) |  | [optional] 
**Fallback** | Pointer to **NullableString** | Pinned models only: &#x60;none&#x60; (default) tries one backend, &#x60;same_model&#x60; every backend/account serving the model, &#x60;any&#x60; also the replacement and the auto candidates when the model is retired or unavailable. | [optional] 
**MaxCostUsd** | Pointer to **NullableFloat32** | Hard per-task ceiling on the estimated cost in USD; unpriced models are excluded. | [optional] 
**Optimize** | Pointer to **NullableString** | How admissible candidates are ordered (default: the gateway&#39;s default, &#x60;balanced&#x60;). | [optional] 
**Profile** | Pointer to **NullableString** | Gateway-defined routing profile, such as &#x60;quality&#x60;, &#x60;fast&#x60;, or &#x60;eu&#x60;. It never names a provider or backend. | [optional] 

## Methods

### NewRoutingDirective

`func NewRoutingDirective() *RoutingDirective`

NewRoutingDirective instantiates a new RoutingDirective object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingDirectiveWithDefaults

`func NewRoutingDirectiveWithDefaults() *RoutingDirective`

NewRoutingDirectiveWithDefaults instantiates a new RoutingDirective object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBudget

`func (o *RoutingDirective) GetBudget() BudgetDirective`

GetBudget returns the Budget field if non-nil, zero value otherwise.

### GetBudgetOk

`func (o *RoutingDirective) GetBudgetOk() (*BudgetDirective, bool)`

GetBudgetOk returns a tuple with the Budget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudget

`func (o *RoutingDirective) SetBudget(v BudgetDirective)`

SetBudget sets Budget field to given value.

### HasBudget

`func (o *RoutingDirective) HasBudget() bool`

HasBudget returns a boolean if a field has been set.

### SetBudgetNil

`func (o *RoutingDirective) SetBudgetNil(b bool)`

 SetBudgetNil sets the value for Budget to be an explicit nil

### UnsetBudget
`func (o *RoutingDirective) UnsetBudget()`

UnsetBudget ensures that no value is present for Budget, not even an explicit nil
### GetFallback

`func (o *RoutingDirective) GetFallback() string`

GetFallback returns the Fallback field if non-nil, zero value otherwise.

### GetFallbackOk

`func (o *RoutingDirective) GetFallbackOk() (*string, bool)`

GetFallbackOk returns a tuple with the Fallback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFallback

`func (o *RoutingDirective) SetFallback(v string)`

SetFallback sets Fallback field to given value.

### HasFallback

`func (o *RoutingDirective) HasFallback() bool`

HasFallback returns a boolean if a field has been set.

### SetFallbackNil

`func (o *RoutingDirective) SetFallbackNil(b bool)`

 SetFallbackNil sets the value for Fallback to be an explicit nil

### UnsetFallback
`func (o *RoutingDirective) UnsetFallback()`

UnsetFallback ensures that no value is present for Fallback, not even an explicit nil
### GetMaxCostUsd

`func (o *RoutingDirective) GetMaxCostUsd() float32`

GetMaxCostUsd returns the MaxCostUsd field if non-nil, zero value otherwise.

### GetMaxCostUsdOk

`func (o *RoutingDirective) GetMaxCostUsdOk() (*float32, bool)`

GetMaxCostUsdOk returns a tuple with the MaxCostUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCostUsd

`func (o *RoutingDirective) SetMaxCostUsd(v float32)`

SetMaxCostUsd sets MaxCostUsd field to given value.

### HasMaxCostUsd

`func (o *RoutingDirective) HasMaxCostUsd() bool`

HasMaxCostUsd returns a boolean if a field has been set.

### SetMaxCostUsdNil

`func (o *RoutingDirective) SetMaxCostUsdNil(b bool)`

 SetMaxCostUsdNil sets the value for MaxCostUsd to be an explicit nil

### UnsetMaxCostUsd
`func (o *RoutingDirective) UnsetMaxCostUsd()`

UnsetMaxCostUsd ensures that no value is present for MaxCostUsd, not even an explicit nil
### GetOptimize

`func (o *RoutingDirective) GetOptimize() string`

GetOptimize returns the Optimize field if non-nil, zero value otherwise.

### GetOptimizeOk

`func (o *RoutingDirective) GetOptimizeOk() (*string, bool)`

GetOptimizeOk returns a tuple with the Optimize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptimize

`func (o *RoutingDirective) SetOptimize(v string)`

SetOptimize sets Optimize field to given value.

### HasOptimize

`func (o *RoutingDirective) HasOptimize() bool`

HasOptimize returns a boolean if a field has been set.

### SetOptimizeNil

`func (o *RoutingDirective) SetOptimizeNil(b bool)`

 SetOptimizeNil sets the value for Optimize to be an explicit nil

### UnsetOptimize
`func (o *RoutingDirective) UnsetOptimize()`

UnsetOptimize ensures that no value is present for Optimize, not even an explicit nil
### GetProfile

`func (o *RoutingDirective) GetProfile() string`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *RoutingDirective) GetProfileOk() (*string, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *RoutingDirective) SetProfile(v string)`

SetProfile sets Profile field to given value.

### HasProfile

`func (o *RoutingDirective) HasProfile() bool`

HasProfile returns a boolean if a field has been set.

### SetProfileNil

`func (o *RoutingDirective) SetProfileNil(b bool)`

 SetProfileNil sets the value for Profile to be an explicit nil

### UnsetProfile
`func (o *RoutingDirective) UnsetProfile()`

UnsetProfile ensures that no value is present for Profile, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


