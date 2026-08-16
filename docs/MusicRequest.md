# MusicRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Input** | [**[]InputInner1**](InputInner1.md) | Non-empty ordered music-generation inputs. | 
**Metadata** | Pointer to **map[string]interface{}** | Client-owned metadata returned unchanged with the task. | [optional] 
**Model** | **string** | Model id returned by GET /v1/models. | 
**Parameters** | Pointer to [**MusicParameters**](MusicParameters.md) |  | [optional] 
**Routing** | Pointer to [**NullableRoutingDirective**](RoutingDirective.md) |  | [optional] 

## Methods

### NewMusicRequest

`func NewMusicRequest(input []InputInner1, model string, ) *MusicRequest`

NewMusicRequest instantiates a new MusicRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMusicRequestWithDefaults

`func NewMusicRequestWithDefaults() *MusicRequest`

NewMusicRequestWithDefaults instantiates a new MusicRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInput

`func (o *MusicRequest) GetInput() []InputInner1`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *MusicRequest) GetInputOk() (*[]InputInner1, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *MusicRequest) SetInput(v []InputInner1)`

SetInput sets Input field to given value.


### GetMetadata

`func (o *MusicRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *MusicRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *MusicRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *MusicRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *MusicRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *MusicRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *MusicRequest) SetModel(v string)`

SetModel sets Model field to given value.


### GetParameters

`func (o *MusicRequest) GetParameters() MusicParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *MusicRequest) GetParametersOk() (*MusicParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *MusicRequest) SetParameters(v MusicParameters)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *MusicRequest) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### GetRouting

`func (o *MusicRequest) GetRouting() RoutingDirective`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *MusicRequest) GetRoutingOk() (*RoutingDirective, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *MusicRequest) SetRouting(v RoutingDirective)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *MusicRequest) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### SetRoutingNil

`func (o *MusicRequest) SetRoutingNil(b bool)`

 SetRoutingNil sets the value for Routing to be an explicit nil

### UnsetRouting
`func (o *MusicRequest) UnsetRouting()`

UnsetRouting ensures that no value is present for Routing, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


