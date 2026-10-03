# ManagedTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Backend** | **string** |  | 
**CompletedAt** | Pointer to **NullableInt32** |  | [optional] 
**CreatedAt** | **int32** |  | 
**Id** | **string** |  | 
**Modality** | **string** |  | 
**Model** | **string** |  | 
**OwnerKeyId** | **string** |  | 
**Status** | **string** |  | 

## Methods

### NewManagedTask

`func NewManagedTask(backend string, createdAt int32, id string, modality string, model string, ownerKeyId string, status string, ) *ManagedTask`

NewManagedTask instantiates a new ManagedTask object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedTaskWithDefaults

`func NewManagedTaskWithDefaults() *ManagedTask`

NewManagedTaskWithDefaults instantiates a new ManagedTask object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackend

`func (o *ManagedTask) GetBackend() string`

GetBackend returns the Backend field if non-nil, zero value otherwise.

### GetBackendOk

`func (o *ManagedTask) GetBackendOk() (*string, bool)`

GetBackendOk returns a tuple with the Backend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackend

`func (o *ManagedTask) SetBackend(v string)`

SetBackend sets Backend field to given value.


### GetCompletedAt

`func (o *ManagedTask) GetCompletedAt() int32`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ManagedTask) GetCompletedAtOk() (*int32, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ManagedTask) SetCompletedAt(v int32)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ManagedTask) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *ManagedTask) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *ManagedTask) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *ManagedTask) GetCreatedAt() int32`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManagedTask) GetCreatedAtOk() (*int32, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManagedTask) SetCreatedAt(v int32)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *ManagedTask) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManagedTask) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManagedTask) SetId(v string)`

SetId sets Id field to given value.


### GetModality

`func (o *ManagedTask) GetModality() string`

GetModality returns the Modality field if non-nil, zero value otherwise.

### GetModalityOk

`func (o *ManagedTask) GetModalityOk() (*string, bool)`

GetModalityOk returns a tuple with the Modality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModality

`func (o *ManagedTask) SetModality(v string)`

SetModality sets Modality field to given value.


### GetModel

`func (o *ManagedTask) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ManagedTask) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ManagedTask) SetModel(v string)`

SetModel sets Model field to given value.


### GetOwnerKeyId

`func (o *ManagedTask) GetOwnerKeyId() string`

GetOwnerKeyId returns the OwnerKeyId field if non-nil, zero value otherwise.

### GetOwnerKeyIdOk

`func (o *ManagedTask) GetOwnerKeyIdOk() (*string, bool)`

GetOwnerKeyIdOk returns a tuple with the OwnerKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerKeyId

`func (o *ManagedTask) SetOwnerKeyId(v string)`

SetOwnerKeyId sets OwnerKeyId field to given value.


### GetStatus

`func (o *ManagedTask) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManagedTask) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManagedTask) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


