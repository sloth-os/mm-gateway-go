# PluginStore

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]PluginEntry**](PluginEntry.md) |  | 
**Directory** | **string** |  | 
**Errors** | [**[]PluginDiscoveryError**](PluginDiscoveryError.md) |  | 
**Persistent** | **bool** |  | 
**Revision** | **string** |  | 
**Watching** | **bool** |  | 

## Methods

### NewPluginStore

`func NewPluginStore(data []PluginEntry, directory string, errors []PluginDiscoveryError, persistent bool, revision string, watching bool, ) *PluginStore`

NewPluginStore instantiates a new PluginStore object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginStoreWithDefaults

`func NewPluginStoreWithDefaults() *PluginStore`

NewPluginStoreWithDefaults instantiates a new PluginStore object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *PluginStore) GetData() []PluginEntry`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PluginStore) GetDataOk() (*[]PluginEntry, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PluginStore) SetData(v []PluginEntry)`

SetData sets Data field to given value.


### GetDirectory

`func (o *PluginStore) GetDirectory() string`

GetDirectory returns the Directory field if non-nil, zero value otherwise.

### GetDirectoryOk

`func (o *PluginStore) GetDirectoryOk() (*string, bool)`

GetDirectoryOk returns a tuple with the Directory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectory

`func (o *PluginStore) SetDirectory(v string)`

SetDirectory sets Directory field to given value.


### GetErrors

`func (o *PluginStore) GetErrors() []PluginDiscoveryError`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *PluginStore) GetErrorsOk() (*[]PluginDiscoveryError, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *PluginStore) SetErrors(v []PluginDiscoveryError)`

SetErrors sets Errors field to given value.


### GetPersistent

`func (o *PluginStore) GetPersistent() bool`

GetPersistent returns the Persistent field if non-nil, zero value otherwise.

### GetPersistentOk

`func (o *PluginStore) GetPersistentOk() (*bool, bool)`

GetPersistentOk returns a tuple with the Persistent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersistent

`func (o *PluginStore) SetPersistent(v bool)`

SetPersistent sets Persistent field to given value.


### GetRevision

`func (o *PluginStore) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *PluginStore) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *PluginStore) SetRevision(v string)`

SetRevision sets Revision field to given value.


### GetWatching

`func (o *PluginStore) GetWatching() bool`

GetWatching returns the Watching field if non-nil, zero value otherwise.

### GetWatchingOk

`func (o *PluginStore) GetWatchingOk() (*bool, bool)`

GetWatchingOk returns a tuple with the Watching field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWatching

`func (o *PluginStore) SetWatching(v bool)`

SetWatching sets Watching field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


