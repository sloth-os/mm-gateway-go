# ManagedKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowBackends** | Pointer to **[]string** |  | [optional] 
**AllowTags** | Pointer to **[]string** |  | [optional] 
**Budget** | Pointer to [**NullableManagedBudget**](ManagedBudget.md) |  | [optional] 
**DefaultAudioBackend** | Pointer to **NullableString** |  | [optional] 
**DefaultAudioTag** | Pointer to **NullableString** |  | [optional] 
**DefaultImageBackend** | Pointer to **NullableString** |  | [optional] 
**DefaultImageTag** | Pointer to **NullableString** |  | [optional] 
**DefaultMusicBackend** | Pointer to **NullableString** |  | [optional] 
**DefaultMusicTag** | Pointer to **NullableString** |  | [optional] 
**DefaultVideoBackend** | Pointer to **NullableString** |  | [optional] 
**DefaultVideoTag** | Pointer to **NullableString** |  | [optional] 
**DenyTags** | Pointer to **[]string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] [default to true]
**Extra** | Pointer to **map[string]interface{}** |  | [optional] 
**Id** | **string** |  | 
**Key** | **string** |  | 

## Methods

### NewManagedKey

`func NewManagedKey(id string, key string, ) *ManagedKey`

NewManagedKey instantiates a new ManagedKey object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedKeyWithDefaults

`func NewManagedKeyWithDefaults() *ManagedKey`

NewManagedKeyWithDefaults instantiates a new ManagedKey object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowBackends

`func (o *ManagedKey) GetAllowBackends() []string`

GetAllowBackends returns the AllowBackends field if non-nil, zero value otherwise.

### GetAllowBackendsOk

`func (o *ManagedKey) GetAllowBackendsOk() (*[]string, bool)`

GetAllowBackendsOk returns a tuple with the AllowBackends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowBackends

`func (o *ManagedKey) SetAllowBackends(v []string)`

SetAllowBackends sets AllowBackends field to given value.

### HasAllowBackends

`func (o *ManagedKey) HasAllowBackends() bool`

HasAllowBackends returns a boolean if a field has been set.

### GetAllowTags

`func (o *ManagedKey) GetAllowTags() []string`

GetAllowTags returns the AllowTags field if non-nil, zero value otherwise.

### GetAllowTagsOk

`func (o *ManagedKey) GetAllowTagsOk() (*[]string, bool)`

GetAllowTagsOk returns a tuple with the AllowTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowTags

`func (o *ManagedKey) SetAllowTags(v []string)`

SetAllowTags sets AllowTags field to given value.

### HasAllowTags

`func (o *ManagedKey) HasAllowTags() bool`

HasAllowTags returns a boolean if a field has been set.

### GetBudget

`func (o *ManagedKey) GetBudget() ManagedBudget`

GetBudget returns the Budget field if non-nil, zero value otherwise.

### GetBudgetOk

`func (o *ManagedKey) GetBudgetOk() (*ManagedBudget, bool)`

GetBudgetOk returns a tuple with the Budget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudget

`func (o *ManagedKey) SetBudget(v ManagedBudget)`

SetBudget sets Budget field to given value.

### HasBudget

`func (o *ManagedKey) HasBudget() bool`

HasBudget returns a boolean if a field has been set.

### SetBudgetNil

`func (o *ManagedKey) SetBudgetNil(b bool)`

 SetBudgetNil sets the value for Budget to be an explicit nil

### UnsetBudget
`func (o *ManagedKey) UnsetBudget()`

UnsetBudget ensures that no value is present for Budget, not even an explicit nil
### GetDefaultAudioBackend

`func (o *ManagedKey) GetDefaultAudioBackend() string`

GetDefaultAudioBackend returns the DefaultAudioBackend field if non-nil, zero value otherwise.

### GetDefaultAudioBackendOk

`func (o *ManagedKey) GetDefaultAudioBackendOk() (*string, bool)`

GetDefaultAudioBackendOk returns a tuple with the DefaultAudioBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAudioBackend

`func (o *ManagedKey) SetDefaultAudioBackend(v string)`

SetDefaultAudioBackend sets DefaultAudioBackend field to given value.

### HasDefaultAudioBackend

`func (o *ManagedKey) HasDefaultAudioBackend() bool`

HasDefaultAudioBackend returns a boolean if a field has been set.

### SetDefaultAudioBackendNil

`func (o *ManagedKey) SetDefaultAudioBackendNil(b bool)`

 SetDefaultAudioBackendNil sets the value for DefaultAudioBackend to be an explicit nil

### UnsetDefaultAudioBackend
`func (o *ManagedKey) UnsetDefaultAudioBackend()`

UnsetDefaultAudioBackend ensures that no value is present for DefaultAudioBackend, not even an explicit nil
### GetDefaultAudioTag

