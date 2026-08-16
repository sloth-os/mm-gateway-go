# ImageTaskResponse

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
**Object** | Pointer to **string** |  | [optional] [default to "image"]
**Outputs** | Pointer to [**[]ImageOutput**](ImageOutput.md) |  | [optional] 
**Status** | **string** |  | 
**Usage** | Pointer to [**NullableUsage**](Usage.md) |  | [optional] 

## Methods

### NewImageTaskResponse

`func NewImageTaskResponse(createdAt time.Time, id string, links ResourceLinks, model string, status string, ) *ImageTaskResponse`

NewImageTaskResponse instantiates a new ImageTaskResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageTaskResponseWithDefaults

`func NewImageTaskResponseWithDefaults() *ImageTaskResponse`

NewImageTaskResponseWithDefaults instantiates a new ImageTaskResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *ImageTaskResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ImageTaskResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ImageTaskResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ImageTaskResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *ImageTaskResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *ImageTaskResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *ImageTaskResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ImageTaskResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ImageTaskResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *ImageTaskResponse) GetError() TaskError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ImageTaskResponse) GetErrorOk() (*TaskError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ImageTaskResponse) SetError(v TaskError)`

SetError sets Error field to given value.

### HasError

`func (o *ImageTaskResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ImageTaskResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ImageTaskResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetId

`func (o *ImageTaskResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ImageTaskResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ImageTaskResponse) SetId(v string)`

SetId sets Id field to given value.


### GetLinks

`func (o *ImageTaskResponse) GetLinks() ResourceLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ImageTaskResponse) GetLinksOk() (*ResourceLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ImageTaskResponse) SetLinks(v ResourceLinks)`

SetLinks sets Links field to given value.


### GetMetadata

`func (o *ImageTaskResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ImageTaskResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ImageTaskResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ImageTaskResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *ImageTaskResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ImageTaskResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ImageTaskResponse) SetModel(v string)`

SetModel sets Model field to given value.


### GetObject

`func (o *ImageTaskResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ImageTaskResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ImageTaskResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *ImageTaskResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetOutputs

`func (o *ImageTaskResponse) GetOutputs() []ImageOutput`

GetOutputs returns the Outputs field if non-nil, zero value otherwise.

### GetOutputsOk

`func (o *ImageTaskResponse) GetOutputsOk() (*[]ImageOutput, bool)`

GetOutputsOk returns a tuple with the Outputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputs

`func (o *ImageTaskResponse) SetOutputs(v []ImageOutput)`

SetOutputs sets Outputs field to given value.

### HasOutputs

`func (o *ImageTaskResponse) HasOutputs() bool`

HasOutputs returns a boolean if a field has been set.

### GetStatus

`func (o *ImageTaskResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ImageTaskResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ImageTaskResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUsage

`func (o *ImageTaskResponse) GetUsage() Usage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *ImageTaskResponse) GetUsageOk() (*Usage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *ImageTaskResponse) SetUsage(v Usage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *ImageTaskResponse) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### SetUsageNil

`func (o *ImageTaskResponse) SetUsageNil(b bool)`

 SetUsageNil sets the value for Usage to be an explicit nil

### UnsetUsage
`func (o *ImageTaskResponse) UnsetUsage()`

UnsetUsage ensures that no value is present for Usage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


