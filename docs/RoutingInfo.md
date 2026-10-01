# RoutingInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attempts** | Pointer to **int32** |  | [optional] [default to 1]
**Budget** | Pointer to [**NullableBudgetState**](BudgetState.md) |  | [optional] 
**EstimatedCost** | Pointer to **NullableFloat32** |  | [optional] 
**Fallback** | Pointer to **bool** |  | [optional] [default to false]
**FallbackReason** | Pointer to **NullableString** |  | [optional] 
**Optimize** | Pointer to **string** |  | [optional] [default to "balanced"]
**RequestedModel** | **string** |  | 

## Methods

### NewRoutingInfo

`func NewRoutingInfo(requestedModel string, ) *RoutingInfo`

NewRoutingInfo instantiates a new RoutingInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingInfoWithDefaults

`func NewRoutingInfoWithDefaults() *RoutingInfo`

NewRoutingInfoWithDefaults instantiates a new RoutingInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttempts

`func (o *RoutingInfo) GetAttempts() int32`

GetAttempts returns the Attempts field if non-nil, zero value otherwise.

### GetAttemptsOk

`func (o *RoutingInfo) GetAttemptsOk() (*int32, bool)`

GetAttemptsOk returns a tuple with the Attempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempts

`func (o *RoutingInfo) SetAttempts(v int32)`

SetAttempts sets Attempts field to given value.

### HasAttempts

`func (o *RoutingInfo) HasAttempts() bool`

HasAttempts returns a boolean if a field has been set.

### GetBudget

`func (o *RoutingInfo) GetBudget() BudgetState`

GetBudget returns the Budget field if non-nil, zero value otherwise.

### GetBudgetOk

`func (o *RoutingInfo) GetBudgetOk() (*BudgetState, bool)`

GetBudgetOk returns a tuple with the Budget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudget

`func (o *RoutingInfo) SetBudget(v BudgetState)`

SetBudget sets Budget field to given value.

### HasBudget

`func (o *RoutingInfo) HasBudget() bool`

HasBudget returns a boolean if a field has been set.

### SetBudgetNil

`func (o *RoutingInfo) SetBudgetNil(b bool)`

 SetBudgetNil sets the value for Budget to be an explicit nil

### UnsetBudget
`func (o *RoutingInfo) UnsetBudget()`

UnsetBudget ensures that no value is present for Budget, not even an explicit nil
### GetEstimatedCost

`func (o *RoutingInfo) GetEstimatedCost() float32`

GetEstimatedCost returns the EstimatedCost field if non-nil, zero value otherwise.

### GetEstimatedCostOk

`func (o *RoutingInfo) GetEstimatedCostOk() (*float32, bool)`

GetEstimatedCostOk returns a tuple with the EstimatedCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedCost

`func (o *RoutingInfo) SetEstimatedCost(v float32)`

SetEstimatedCost sets EstimatedCost field to given value.

### HasEstimatedCost

`func (o *RoutingInfo) HasEstimatedCost() bool`

HasEstimatedCost returns a boolean if a field has been set.

### SetEstimatedCostNil

`func (o *RoutingInfo) SetEstimatedCostNil(b bool)`

 SetEstimatedCostNil sets the value for EstimatedCost to be an explicit nil

### UnsetEstimatedCost
`func (o *RoutingInfo) UnsetEstimatedCost()`

UnsetEstimatedCost ensures that no value is present for EstimatedCost, not even an explicit nil
### GetFallback

`func (o *RoutingInfo) GetFallback() bool`

GetFallback returns the Fallback field if non-nil, zero value otherwise.

### GetFallbackOk

`func (o *RoutingInfo) GetFallbackOk() (*bool, bool)`

GetFallbackOk returns a tuple with the Fallback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFallback

`func (o *RoutingInfo) SetFallback(v bool)`

SetFallback sets Fallback field to given value.

### HasFallback

`func (o *RoutingInfo) HasFallback() bool`

HasFallback returns a boolean if a field has been set.

### GetFallbackReason

`func (o *RoutingInfo) GetFallbackReason() string`

GetFallbackReason returns the FallbackReason field if non-nil, zero value otherwise.

### GetFallbackReasonOk

`func (o *RoutingInfo) GetFallbackReasonOk() (*string, bool)`

GetFallbackReasonOk returns a tuple with the FallbackReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFallbackReason

`func (o *RoutingInfo) SetFallbackReason(v string)`

SetFallbackReason sets FallbackReason field to given value.

### HasFallbackReason

`func (o *RoutingInfo) HasFallbackReason() bool`

HasFallbackReason returns a boolean if a field has been set.

### SetFallbackReasonNil

`func (o *RoutingInfo) SetFallbackReasonNil(b bool)`

 SetFallbackReasonNil sets the value for FallbackReason to be an explicit nil

### UnsetFallbackReason
`func (o *RoutingInfo) UnsetFallbackReason()`

UnsetFallbackReason ensures that no value is present for FallbackReason, not even an explicit nil
### GetOptimize

`func (o *RoutingInfo) GetOptimize() string`

GetOptimize returns the Optimize field if non-nil, zero value otherwise.

### GetOptimizeOk

`func (o *RoutingInfo) GetOptimizeOk() (*string, bool)`

GetOptimizeOk returns a tuple with the Optimize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptimize

`func (o *RoutingInfo) SetOptimize(v string)`

SetOptimize sets Optimize field to given value.

### HasOptimize

`func (o *RoutingInfo) HasOptimize() bool`

HasOptimize returns a boolean if a field has been set.

### GetRequestedModel

`func (o *RoutingInfo) GetRequestedModel() string`

GetRequestedModel returns the RequestedModel field if non-nil, zero value otherwise.

### GetRequestedModelOk

`func (o *RoutingInfo) GetRequestedModelOk() (*string, bool)`

GetRequestedModelOk returns a tuple with the RequestedModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedModel

`func (o *RoutingInfo) SetRequestedModel(v string)`

SetRequestedModel sets RequestedModel field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