`func (o *ManagedKey) GetDefaultAudioTag() string`

GetDefaultAudioTag returns the DefaultAudioTag field if non-nil, zero value otherwise.

### GetDefaultAudioTagOk

`func (o *ManagedKey) GetDefaultAudioTagOk() (*string, bool)`

GetDefaultAudioTagOk returns a tuple with the DefaultAudioTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAudioTag

`func (o *ManagedKey) SetDefaultAudioTag(v string)`

SetDefaultAudioTag sets DefaultAudioTag field to given value.

### HasDefaultAudioTag

`func (o *ManagedKey) HasDefaultAudioTag() bool`

HasDefaultAudioTag returns a boolean if a field has been set.

### SetDefaultAudioTagNil

`func (o *ManagedKey) SetDefaultAudioTagNil(b bool)`

 SetDefaultAudioTagNil sets the value for DefaultAudioTag to be an explicit nil

### UnsetDefaultAudioTag
`func (o *ManagedKey) UnsetDefaultAudioTag()`

UnsetDefaultAudioTag ensures that no value is present for DefaultAudioTag, not even an explicit nil
### GetDefaultImageBackend

`func (o *ManagedKey) GetDefaultImageBackend() string`

GetDefaultImageBackend returns the DefaultImageBackend field if non-nil, zero value otherwise.

### GetDefaultImageBackendOk

`func (o *ManagedKey) GetDefaultImageBackendOk() (*string, bool)`

GetDefaultImageBackendOk returns a tuple with the DefaultImageBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultImageBackend

`func (o *ManagedKey) SetDefaultImageBackend(v string)`

SetDefaultImageBackend sets DefaultImageBackend field to given value.

### HasDefaultImageBackend

`func (o *ManagedKey) HasDefaultImageBackend() bool`

HasDefaultImageBackend returns a boolean if a field has been set.

### SetDefaultImageBackendNil

`func (o *ManagedKey) SetDefaultImageBackendNil(b bool)`

 SetDefaultImageBackendNil sets the value for DefaultImageBackend to be an explicit nil

### UnsetDefaultImageBackend
`func (o *ManagedKey) UnsetDefaultImageBackend()`

UnsetDefaultImageBackend ensures that no value is present for DefaultImageBackend, not even an explicit nil
### GetDefaultImageTag

`func (o *ManagedKey) GetDefaultImageTag() string`

GetDefaultImageTag returns the DefaultImageTag field if non-nil, zero value otherwise.

### GetDefaultImageTagOk

`func (o *ManagedKey) GetDefaultImageTagOk() (*string, bool)`

GetDefaultImageTagOk returns a tuple with the DefaultImageTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultImageTag

`func (o *ManagedKey) SetDefaultImageTag(v string)`

SetDefaultImageTag sets DefaultImageTag field to given value.

### HasDefaultImageTag

`func (o *ManagedKey) HasDefaultImageTag() bool`

HasDefaultImageTag returns a boolean if a field has been set.

### SetDefaultImageTagNil

`func (o *ManagedKey) SetDefaultImageTagNil(b bool)`

 SetDefaultImageTagNil sets the value for DefaultImageTag to be an explicit nil

### UnsetDefaultImageTag
`func (o *ManagedKey) UnsetDefaultImageTag()`

UnsetDefaultImageTag ensures that no value is present for DefaultImageTag, not even an explicit nil
### GetDefaultMusicBackend

`func (o *ManagedKey) GetDefaultMusicBackend() string`

GetDefaultMusicBackend returns the DefaultMusicBackend field if non-nil, zero value otherwise.

### GetDefaultMusicBackendOk

`func (o *ManagedKey) GetDefaultMusicBackendOk() (*string, bool)`

GetDefaultMusicBackendOk returns a tuple with the DefaultMusicBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultMusicBackend

`func (o *ManagedKey) SetDefaultMusicBackend(v string)`

SetDefaultMusicBackend sets DefaultMusicBackend field to given value.

### HasDefaultMusicBackend

`func (o *ManagedKey) HasDefaultMusicBackend() bool`

HasDefaultMusicBackend returns a boolean if a field has been set.

### SetDefaultMusicBackendNil

`func (o *ManagedKey) SetDefaultMusicBackendNil(b bool)`

 SetDefaultMusicBackendNil sets the value for DefaultMusicBackend to be an explicit nil

### UnsetDefaultMusicBackend
`func (o *ManagedKey) UnsetDefaultMusicBackend()`

UnsetDefaultMusicBackend ensures that no value is present for DefaultMusicBackend, not even an explicit nil
### GetDefaultMusicTag

`func (o *ManagedKey) GetDefaultMusicTag() string`

GetDefaultMusicTag returns the DefaultMusicTag field if non-nil, zero value otherwise.

### GetDefaultMusicTagOk

