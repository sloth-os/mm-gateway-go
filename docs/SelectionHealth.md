# SelectionHealth

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Account** | **string** |  | 
**Attempts** | **int32** |  | 
**Backend** | **string** |  | 
**CooldownRemainingS** | **float32** |  | 
**LatencyS** | **NullableFloat32** |  | 
**Modality** | **string** |  | 
**Model** | **NullableString** |  | 
**RateLimited** | **bool** |  | 
**SuccessRate** | **NullableFloat32** |  | 

## Methods

### NewSelectionHealth

`func NewSelectionHealth(account string, attempts int32, backend string, cooldownRemainingS float32, latencyS NullableFloat32, modality string, model NullableString, rateLimited bool, successRate NullableFloat32, ) *SelectionHealth`

NewSelectionHealth instantiates a new SelectionHealth object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSelectionHealthWithDefaults

`func NewSelectionHealthWithDefaults() *SelectionHealth`

NewSelectionHealthWithDefaults instantiates a new SelectionHealth object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccount

`func (o *SelectionHealth) GetAccount() string`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *SelectionHealth) GetAccountOk() (*string, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *SelectionHealth) SetAccount(v string)`

SetAccount sets Account field to given value.


### GetAttempts

`func (o *SelectionHealth) GetAttempts() int32`

GetAttempts returns the Attempts field if non-nil, zero value otherwise.

### GetAttemptsOk

`func (o *SelectionHealth) GetAttemptsOk() (*int32, bool)`

GetAttemptsOk returns a tuple with the Attempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttempts

`func (o *SelectionHealth) SetAttempts(v int32)`

SetAttempts sets Attempts field to given value.


### GetBackend

`func (o *SelectionHealth) GetBackend() string`

GetBackend returns the Backend field if non-nil, zero value otherwise.

### GetBackendOk

`func (o *SelectionHealth) GetBackendOk() (*string, bool)`

GetBackendOk returns a tuple with the Backend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackend

`func (o *SelectionHealth) SetBackend(v string)`

SetBackend sets Backend field to given value.


### GetCooldownRemainingS

`func (o *SelectionHealth) GetCooldownRemainingS() float32`

GetCooldownRemainingS returns the CooldownRemainingS field if non-nil, zero value otherwise.

### GetCooldownRemainingSOk

`func (o *SelectionHealth) GetCooldownRemainingSOk() (*float32, bool)`

GetCooldownRemainingSOk returns a tuple with the CooldownRemainingS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCooldownRemainingS

`func (o *SelectionHealth) SetCooldownRemainingS(v float32)`

SetCooldownRemainingS sets CooldownRemainingS field to given value.


### GetLatencyS

`func (o *SelectionHealth) GetLatencyS() float32`

GetLatencyS returns the LatencyS field if non-nil, zero value otherwise.

### GetLatencySOk

`func (o *SelectionHealth) GetLatencySOk() (*float32, bool)`

GetLatencySOk returns a tuple with the LatencyS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatencyS

`func (o *SelectionHealth) SetLatencyS(v float32)`

SetLatencyS sets LatencyS field to given value.


### SetLatencySNil

`func (o *SelectionHealth) SetLatencySNil(b bool)`

 SetLatencySNil sets the value for LatencyS to be an explicit nil

### UnsetLatencyS
`func (o *SelectionHealth) UnsetLatencyS()`

UnsetLatencyS ensures that no value is present for LatencyS, not even an explicit nil
### GetModality

`func (o *SelectionHealth) GetModality() string`

GetModality returns the Modality field if non-nil, zero value otherwise.

### GetModalityOk

`func (o *SelectionHealth) GetModalityOk() (*string, bool)`

GetModalityOk returns a tuple with the Modality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModality

`func (o *SelectionHealth) SetModality(v string)`

SetModality sets Modality field to given value.


### GetModel

`func (o *SelectionHealth) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *SelectionHealth) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *SelectionHealth) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *SelectionHealth) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *SelectionHealth) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetRateLimited

`func (o *SelectionHealth) GetRateLimited() bool`

GetRateLimited returns the RateLimited field if non-nil, zero value otherwise.

### GetRateLimitedOk

`func (o *SelectionHealth) GetRateLimitedOk() (*bool, bool)`

GetRateLimitedOk returns a tuple with the RateLimited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRateLimited

`func (o *SelectionHealth) SetRateLimited(v bool)`

SetRateLimited sets RateLimited field to given value.


### GetSuccessRate

`func (o *SelectionHealth) GetSuccessRate() float32`

GetSuccessRate returns the SuccessRate field if non-nil, zero value otherwise.

### GetSuccessRateOk

`func (o *SelectionHealth) GetSuccessRateOk() (*float32, bool)`

GetSuccessRateOk returns a tuple with the SuccessRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessRate

`func (o *SelectionHealth) SetSuccessRate(v float32)`

SetSuccessRate sets SuccessRate field to given value.


### SetSuccessRateNil

`func (o *SelectionHealth) SetSuccessRateNil(b bool)`

 SetSuccessRateNil sets the value for SuccessRate to be an explicit nil

### UnsetSuccessRate
`func (o *SelectionHealth) UnsetSuccessRate()`

UnsetSuccessRate ensures that no value is present for SuccessRate, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


