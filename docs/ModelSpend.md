# ModelSpend

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Modality** | **string** |  | 
**Model** | **string** |  | 
**SpentUsd** | Pointer to **float32** |  | [optional] [default to 0.0]
**Tasks** | Pointer to **int32** |  | [optional] [default to 0]

## Methods

### NewModelSpend

`func NewModelSpend(modality string, model string, ) *ModelSpend`

NewModelSpend instantiates a new ModelSpend object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelSpendWithDefaults

`func NewModelSpendWithDefaults() *ModelSpend`

NewModelSpendWithDefaults instantiates a new ModelSpend object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModality

`func (o *ModelSpend) GetModality() string`

GetModality returns the Modality field if non-nil, zero value otherwise.

### GetModalityOk

`func (o *ModelSpend) GetModalityOk() (*string, bool)`

GetModalityOk returns a tuple with the Modality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModality

`func (o *ModelSpend) SetModality(v string)`

SetModality sets Modality field to given value.


### GetModel

`func (o *ModelSpend) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ModelSpend) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ModelSpend) SetModel(v string)`

SetModel sets Model field to given value.


### GetSpentUsd

`func (o *ModelSpend) GetSpentUsd() float32`

GetSpentUsd returns the SpentUsd field if non-nil, zero value otherwise.

### GetSpentUsdOk

`func (o *ModelSpend) GetSpentUsdOk() (*float32, bool)`

GetSpentUsdOk returns a tuple with the SpentUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpentUsd

`func (o *ModelSpend) SetSpentUsd(v float32)`

SetSpentUsd sets SpentUsd field to given value.

### HasSpentUsd

`func (o *ModelSpend) HasSpentUsd() bool`

HasSpentUsd returns a boolean if a field has been set.

### GetTasks

`func (o *ModelSpend) GetTasks() int32`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *ModelSpend) GetTasksOk() (*int32, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *ModelSpend) SetTasks(v int32)`

SetTasks sets Tasks field to given value.

### HasTasks

`func (o *ModelSpend) HasTasks() bool`

HasTasks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


