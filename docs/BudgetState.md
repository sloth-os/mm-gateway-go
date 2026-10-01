# BudgetState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LimitUsd** | Pointer to **NullableFloat32** |  | [optional] 
**RemainingUsd** | Pointer to **NullableFloat32** |  | [optional] 
**ReservedUsd** | Pointer to **float32** |  | [optional] [default to 0.0]
**Scope** | Pointer to **NullableString** |  | [optional] 
**SpentUsd** | Pointer to **float32** |  | [optional] [default to 0.0]
**Tasks** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewBudgetState

`func NewBudgetState() *BudgetState`

NewBudgetState instantiates a new BudgetState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBudgetStateWithDefaults

`func NewBudgetStateWithDefaults() *BudgetState`

NewBudgetStateWithDefaults instantiates a new BudgetState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimitUsd

`func (o *BudgetState) GetLimitUsd() float32`

GetLimitUsd returns the LimitUsd field if non-nil, zero value otherwise.

### GetLimitUsdOk

`func (o *BudgetState) GetLimitUsdOk() (*float32, bool)`

GetLimitUsdOk returns a tuple with the LimitUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitUsd

`func (o *BudgetState) SetLimitUsd(v float32)`

SetLimitUsd sets LimitUsd field to given value.

### HasLimitUsd

`func (o *BudgetState) HasLimitUsd() bool`

HasLimitUsd returns a boolean if a field has been set.

### SetLimitUsdNil

`func (o *BudgetState) SetLimitUsdNil(b bool)`

 SetLimitUsdNil sets the value for LimitUsd to be an explicit nil

### UnsetLimitUsd
`func (o *BudgetState) UnsetLimitUsd()`

UnsetLimitUsd ensures that no value is present for LimitUsd, not even an explicit nil
### GetRemainingUsd

`func (o *BudgetState) GetRemainingUsd() float32`

GetRemainingUsd returns the RemainingUsd field if non-nil, zero value otherwise.

### GetRemainingUsdOk

`func (o *BudgetState) GetRemainingUsdOk() (*float32, bool)`

GetRemainingUsdOk returns a tuple with the RemainingUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemainingUsd

`func (o *BudgetState) SetRemainingUsd(v float32)`

SetRemainingUsd sets RemainingUsd field to given value.

### HasRemainingUsd

`func (o *BudgetState) HasRemainingUsd() bool`

HasRemainingUsd returns a boolean if a field has been set.

### SetRemainingUsdNil

`func (o *BudgetState) SetRemainingUsdNil(b bool)`

 SetRemainingUsdNil sets the value for RemainingUsd to be an explicit nil

### UnsetRemainingUsd
`func (o *BudgetState) UnsetRemainingUsd()`

UnsetRemainingUsd ensures that no value is present for RemainingUsd, not even an explicit nil
### GetReservedUsd

`func (o *BudgetState) GetReservedUsd() float32`

GetReservedUsd returns the ReservedUsd field if non-nil, zero value otherwise.

### GetReservedUsdOk

`func (o *BudgetState) GetReservedUsdOk() (*float32, bool)`

GetReservedUsdOk returns a tuple with the ReservedUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedUsd

`func (o *BudgetState) SetReservedUsd(v float32)`

SetReservedUsd sets ReservedUsd field to given value.

### HasReservedUsd

`func (o *BudgetState) HasReservedUsd() bool`

HasReservedUsd returns a boolean if a field has been set.

### GetScope

`func (o *BudgetState) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *BudgetState) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *BudgetState) SetScope(v string)`

SetScope sets Scope field to given value.

### HasScope

`func (o *BudgetState) HasScope() bool`

HasScope returns a boolean if a field has been set.

### SetScopeNil

`func (o *BudgetState) SetScopeNil(b bool)`

 SetScopeNil sets the value for Scope to be an explicit nil

### UnsetScope
`func (o *BudgetState) UnsetScope()`

UnsetScope ensures that no value is present for Scope, not even an explicit nil
### GetSpentUsd

`func (o *BudgetState) GetSpentUsd() float32`

GetSpentUsd returns the SpentUsd field if non-nil, zero value otherwise.

### GetSpentUsdOk

`func (o *BudgetState) GetSpentUsdOk() (*float32, bool)`

GetSpentUsdOk returns a tuple with the SpentUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpentUsd

`func (o *BudgetState) SetSpentUsd(v float32)`

SetSpentUsd sets SpentUsd field to given value.

### HasSpentUsd

`func (o *BudgetState) HasSpentUsd() bool`

HasSpentUsd returns a boolean if a field has been set.

### GetTasks

`func (o *BudgetState) GetTasks() int32`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *BudgetState) GetTasksOk() (*int32, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *BudgetState) SetTasks(v int32)`

SetTasks sets Tasks field to given value.

### HasTasks

`func (o *BudgetState) HasTasks() bool`

HasTasks returns a boolean if a field has been set.

### SetTasksNil

`func (o *BudgetState) SetTasksNil(b bool)`

 SetTasksNil sets the value for Tasks to be an explicit nil

### UnsetTasks
`func (o *BudgetState) UnsetTasks()`

UnsetTasks ensures that no value is present for Tasks, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


