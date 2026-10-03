# AudioRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Input** | [**[]TextInput**](TextInput.md) |  | 
**Metadata** | Pointer to **map[string]interface{}** | Client-owned metadata returned unchanged with the task. | [optional] 
**Model** | Pointer to **NullableString** | Model id returned by GET /v1/models, or omit / set to &#x60;auto&#x60; to let the gateway auto-route to a backend whose limits fit the request&#39;s input (modalities, dimensions, duration, ...). | [optional] 
**Parameters** | Pointer to [**AudioParameters**](AudioParameters.md) |  | [optional] 
**Routing** | Pointer to [**NullableRoutingDirective**](RoutingDirective.md) |  | [optional] 

## Methods

### NewAudioRequest

`func NewAudioRequest(input []TextInput, ) *AudioRequest`

NewAudioRequest instantiates a new AudioRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudioRequestWithDefaults

`func NewAudioRequestWithDefaults() *AudioRequest`

NewAudioRequestWithDefaults instantiates a new AudioRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInput

`func (o *AudioRequest) GetInput() []TextInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *AudioRequest) GetInputOk() (*[]TextInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *AudioRequest) SetInput(v []TextInput)`

SetInput sets Input field to given value.


### GetMetadata

`func (o *AudioRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AudioRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AudioRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AudioRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *AudioRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AudioRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AudioRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AudioRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *AudioRequest) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *AudioRequest) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetParameters

`func (o *AudioRequest) GetParameters() AudioParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *AudioRequest) GetParametersOk() (*AudioParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *AudioRequest) SetParameters(v AudioParameters)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *AudioRequest) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### GetRouting

`func (o *AudioRequest) GetRouting() RoutingDirective`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *AudioRequest) GetRoutingOk() (*RoutingDirective, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *AudioRequest) SetRouting(v RoutingDirective)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *AudioRequest) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### SetRoutingNil

`func (o *AudioRequest) SetRoutingNil(b bool)`

 SetRoutingNil sets the value for Routing to be an explicit nil

### UnsetRouting
`func (o *AudioRequest) UnsetRouting()`

UnsetRouting ensures that no value is present for Routing, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


