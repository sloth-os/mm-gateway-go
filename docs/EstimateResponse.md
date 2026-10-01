# EstimateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Budget** | Pointer to [**NullableBudgetState**](BudgetState.md) |  | [optional] 
**Candidates** | Pointer to [**[]EstimateCandidate**](EstimateCandidate.md) |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] [default to "USD"]
**EstimatedCost** | Pointer to **NullableFloat32** |  | [optional] 
**Modality** | **string** |  | 
**Model** | Pointer to **NullableString** |  | [optional] 
**Object** | Pointer to **string** |  | [optional] [default to "estimate"]

## Methods

### NewEstimateResponse

`func NewEstimateResponse(modality string, ) *EstimateResponse`

NewEstimateResponse instantiates a new EstimateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEstimateResponseWithDefaults

`func NewEstimateResponseWithDefaults() *EstimateResponse`

NewEstimateResponseWithDefaults instantiates a new EstimateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBudget

`func (o *EstimateResponse) GetBudget() BudgetState`

GetBudget returns the Budget field if non-nil, zero value otherwise.

### GetBudgetOk

`func (o *EstimateResponse) GetBudgetOk() (*BudgetState, bool)`

GetBudgetOk returns a tuple with the Budget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudget

`func (o *EstimateResponse) SetBudget(v BudgetState)`

SetBudget sets Budget field to given value.

### HasBudget

`func (o *EstimateResponse) HasBudget() bool`

HasBudget returns a boolean if a field has been set.

### SetBudgetNil

`func (o *EstimateResponse) SetBudgetNil(b bool)`

 SetBudgetNil sets the value for Budget to be an explicit nil

### UnsetBudget
`func (o *EstimateResponse) UnsetBudget()`

UnsetBudget ensures that no value is present for Budget, not even an explicit nil
### GetCandidates

`func (o *EstimateResponse) GetCandidates() []EstimateCandidate`

GetCandidates returns the Candidates field if non-nil, zero value otherwise.

### GetCandidatesOk

`func (o *EstimateResponse) GetCandidatesOk() (*[]EstimateCandidate, bool)`

GetCandidatesOk returns a tuple with the Candidates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCandidates

`func (o *EstimateResponse) SetCandidates(v []EstimateCandidate)`

SetCandidates sets Candidates field to given value.

### HasCandidates

`func (o *EstimateResponse) HasCandidates() bool`

HasCandidates returns a boolean if a field has been set.

### GetCurrency

`func (o *EstimateResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *EstimateResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *EstimateResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *EstimateResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetEstimatedCost

`func (o *EstimateResponse) GetEstimatedCost() float32`

GetEstimatedCost returns the EstimatedCost field if non-nil, zero value otherwise.

### GetEstimatedCostOk

`func (o *EstimateResponse) GetEstimatedCostOk() (*float32, bool)`

GetEstimatedCostOk returns a tuple with the EstimatedCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedCost

`func (o *EstimateResponse) SetEstimatedCost(v float32)`

SetEstimatedCost sets EstimatedCost field to given value.

### HasEstimatedCost

`func (o *EstimateResponse) HasEstimatedCost() bool`

HasEstimatedCost returns a boolean if a field has been set.

### SetEstimatedCostNil

`func (o *EstimateResponse) SetEstimatedCostNil(b bool)`

 SetEstimatedCostNil sets the value for EstimatedCost to be an explicit nil

### UnsetEstimatedCost
`func (o *EstimateResponse) UnsetEstimatedCost()`

UnsetEstimatedCost ensures that no value is present for EstimatedCost, not even an explicit nil
### GetModality

`func (o *EstimateResponse) GetModality() string`

GetModality returns the Modality field if non-nil, zero value otherwise.

### GetModalityOk

`func (o *EstimateResponse) GetModalityOk() (*string, bool)`

GetModalityOk returns a tuple with the Modality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModality

`func (o *EstimateResponse) SetModality(v string)`

SetModality sets Modality field to given value.


### GetModel

`func (o *EstimateResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *EstimateResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *EstimateResponse) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *EstimateResponse) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *EstimateResponse) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *EstimateResponse) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetObject

`func (o *EstimateResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *EstimateResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *EstimateResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *EstimateResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


