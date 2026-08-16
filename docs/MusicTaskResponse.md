# MusicTaskResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**Error** | Pointer to [**NullableTaskError**](TaskError.md) |  | [optional] 
**Id** | **string** |  | 
**Links** | [**ResourceLinks**](ResourceLinks.md) |  | 
**Lyrics** | Pointer to **NullableString** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**Model** | **string** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "music"]
**Outputs** | Pointer to [**[]MusicOutput**](MusicOutput.md) |  | [optional] 
**Status** | **string** |  | 
**Usage** | Pointer to [**NullableUsage**](Usage.md) |  | [optional] 

## Methods

### NewMusicTaskResponse

`func NewMusicTaskResponse(createdAt time.Time, id string, links ResourceLinks, model string, status string, ) *MusicTaskResponse`

NewMusicTaskResponse instantiates a new MusicTaskResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMusicTaskResponseWithDefaults

`func NewMusicTaskResponseWithDefaults() *MusicTaskResponse`

NewMusicTaskResponseWithDefaults instantiates a new MusicTaskResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *MusicTaskResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *MusicTaskResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *MusicTaskResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *MusicTaskResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *MusicTaskResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *MusicTaskResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *MusicTaskResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MusicTaskResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MusicTaskResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *MusicTaskResponse) GetError() TaskError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *MusicTaskResponse) GetErrorOk() (*TaskError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *MusicTaskResponse) SetError(v TaskError)`

SetError sets Error field to given value.

### HasError

`func (o *MusicTaskResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *MusicTaskResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *MusicTaskResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetId

`func (o *MusicTaskResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MusicTaskResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MusicTaskResponse) SetId(v string)`

SetId sets Id field to given value.


### GetLinks

`func (o *MusicTaskResponse) GetLinks() ResourceLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *MusicTaskResponse) GetLinksOk() (*ResourceLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *MusicTaskResponse) SetLinks(v ResourceLinks)`

SetLinks sets Links field to given value.


### GetLyrics

`func (o *MusicTaskResponse) GetLyrics() string`

GetLyrics returns the Lyrics field if non-nil, zero value otherwise.

### GetLyricsOk

`func (o *MusicTaskResponse) GetLyricsOk() (*string, bool)`

GetLyricsOk returns a tuple with the Lyrics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLyrics

`func (o *MusicTaskResponse) SetLyrics(v string)`

SetLyrics sets Lyrics field to given value.

### HasLyrics

`func (o *MusicTaskResponse) HasLyrics() bool`

HasLyrics returns a boolean if a field has been set.

### SetLyricsNil

`func (o *MusicTaskResponse) SetLyricsNil(b bool)`

 SetLyricsNil sets the value for Lyrics to be an explicit nil

### UnsetLyrics
`func (o *MusicTaskResponse) UnsetLyrics()`

UnsetLyrics ensures that no value is present for Lyrics, not even an explicit nil
### GetMetadata

`func (o *MusicTaskResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *MusicTaskResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *MusicTaskResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *MusicTaskResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *MusicTaskResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *MusicTaskResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *MusicTaskResponse) SetModel(v string)`

SetModel sets Model field to given value.


### GetObject

`func (o *MusicTaskResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *MusicTaskResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *MusicTaskResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *MusicTaskResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetOutputs

`func (o *MusicTaskResponse) GetOutputs() []MusicOutput`

GetOutputs returns the Outputs field if non-nil, zero value otherwise.

### GetOutputsOk

`func (o *MusicTaskResponse) GetOutputsOk() (*[]MusicOutput, bool)`

GetOutputsOk returns a tuple with the Outputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputs

`func (o *MusicTaskResponse) SetOutputs(v []MusicOutput)`

SetOutputs sets Outputs field to given value.

### HasOutputs

`func (o *MusicTaskResponse) HasOutputs() bool`

HasOutputs returns a boolean if a field has been set.

### GetStatus

`func (o *MusicTaskResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MusicTaskResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MusicTaskResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUsage

`func (o *MusicTaskResponse) GetUsage() Usage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *MusicTaskResponse) GetUsageOk() (*Usage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *MusicTaskResponse) SetUsage(v Usage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *MusicTaskResponse) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### SetUsageNil

`func (o *MusicTaskResponse) SetUsageNil(b bool)`

 SetUsageNil sets the value for Usage to be an explicit nil

### UnsetUsage
`func (o *MusicTaskResponse) UnsetUsage()`

UnsetUsage ensures that no value is present for Usage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


