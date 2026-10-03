# BackendRuntime

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accounts** | **[]string** |  | 
**Active** | **bool** |  | 
**Configured** | **bool** |  | 
**Enabled** | **bool** |  | 
**Models** | **map[string][]string** |  | 
**Name** | **string** |  | 
**Tags** | **[]string** |  | 
**Type** | **string** |  | 

## Methods

### NewBackendRuntime

`func NewBackendRuntime(accounts []string, active bool, configured bool, enabled bool, models map[string][]string, name string, tags []string, type_ string, ) *BackendRuntime`

NewBackendRuntime instantiates a new BackendRuntime object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBackendRuntimeWithDefaults

`func NewBackendRuntimeWithDefaults() *BackendRuntime`

NewBackendRuntimeWithDefaults instantiates a new BackendRuntime object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccounts

`func (o *BackendRuntime) GetAccounts() []string`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *BackendRuntime) GetAccountsOk() (*[]string, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *BackendRuntime) SetAccounts(v []string)`

SetAccounts sets Accounts field to given value.


### GetActive

`func (o *BackendRuntime) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *BackendRuntime) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *BackendRuntime) SetActive(v bool)`

SetActive sets Active field to given value.


### GetConfigured

`func (o *BackendRuntime) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *BackendRuntime) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *BackendRuntime) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetEnabled

`func (o *BackendRuntime) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *BackendRuntime) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *BackendRuntime) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetModels

`func (o *BackendRuntime) GetModels() map[string][]string`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *BackendRuntime) GetModelsOk() (*map[string][]string, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *BackendRuntime) SetModels(v map[string][]string)`

SetModels sets Models field to given value.


### GetName

`func (o *BackendRuntime) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BackendRuntime) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BackendRuntime) SetName(v string)`

SetName sets Name field to given value.


### GetTags

`func (o *BackendRuntime) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *BackendRuntime) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *BackendRuntime) SetTags(v []string)`

SetTags sets Tags field to given value.


### GetType

`func (o *BackendRuntime) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *BackendRuntime) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *BackendRuntime) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


