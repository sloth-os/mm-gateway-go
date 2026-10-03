# VoiceCloneRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Consent** | [**VoiceConsent**](VoiceConsent.md) |  | 
**Input** | [**[]VoiceSampleInput**](VoiceSampleInput.md) |  | 
**Metadata** | Pointer to **map[string]interface{}** | Client-owned metadata returned unchanged with the task. | [optional] 
**Model** | Pointer to **NullableString** | Model id returned by GET /v1/models, or omit / set to &#x60;auto&#x60; to let the gateway auto-route to a backend whose limits fit the request&#39;s input (modalities, dimensions, duration, ...). | [optional] 
**Parameters** | [**VoiceParameters**](VoiceParameters.md) |  | 
**Routing** | Pointer to [**NullableRoutingDirective**](RoutingDirective.md) |  | [optional] 

## Methods

### NewVoiceCloneRequest

`func NewVoiceCloneRequest(consent VoiceConsent, input []VoiceSampleInput, parameters VoiceParameters, ) *VoiceCloneRequest`

NewVoiceCloneRequest instantiates a new VoiceCloneRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoiceCloneRequestWithDefaults

`func NewVoiceCloneRequestWithDefaults() *VoiceCloneRequest`

NewVoiceCloneRequestWithDefaults instantiates a new VoiceCloneRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConsent

`func (o *VoiceCloneRequest) GetConsent() VoiceConsent`

GetConsent returns the Consent field if non-nil, zero value otherwise.

### GetConsentOk

`func (o *VoiceCloneRequest) GetConsentOk() (*VoiceConsent, bool)`

GetConsentOk returns a tuple with the Consent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsent

`func (o *VoiceCloneRequest) SetConsent(v VoiceConsent)`

SetConsent sets Consent field to given value.


### GetInput

`func (o *VoiceCloneRequest) GetInput() []VoiceSampleInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *VoiceCloneRequest) GetInputOk() (*[]VoiceSampleInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *VoiceCloneRequest) SetInput(v []VoiceSampleInput)`

SetInput sets Input field to given value.


### GetMetadata

`func (o *VoiceCloneRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *VoiceCloneRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *VoiceCloneRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *VoiceCloneRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *VoiceCloneRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *VoiceCloneRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *VoiceCloneRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *VoiceCloneRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *VoiceCloneRequest) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *VoiceCloneRequest) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetParameters

`func (o *VoiceCloneRequest) GetParameters() VoiceParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *VoiceCloneRequest) GetParametersOk() (*VoiceParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *VoiceCloneRequest) SetParameters(v VoiceParameters)`

SetParameters sets Parameters field to given value.


### GetRouting

`func (o *VoiceCloneRequest) GetRouting() RoutingDirective`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *VoiceCloneRequest) GetRoutingOk() (*RoutingDirective, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *VoiceCloneRequest) SetRouting(v RoutingDirective)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *VoiceCloneRequest) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### SetRoutingNil

`func (o *VoiceCloneRequest) SetRoutingNil(b bool)`

 SetRoutingNil sets the value for Routing to be an explicit nil

### UnsetRouting
`func (o *VoiceCloneRequest) UnsetRouting()`

UnsetRouting ensures that no value is present for Routing, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


