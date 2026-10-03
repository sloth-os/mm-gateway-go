# ManagedBudget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LimitUsd** | Pointer to **NullableFloat32** |  | [optional] 
**Period** | Pointer to **string** |  | [optional] [default to "month"]
**ScopesLimitUsd** | Pointer to **NullableFloat32** |  | [optional] 

## Methods

### NewManagedBudget

`func NewManagedBudget() *ManagedBudget`

NewManagedBudget instantiates a new ManagedBudget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedBudgetWithDefaults

`func NewManagedBudgetWithDefaults() *ManagedBudget`

NewManagedBudgetWithDefaults instantiates a new ManagedBudget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimitUsd

`func (o *ManagedBudget) GetLimitUsd() float32`

GetLimitUsd returns the LimitUsd field if non-nil, zero value otherwise.

### GetLimitUsdOk

`func (o *ManagedBudget) GetLimitUsdOk() (*float32, bool)`

GetLimitUsdOk returns a tuple with the LimitUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitUsd

`func (o *ManagedBudget) SetLimitUsd(v float32)`

SetLimitUsd sets LimitUsd field to given value.

### HasLimitUsd

`func (o *ManagedBudget) HasLimitUsd() bool`

HasLimitUsd returns a boolean if a field has been set.

### SetLimitUsdNil

`func (o *ManagedBudget) SetLimitUsdNil(b bool)`

 SetLimitUsdNil sets the value for LimitUsd to be an explicit nil

### UnsetLimitUsd
`func (o *ManagedBudget) UnsetLimitUsd()`

UnsetLimitUsd ensures that no value is present for LimitUsd, not even an explicit nil
### GetPeriod

`func (o *ManagedBudget) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *ManagedBudget) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *ManagedBudget) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *ManagedBudget) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetScopesLimitUsd

`func (o *ManagedBudget) GetScopesLimitUsd() float32`

GetScopesLimitUsd returns the ScopesLimitUsd field if non-nil, zero value otherwise.

### GetScopesLimitUsdOk

`func (o *ManagedBudget) GetScopesLimitUsdOk() (*float32, bool)`

GetScopesLimitUsdOk returns a tuple with the ScopesLimitUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopesLimitUsd

`func (o *ManagedBudget) SetScopesLimitUsd(v float32)`

SetScopesLimitUsd sets ScopesLimitUsd field to given value.

### HasScopesLimitUsd

`func (o *ManagedBudget) HasScopesLimitUsd() bool`

HasScopesLimitUsd returns a boolean if a field has been set.

### SetScopesLimitUsdNil

`func (o *ManagedBudget) SetScopesLimitUsdNil(b bool)`

 SetScopesLimitUsdNil sets the value for ScopesLimitUsd to be an explicit nil

### UnsetScopesLimitUsd
`func (o *ManagedBudget) UnsetScopesLimitUsd()`

UnsetScopesLimitUsd ensures that no value is present for ScopesLimitUsd, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


