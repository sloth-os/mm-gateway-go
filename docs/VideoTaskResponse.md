# VideoTaskResponse

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
**Object** | Pointer to **string** |  | [optional] [default to "video"]
**Outputs** | Pointer to [**[]VideoOutput**](VideoOutput.md) |  | [optional] 
**Status** | **string** |  | 
**Usage** | Pointer to [**NullableUsage**](Usage.md) |  | [optional] 

## Methods

### NewVideoTaskResponse

`func NewVideoTaskResponse(createdAt time.Time, id string, links ResourceLinks, model string, status string, ) *VideoTaskResponse`

NewVideoTaskResponse instantiates a new VideoTaskResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVideoTaskResponseWithDefaults

`func NewVideoTaskResponseWithDefaults() *VideoTaskResponse`

NewVideoTaskResponseWithDefaults instantiates a new VideoTaskResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *VideoTaskResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *VideoTaskResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *VideoTaskResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *VideoTaskResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *VideoTaskResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *VideoTaskResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *VideoTaskResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *VideoTaskResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *VideoTaskResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *VideoTaskResponse) GetError() TaskError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *VideoTaskResponse) GetErrorOk() (*TaskError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *VideoTaskResponse) SetError(v TaskError)`

SetError sets Error field to given value.

### HasError

`func (o *VideoTaskResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *VideoTaskResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *VideoTaskResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetId

`func (o *VideoTaskResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *VideoTaskResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *VideoTaskResponse) SetId(v string)`

SetId sets Id field to given value.


### GetLinks

`func (o *VideoTaskResponse) GetLinks() ResourceLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *VideoTaskResponse) GetLinksOk() (*ResourceLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *VideoTaskResponse) SetLinks(v ResourceLinks)`

SetLinks sets Links field to given value.


### GetMetadata

`func (o *VideoTaskResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *VideoTaskResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *VideoTaskResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *VideoTaskResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *VideoTaskResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *VideoTaskResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *VideoTaskResponse) SetModel(v string)`

SetModel sets Model field to given value.


### GetObject

`func (o *VideoTaskResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *VideoTaskResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *VideoTaskResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *VideoTaskResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetOutputs

`func (o *VideoTaskResponse) GetOutputs() []VideoOutput`

GetOutputs returns the Outputs field if non-nil, zero value otherwise.

### GetOutputsOk

`func (o *VideoTaskResponse) GetOutputsOk() (*[]VideoOutput, bool)`

GetOutputsOk returns a tuple with the Outputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputs

`func (o *VideoTaskResponse) SetOutputs(v []VideoOutput)`

SetOutputs sets Outputs field to given value.

### HasOutputs

`func (o *VideoTaskResponse) HasOutputs() bool`

HasOutputs returns a boolean if a field has been set.

### GetStatus

`func (o *VideoTaskResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *VideoTaskResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *VideoTaskResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUsage

`func (o *VideoTaskResponse) GetUsage() Usage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *VideoTaskResponse) GetUsageOk() (*Usage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *VideoTaskResponse) SetUsage(v Usage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *VideoTaskResponse) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### SetUsageNil

`func (o *VideoTaskResponse) SetUsageNil(b bool)`

 SetUsageNil sets the value for Usage to be an explicit nil

### UnsetUsage
`func (o *VideoTaskResponse) UnsetUsage()`

UnsetUsage ensures that no value is present for Usage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


