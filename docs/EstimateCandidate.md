# EstimateCandidate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Admissible** | Pointer to **bool** |  | [optional] [default to true]
**EstimatedCost** | Pointer to **NullableFloat32** |  | [optional] 
**Lifecycle** | Pointer to **string** |  | [optional] [default to "active"]
**Model** | **string** |  | 
**Reason** | Pointer to **NullableString** | Why the candidate is not admissible: limits, retired, max_cost, unpriced or budget. | [optional] 

## Methods

### NewEstimateCandidate

`func NewEstimateCandidate(model string, ) *EstimateCandidate`

NewEstimateCandidate instantiates a new EstimateCandidate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEstimateCandidateWithDefaults

`func NewEstimateCandidateWithDefaults() *EstimateCandidate`

NewEstimateCandidateWithDefaults instantiates a new EstimateCandidate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdmissible

`func (o *EstimateCandidate) GetAdmissible() bool`

GetAdmissible returns the Admissible field if non-nil, zero value otherwise.

### GetAdmissibleOk

`func (o *EstimateCandidate) GetAdmissibleOk() (*bool, bool)`

GetAdmissibleOk returns a tuple with the Admissible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdmissible

`func (o *EstimateCandidate) SetAdmissible(v bool)`

SetAdmissible sets Admissible field to given value.

### HasAdmissible

`func (o *EstimateCandidate) HasAdmissible() bool`

HasAdmissible returns a boolean if a field has been set.

### GetEstimatedCost

`func (o *EstimateCandidate) GetEstimatedCost() float32`

GetEstimatedCost returns the EstimatedCost field if non-nil, zero value otherwise.

### GetEstimatedCostOk

`func (o *EstimateCandidate) GetEstimatedCostOk() (*float32, bool)`

GetEstimatedCostOk returns a tuple with the EstimatedCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedCost

`func (o *EstimateCandidate) SetEstimatedCost(v float32)`

SetEstimatedCost sets EstimatedCost field to given value.

### HasEstimatedCost

`func (o *EstimateCandidate) HasEstimatedCost() bool`

HasEstimatedCost returns a boolean if a field has been set.

### SetEstimatedCostNil

`func (o *EstimateCandidate) SetEstimatedCostNil(b bool)`

 SetEstimatedCostNil sets the value for EstimatedCost to be an explicit nil

### UnsetEstimatedCost
`func (o *EstimateCandidate) UnsetEstimatedCost()`

UnsetEstimatedCost ensures that no value is present for EstimatedCost, not even an explicit nil
### GetLifecycle

`func (o *EstimateCandidate) GetLifecycle() string`

GetLifecycle returns the Lifecycle field if non-nil, zero value otherwise.

### GetLifecycleOk

`func (o *EstimateCandidate) GetLifecycleOk() (*string, bool)`

GetLifecycleOk returns a tuple with the Lifecycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLifecycle

`func (o *EstimateCandidate) SetLifecycle(v string)`

SetLifecycle sets Lifecycle field to given value.

### HasLifecycle

`func (o *EstimateCandidate) HasLifecycle() bool`

HasLifecycle returns a boolean if a field has been set.

### GetModel

`func (o *EstimateCandidate) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *EstimateCandidate) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *EstimateCandidate) SetModel(v string)`

SetModel sets Model field to given value.


### GetReason

`func (o *EstimateCandidate) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *EstimateCandidate) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *EstimateCandidate) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *EstimateCandidate) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *EstimateCandidate) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *EstimateCandidate) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


