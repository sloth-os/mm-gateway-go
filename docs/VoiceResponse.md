# VoiceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**Error** | Pointer to [**NullableTaskError**](TaskError.md) |  | [optional] 
**Id** | **string** |  | 
**Kind** | Pointer to **string** |  | [optional] [default to "cloned"]
**Links** | [**ResourceLinks**](ResourceLinks.md) |  | 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**Model** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "voice"]
**Routing** | Pointer to [**NullableRoutingInfo**](RoutingInfo.md) |  | [optional] 
**Status** | **string** |  | 
**Usage** | Pointer to [**NullableUsage**](Usage.md) |  | [optional] 
**VerificationRequired** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewVoiceResponse

`func NewVoiceResponse(id string, links ResourceLinks, name string, status string, ) *VoiceResponse`

NewVoiceResponse instantiates a new VoiceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoiceResponseWithDefaults

`func NewVoiceResponseWithDefaults() *VoiceResponse`

NewVoiceResponseWithDefaults instantiates a new VoiceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *VoiceResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *VoiceResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *VoiceResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *VoiceResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *VoiceResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *VoiceResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *VoiceResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *VoiceResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *VoiceResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *VoiceResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *VoiceResponse) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *VoiceResponse) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetError

`func (o *VoiceResponse) GetError() TaskError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *VoiceResponse) GetErrorOk() (*TaskError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *VoiceResponse) SetError(v TaskError)`

SetError sets Error field to given value.

### HasError

`func (o *VoiceResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *VoiceResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *VoiceResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetId

`func (o *VoiceResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *VoiceResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *VoiceResponse) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *VoiceResponse) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *VoiceResponse) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *VoiceResponse) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *VoiceResponse) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetLinks

`func (o *VoiceResponse) GetLinks() ResourceLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *VoiceResponse) GetLinksOk() (*ResourceLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *VoiceResponse) SetLinks(v ResourceLinks)`

SetLinks sets Links field to given value.


### GetMetadata

`func (o *VoiceResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *VoiceResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *VoiceResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *VoiceResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetModel

`func (o *VoiceResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *VoiceResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *VoiceResponse) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *VoiceResponse) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *VoiceResponse) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *VoiceResponse) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetName

`func (o *VoiceResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VoiceResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VoiceResponse) SetName(v string)`

SetName sets Name field to given value.


### GetObject

`func (o *VoiceResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *VoiceResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *VoiceResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *VoiceResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetRouting

`func (o *VoiceResponse) GetRouting() RoutingInfo`

GetRouting returns the Routing field if non-nil, zero value otherwise.

### GetRoutingOk

`func (o *VoiceResponse) GetRoutingOk() (*RoutingInfo, bool)`

GetRoutingOk returns a tuple with the Routing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouting

`func (o *VoiceResponse) SetRouting(v RoutingInfo)`

SetRouting sets Routing field to given value.

### HasRouting

`func (o *VoiceResponse) HasRouting() bool`

HasRouting returns a boolean if a field has been set.

### SetRoutingNil

`func (o *VoiceResponse) SetRoutingNil(b bool)`

 SetRoutingNil sets the value for Routing to be an explicit nil

### UnsetRouting
`func (o *VoiceResponse) UnsetRouting()`

UnsetRouting ensures that no value is present for Routing, not even an explicit nil
### GetStatus

`func (o *VoiceResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *VoiceResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *VoiceResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUsage

`func (o *VoiceResponse) GetUsage() Usage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *VoiceResponse) GetUsageOk() (*Usage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *VoiceResponse) SetUsage(v Usage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *VoiceResponse) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### SetUsageNil

`func (o *VoiceResponse) SetUsageNil(b bool)`

 SetUsageNil sets the value for Usage to be an explicit nil

### UnsetUsage
`func (o *VoiceResponse) UnsetUsage()`

UnsetUsage ensures that no value is present for Usage, not even an explicit nil
### GetVerificationRequired

`func (o *VoiceResponse) GetVerificationRequired() bool`

GetVerificationRequired returns the VerificationRequired field if non-nil, zero value otherwise.

### GetVerificationRequiredOk

`func (o *VoiceResponse) GetVerificationRequiredOk() (*bool, bool)`

GetVerificationRequiredOk returns a tuple with the VerificationRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationRequired

`func (o *VoiceResponse) SetVerificationRequired(v bool)`

SetVerificationRequired sets VerificationRequired field to given value.

### HasVerificationRequired

`func (o *VoiceResponse) HasVerificationRequired() bool`

HasVerificationRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


