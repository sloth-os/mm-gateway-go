# ManagedBackend

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | Pointer to **NullableString** |  | [optional] 
**BaseUrl** | Pointer to **NullableString** |  | [optional] 
**Credentials** | Pointer to [**[]BackendCredential**](BackendCredential.md) |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] [default to true]
**Extra** | Pointer to **map[string]interface{}** |  | [optional] 
**Name** | **string** |  | 
**Tags** | Pointer to **[]string** |  | [optional] 
**Type** | **string** |  | 

## Methods

### NewManagedBackend

`func NewManagedBackend(name string, type_ string, ) *ManagedBackend`

NewManagedBackend instantiates a new ManagedBackend object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedBackendWithDefaults

`func NewManagedBackendWithDefaults() *ManagedBackend`

NewManagedBackendWithDefaults instantiates a new ManagedBackend object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKey

`func (o *ManagedBackend) GetApiKey() string`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *ManagedBackend) GetApiKeyOk() (*string, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *ManagedBackend) SetApiKey(v string)`

SetApiKey sets ApiKey field to given value.

### HasApiKey

`func (o *ManagedBackend) HasApiKey() bool`

HasApiKey returns a boolean if a field has been set.

### SetApiKeyNil

`func (o *ManagedBackend) SetApiKeyNil(b bool)`

 SetApiKeyNil sets the value for ApiKey to be an explicit nil

### UnsetApiKey
`func (o *ManagedBackend) UnsetApiKey()`

UnsetApiKey ensures that no value is present for ApiKey, not even an explicit nil
### GetBaseUrl

`func (o *ManagedBackend) GetBaseUrl() string`

GetBaseUrl returns the BaseUrl field if non-nil, zero value otherwise.

### GetBaseUrlOk

`func (o *ManagedBackend) GetBaseUrlOk() (*string, bool)`

GetBaseUrlOk returns a tuple with the BaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseUrl

`func (o *ManagedBackend) SetBaseUrl(v string)`

SetBaseUrl sets BaseUrl field to given value.

### HasBaseUrl

`func (o *ManagedBackend) HasBaseUrl() bool`

HasBaseUrl returns a boolean if a field has been set.

### SetBaseUrlNil

`func (o *ManagedBackend) SetBaseUrlNil(b bool)`

 SetBaseUrlNil sets the value for BaseUrl to be an explicit nil

### UnsetBaseUrl
`func (o *ManagedBackend) UnsetBaseUrl()`

UnsetBaseUrl ensures that no value is present for BaseUrl, not even an explicit nil
### GetCredentials

`func (o *ManagedBackend) GetCredentials() []BackendCredential`

GetCredentials returns the Credentials field if non-nil, zero value otherwise.

### GetCredentialsOk

`func (o *ManagedBackend) GetCredentialsOk() (*[]BackendCredential, bool)`

GetCredentialsOk returns a tuple with the Credentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentials

`func (o *ManagedBackend) SetCredentials(v []BackendCredential)`

SetCredentials sets Credentials field to given value.

### HasCredentials

`func (o *ManagedBackend) HasCredentials() bool`

HasCredentials returns a boolean if a field has been set.

### GetEnabled

`func (o *ManagedBackend) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManagedBackend) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManagedBackend) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManagedBackend) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetExtra

`func (o *ManagedBackend) GetExtra() map[string]interface{}`

GetExtra returns the Extra field if non-nil, zero value otherwise.

### GetExtraOk

`func (o *ManagedBackend) GetExtraOk() (*map[string]interface{}, bool)`

GetExtraOk returns a tuple with the Extra field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtra

`func (o *ManagedBackend) SetExtra(v map[string]interface{})`

SetExtra sets Extra field to given value.

### HasExtra

`func (o *ManagedBackend) HasExtra() bool`

HasExtra returns a boolean if a field has been set.

### GetName

`func (o *ManagedBackend) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ManagedBackend) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ManagedBackend) SetName(v string)`

SetName sets Name field to given value.


### GetTags

`func (o *ManagedBackend) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ManagedBackend) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ManagedBackend) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ManagedBackend) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetType

`func (o *ManagedBackend) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ManagedBackend) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ManagedBackend) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


