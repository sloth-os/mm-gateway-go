# ImageRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Input** | [**[]InputInner**](InputInner.md) | Non-empty ordered image-generation inputs. | 
**Metadata** | Pointer to **map[string]interface{}** | Client-owned metadata returned unchanged with the task. | [optional] 
**Model** | **string** | Model id returned by GET /v1/models. | 
**Parameters** | Pointer to [**ImageParameters**](ImageParameters.md) |  | [optional] 
**Routing** | Pointer to [**NullableRoutingDirective**](RoutingDirective.md) |  | [optional] 

## Methods

### NewImageRequest

`func NewImageRequest(input []InputInner, model string, ) *ImageRequest`

NewImageRequest instantiates a new ImageRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageRequestWithDefaults

`func NewImageRequestWithDefaults() *ImageRequest`

NewImageRequestWithDefaults instantiates a new ImageRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInput

`func (o *ImageRequest) GetInput() []InputInner`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *ImageRequest) GetInputOk() (*[]InputInner, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *ImageRequest) SetInput(v []InputInner)`

SetInput sets Input field to given value.


### GetMetadata

`func (o *ImageRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ImageRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ImageRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ImageRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *ImageRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ImageRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ImageRequest) SetModel(v string)`

SetModel sets Model field to given value.


### GetParameters

`func (o *ImageRequest) GetParameters() ImageParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *ImageRequest) GetParametersOk() (*ImageParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *ImageRequest) SetParameters(v ImageParameters)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *ImageRequest) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### GetRouting

`func (o *ImageRequest) GetRouting() RoutingDirective`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *ImageRequest) GetRoutingOk() (*RoutingDirective, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *ImageRequest) SetRouting(v RoutingDirective)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *ImageRequest) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### SetRoutingNil

`func (o *ImageRequest) SetRoutingNil(b bool)`

 SetRoutingNil sets the value for Routing to be an explicit nil

### UnsetRouting
`func (o *ImageRequest) UnsetRouting()`

UnsetRouting ensures that no value is present for Routing, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