`func (o *ManagedKey) GetDefaultMusicTagOk() (*string, bool)`

GetDefaultMusicTagOk returns a tuple with the DefaultMusicTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultMusicTag

`func (o *ManagedKey) SetDefaultMusicTag(v string)`

SetDefaultMusicTag sets DefaultMusicTag field to given value.

### HasDefaultMusicTag

`func (o *ManagedKey) HasDefaultMusicTag() bool`

HasDefaultMusicTag returns a boolean if a field has been set.

### SetDefaultMusicTagNil

`func (o *ManagedKey) SetDefaultMusicTagNil(b bool)`

 SetDefaultMusicTagNil sets the value for DefaultMusicTag to be an explicit nil

### UnsetDefaultMusicTag
`func (o *ManagedKey) UnsetDefaultMusicTag()`

UnsetDefaultMusicTag ensures that no value is present for DefaultMusicTag, not even an explicit nil
### GetDefaultVideoBackend

`func (o *ManagedKey) GetDefaultVideoBackend() string`

GetDefaultVideoBackend returns the DefaultVideoBackend field if non-nil, zero value otherwise.

### GetDefaultVideoBackendOk

`func (o *ManagedKey) GetDefaultVideoBackendOk() (*string, bool)`

GetDefaultVideoBackendOk returns a tuple with the DefaultVideoBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultVideoBackend

`func (o *ManagedKey) SetDefaultVideoBackend(v string)`

SetDefaultVideoBackend sets DefaultVideoBackend field to given value.

### HasDefaultVideoBackend

`func (o *ManagedKey) HasDefaultVideoBackend() bool`

HasDefaultVideoBackend returns a boolean if a field has been set.

### SetDefaultVideoBackendNil

`func (o *ManagedKey) SetDefaultVideoBackendNil(b bool)`

 SetDefaultVideoBackendNil sets the value for DefaultVideoBackend to be an explicit nil

### UnsetDefaultVideoBackend
`func (o *ManagedKey) UnsetDefaultVideoBackend()`

UnsetDefaultVideoBackend ensures that no value is present for DefaultVideoBackend, not even an explicit nil
### GetDefaultVideoTag

`func (o *ManagedKey) GetDefaultVideoTag() string`

GetDefaultVideoTag returns the DefaultVideoTag field if non-nil, zero value otherwise.

### GetDefaultVideoTagOk

`func (o *ManagedKey) GetDefaultVideoTagOk() (*string, bool)`

GetDefaultVideoTagOk returns a tuple with the DefaultVideoTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultVideoTag

`func (o *ManagedKey) SetDefaultVideoTag(v string)`

SetDefaultVideoTag sets DefaultVideoTag field to given value.

### HasDefaultVideoTag

`func (o *ManagedKey) HasDefaultVideoTag() bool`

HasDefaultVideoTag returns a boolean if a field has been set.

### SetDefaultVideoTagNil

`func (o *ManagedKey) SetDefaultVideoTagNil(b bool)`

 SetDefaultVideoTagNil sets the value for DefaultVideoTag to be an explicit nil

### UnsetDefaultVideoTag
`func (o *ManagedKey) UnsetDefaultVideoTag()`

UnsetDefaultVideoTag ensures that no value is present for DefaultVideoTag, not even an explicit nil
### GetDenyTags

`func (o *ManagedKey) GetDenyTags() []string`

GetDenyTags returns the DenyTags field if non-nil, zero value otherwise.

### GetDenyTagsOk

`func (o *ManagedKey) GetDenyTagsOk() (*[]string, bool)`

GetDenyTagsOk returns a tuple with the DenyTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenyTags

`func (o *ManagedKey) SetDenyTags(v []string)`

SetDenyTags sets DenyTags field to given value.

### HasDenyTags

`func (o *ManagedKey) HasDenyTags() bool`

HasDenyTags returns a boolean if a field has been set.

### GetEnabled

`func (o *ManagedKey) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManagedKey) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManagedKey) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManagedKey) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetExtra

`func (o *ManagedKey) GetExtra() map[string]interface{}`

GetExtra returns the Extra field if non-nil, zero value otherwise.

### GetExtraOk

`func (o *ManagedKey) GetExtraOk() (*map[string]interface{}, bool)`

GetExtraOk returns a tuple with the Extra field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtra

`func (o *ManagedKey) SetExtra(v map[string]interface{})`

SetExtra sets Extra field to given value.

### HasExtra

`func (o *ManagedKey) HasExtra() bool`

HasExtra returns a boolean if a field has been set.

### GetId

`func (o *ManagedKey) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManagedKey) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManagedKey) SetId(v string)`

SetId sets Id field to given value.


### GetKey

`func (o *ManagedKey) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ManagedKey) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ManagedKey) SetKey(v string)`

SetKey sets Key field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


