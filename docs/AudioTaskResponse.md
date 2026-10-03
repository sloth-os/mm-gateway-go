# AudioTaskResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**Error** | Pointer to [**NullableTaskError**](TaskError.md) |  | [optional] 
**Id** | **string** |  | 
**Links** | [**ResourceLinks**](ResourceLinks.md) |  | 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**Model** | **string** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "audio"]
**Outputs** | Pointer to [**[]AudioOutput**](AudioOutput.md) |  | [optional] 
**Routing** | Pointer to [**NullableRoutingInfo**](RoutingInfo.md) |  | [optional] 
**Status** | **string** |  | 
**Usage** | Pointer to [**NullableUsage**](Usage.md) |  | [optional] 

## Methods

### NewAudioTaskResponse

`func NewAudioTaskResponse(createdAt time.Time, id string, links ResourceLinks, model string, status string, ) *AudioTaskResponse`

NewAudioTaskResponse instantiates a new AudioTaskResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudioTaskResponseWithDefaults

`func NewAudioTaskResponseWithDefaults() *AudioTaskResponse`

NewAudioTaskResponseWithDefaults instantiates a new AudioTaskResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *AudioTaskResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AudioTaskResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AudioTaskResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *AudioTaskResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *AudioTaskResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AudioTaskResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *AudioTaskResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AudioTaskResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AudioTaskResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *AudioTaskResponse) GetError() TaskError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AudioTaskResponse) GetErrorOk() (*TaskError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AudioTaskResponse) SetError(v TaskError)`

SetError sets Error field to given value.

### HasError

`func (o *AudioTaskResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *AudioTaskResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *AudioTaskResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetId

`func (o *AudioTaskResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AudioTaskResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AudioTaskResponse) SetId(v string)`

SetId sets Id field to given value.


### GetLinks

`func (o *AudioTaskResponse) GetLinks() ResourceLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *AudioTaskResponse) GetLinksOk() (*ResourceLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *AudioTaskResponse) SetLinks(v ResourceLinks)`

SetLinks sets Links field to given value.


### GetMetadata

`func (o *AudioTaskResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AudioTaskResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AudioTaskResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AudioTaskResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *AudioTaskResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AudioTaskResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AudioTaskResponse) SetModel(v string)`

SetModel sets Model field to given value.


### GetObject

`func (o *AudioTaskResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *AudioTaskResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *AudioTaskResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *AudioTaskResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetOutputs

`func (o *AudioTaskResponse) GetOutputs() []AudioOutput`

GetOutputs returns the Outputs field if non-nil, zero value otherwise.

### GetOutputsOk

`func (o *AudioTaskResponse) GetOutputsOk() (*[]AudioOutput, bool)`

GetOutputsOk returns a tuple with the Outputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputs

`func (o *AudioTaskResponse) SetOutputs(v []AudioOutput)`

SetOutputs sets Outputs field to given value.

### HasOutputs

`func (o *AudioTaskResponse) HasOutputs() bool`

HasOutputs returns a boolean if a field has been set.

### GetRouting

`func (o *AudioTaskResponse) GetRouting() RoutingInfo`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *AudioTaskResponse) GetRoutingOk() (*RoutingInfo, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *AudioTaskResponse) SetRouting(v RoutingInfo)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *AudioTaskResponse) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### SetRoutingNil

`func (o *AudioTaskResponse) SetRoutingNil(b bool)`

 SetRoutingNil sets the value for Routing to be an explicit nil

### UnsetRouting
`func (o *AudioTaskResponse) UnsetRouting()`

UnsetRouting ensures that no value is present for Routing, not even an explicit nil
### GetStatus

`func (o *AudioTaskResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AudioTaskResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AudioTaskResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUsage

`func (o *AudioTaskResponse) GetUsage() Usage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *AudioTaskResponse) GetUsageOk() (*Usage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *AudioTaskResponse) SetUsage(v Usage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *AudioTaskResponse) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### SetUsageNil

`func (o *AudioTaskResponse) SetUsageNil(b bool)`

 SetUsageNil sets the value for Usage to be an explicit nil

### UnsetUsage
`func (o *AudioTaskResponse) UnsetUsage()`

UnsetUsage ensures that no value is present for Usage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


