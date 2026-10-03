# ManagementStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BackendTypes** | **[]string** |  | 
**Backends** | [**[]BackendRuntime**](BackendRuntime.md) |  | 
**EnabledKeysCount** | **int32** |  | 
**KeysCount** | **int32** |  | 
**MetricsEnabled** | **bool** |  | 
**Persistent** | **bool** |  | 
**Proxies** | [**[]ProxyRuntime**](ProxyRuntime.md) |  | 
**Revision** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] [default to "ok"]
**TasksByStatus** | **map[string]int32** |  | 
**UptimeSeconds** | **float32** |  | 
**Version** | **string** |  | 

## Methods

### NewManagementStatus

`func NewManagementStatus(backendTypes []string, backends []BackendRuntime, enabledKeysCount int32, keysCount int32, metricsEnabled bool, persistent bool, proxies []ProxyRuntime, revision string, tasksByStatus map[string]int32, uptimeSeconds float32, version string, ) *ManagementStatus`

NewManagementStatus instantiates a new ManagementStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementStatusWithDefaults

`func NewManagementStatusWithDefaults() *ManagementStatus`

NewManagementStatusWithDefaults instantiates a new ManagementStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackendTypes

`func (o *ManagementStatus) GetBackendTypes() []string`

GetBackendTypes returns the BackendTypes field if non-nil, zero value otherwise.

### GetBackendTypesOk

`func (o *ManagementStatus) GetBackendTypesOk() (*[]string, bool)`

GetBackendTypesOk returns a tuple with the BackendTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackendTypes

`func (o *ManagementStatus) SetBackendTypes(v []string)`

SetBackendTypes sets BackendTypes field to given value.


### GetBackends

`func (o *ManagementStatus) GetBackends() []BackendRuntime`

GetBackends returns the Backends field if non-nil, zero value otherwise.

### GetBackendsOk

`func (o *ManagementStatus) GetBackendsOk() (*[]BackendRuntime, bool)`

GetBackendsOk returns a tuple with the Backends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackends

`func (o *ManagementStatus) SetBackends(v []BackendRuntime)`

SetBackends sets Backends field to given value.


### GetEnabledKeysCount

`func (o *ManagementStatus) GetEnabledKeysCount() int32`

GetEnabledKeysCount returns the EnabledKeysCount field if non-nil, zero value otherwise.

### GetEnabledKeysCountOk

`func (o *ManagementStatus) GetEnabledKeysCountOk() (*int32, bool)`

GetEnabledKeysCountOk returns a tuple with the EnabledKeysCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabledKeysCount

`func (o *ManagementStatus) SetEnabledKeysCount(v int32)`

SetEnabledKeysCount sets EnabledKeysCount field to given value.


### GetKeysCount

`func (o *ManagementStatus) GetKeysCount() int32`

GetKeysCount returns the KeysCount field if non-nil, zero value otherwise.

### GetKeysCountOk

`func (o *ManagementStatus) GetKeysCountOk() (*int32, bool)`

GetKeysCountOk returns a tuple with the KeysCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeysCount

`func (o *ManagementStatus) SetKeysCount(v int32)`

SetKeysCount sets KeysCount field to given value.


### GetMetricsEnabled

`func (o *ManagementStatus) GetMetricsEnabled() bool`

GetMetricsEnabled returns the MetricsEnabled field if non-nil, zero value otherwise.

### GetMetricsEnabledOk

`func (o *ManagementStatus) GetMetricsEnabledOk() (*bool, bool)`

GetMetricsEnabledOk returns a tuple with the MetricsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetricsEnabled

`func (o *ManagementStatus) SetMetricsEnabled(v bool)`

SetMetricsEnabled sets MetricsEnabled field to given value.


### GetPersistent

`func (o *ManagementStatus) GetPersistent() bool`

GetPersistent returns the Persistent field if non-nil, zero value otherwise.

### GetPersistentOk

`func (o *ManagementStatus) GetPersistentOk() (*bool, bool)`

GetPersistentOk returns a tuple with the Persistent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersistent

`func (o *ManagementStatus) SetPersistent(v bool)`

SetPersistent sets Persistent field to given value.


### GetProxies

`func (o *ManagementStatus) GetProxies() []ProxyRuntime`

GetProxies returns the Proxies field if non-nil, zero value otherwise.

### GetProxiesOk

`func (o *ManagementStatus) GetProxiesOk() (*[]ProxyRuntime, bool)`

GetProxiesOk returns a tuple with the Proxies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProxies

`func (o *ManagementStatus) SetProxies(v []ProxyRuntime)`

SetProxies sets Proxies field to given value.


### GetRevision

`func (o *ManagementStatus) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ManagementStatus) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ManagementStatus) SetRevision(v string)`

SetRevision sets Revision field to given value.


### GetStatus

`func (o *ManagementStatus) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManagementStatus) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManagementStatus) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ManagementStatus) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTasksByStatus

`func (o *ManagementStatus) GetTasksByStatus() map[string]int32`

GetTasksByStatus returns the TasksByStatus field if non-nil, zero value otherwise.

### GetTasksByStatusOk

`func (o *ManagementStatus) GetTasksByStatusOk() (*map[string]int32, bool)`

GetTasksByStatusOk returns a tuple with the TasksByStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasksByStatus

`func (o *ManagementStatus) SetTasksByStatus(v map[string]int32)`

SetTasksByStatus sets TasksByStatus field to given value.


### GetUptimeSeconds

`func (o *ManagementStatus) GetUptimeSeconds() float32`

GetUptimeSeconds returns the UptimeSeconds field if non-nil, zero value otherwise.

### GetUptimeSecondsOk

`func (o *ManagementStatus) GetUptimeSecondsOk() (*float32, bool)`

GetUptimeSecondsOk returns a tuple with the UptimeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUptimeSeconds

`func (o *ManagementStatus) SetUptimeSeconds(v float32)`

SetUptimeSeconds sets UptimeSeconds field to given value.


### GetVersion

`func (o *ManagementStatus) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ManagementStatus) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ManagementStatus) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


