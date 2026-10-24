# ManagementConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Backends** | Pointer to [**[]ManagedBackend**](ManagedBackend.md) |  | [optional] 
**BudgetAllowUnpriced** | Pointer to **bool** |  | [optional] [default to false]
**CatalogModels** | Pointer to **map[string]interface{}** |  | [optional] 
**Keys** | Pointer to [**[]ManagedKey**](ManagedKey.md) |  | [optional] 
**OutboundProxy** | Pointer to **NullableString** |  | [optional] 
**Proxies** | Pointer to [**[]ManagedProxy**](ManagedProxy.md) |  | [optional] 
**RoutingDefaultOptimize** | Pointer to **string** |  | [optional] [default to "balanced"]
**RoutingProfiles** | Pointer to [**map[string]ManagedRoutingProfile**](ManagedRoutingProfile.md) |  | [optional] 

## Methods

### NewManagementConfig

`func NewManagementConfig() *ManagementConfig`

NewManagementConfig instantiates a new ManagementConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementConfigWithDefaults

`func NewManagementConfigWithDefaults() *ManagementConfig`

NewManagementConfigWithDefaults instantiates a new ManagementConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackends

`func (o *ManagementConfig) GetBackends() []ManagedBackend`

GetBackends returns the Backends field if non-nil, zero value otherwise.

### GetBackendsOk

`func (o *ManagementConfig) GetBackendsOk() (*[]ManagedBackend, bool)`

GetBackendsOk returns a tuple with the Backends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackends

`func (o *ManagementConfig) SetBackends(v []ManagedBackend)`

SetBackends sets Backends field to given value.

### HasBackends

`func (o *ManagementConfig) HasBackends() bool`

HasBackends returns a boolean if a field has been set.

### GetBudgetAllowUnpriced

`func (o *ManagementConfig) GetBudgetAllowUnpriced() bool`

GetBudgetAllowUnpriced returns the BudgetAllowUnpriced field if non-nil, zero value otherwise.

### GetBudgetAllowUnpricedOk

`func (o *ManagementConfig) GetBudgetAllowUnpricedOk() (*bool, bool)`

GetBudgetAllowUnpricedOk returns a tuple with the BudgetAllowUnpriced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudgetAllowUnpriced

`func (o *ManagementConfig) SetBudgetAllowUnpriced(v bool)`

SetBudgetAllowUnpriced sets BudgetAllowUnpriced field to given value.

### HasBudgetAllowUnpriced

`func (o *ManagementConfig) HasBudgetAllowUnpriced() bool`

HasBudgetAllowUnpriced returns a boolean if a field has been set.

### GetCatalogModels

`func (o *ManagementConfig) GetCatalogModels() map[string]interface{}`

GetCatalogModels returns the CatalogModels field if non-nil, zero value otherwise.

### GetCatalogModelsOk

`func (o *ManagementConfig) GetCatalogModelsOk() (*map[string]interface{}, bool)`

GetCatalogModelsOk returns a tuple with the CatalogModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogModels

`func (o *ManagementConfig) SetCatalogModels(v map[string]interface{})`

SetCatalogModels sets CatalogModels field to given value.

### HasCatalogModels

`func (o *ManagementConfig) HasCatalogModels() bool`

HasCatalogModels returns a boolean if a field has been set.

### GetKeys

`func (o *ManagementConfig) GetKeys() []ManagedKey`

GetKeys returns the Keys field if non-nil, zero value otherwise.

### GetKeysOk

`func (o *ManagementConfig) GetKeysOk() (*[]ManagedKey, bool)`

GetKeysOk returns a tuple with the Keys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeys

`func (o *ManagementConfig) SetKeys(v []ManagedKey)`

SetKeys sets Keys field to given value.

### HasKeys

`func (o *ManagementConfig) HasKeys() bool`

HasKeys returns a boolean if a field has been set.

### GetOutboundProxy

`func (o *ManagementConfig) GetOutboundProxy() string`

GetOutboundProxy returns the OutboundProxy field if non-nil, zero value otherwise.

### GetOutboundProxyOk

`func (o *ManagementConfig) GetOutboundProxyOk() (*string, bool)`

GetOutboundProxyOk returns a tuple with the OutboundProxy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundProxy

`func (o *ManagementConfig) SetOutboundProxy(v string)`

SetOutboundProxy sets OutboundProxy field to given value.

### HasOutboundProxy

`func (o *ManagementConfig) HasOutboundProxy() bool`

HasOutboundProxy returns a boolean if a field has been set.

### SetOutboundProxyNil

`func (o *ManagementConfig) SetOutboundProxyNil(b bool)`

 SetOutboundProxyNil sets the value for OutboundProxy to be an explicit nil

### UnsetOutboundProxy
`func (o *ManagementConfig) UnsetOutboundProxy()`

UnsetOutboundProxy ensures that no value is present for OutboundProxy, not even an explicit nil
### GetProxies

`func (o *ManagementConfig) GetProxies() []ManagedProxy`

GetProxies returns the Proxies field if non-nil, zero value otherwise.

### GetProxiesOk

`func (o *ManagementConfig) GetProxiesOk() (*[]ManagedProxy, bool)`

GetProxiesOk returns a tuple with the Proxies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProxies

`func (o *ManagementConfig) SetProxies(v []ManagedProxy)`

SetProxies sets Proxies field to given value.

### HasProxies

`func (o *ManagementConfig) HasProxies() bool`

HasProxies returns a boolean if a field has been set.

### GetRoutingDefaultOptimize

`func (o *ManagementConfig) GetRoutingDefaultOptimize() string`

GetRoutingDefaultOptimize returns the RoutingDefaultOptimize field if non-nil, zero value otherwise.

### GetRoutingDefaultOptimizeOk

`func (o *ManagementConfig) GetRoutingDefaultOptimizeOk() (*string, bool)`

GetRoutingDefaultOptimizeOk returns a tuple with the RoutingDefaultOptimize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingDefaultOptimize

`func (o *ManagementConfig) SetRoutingDefaultOptimize(v string)`

SetRoutingDefaultOptimize sets RoutingDefaultOptimize field to given value.

### HasRoutingDefaultOptimize

`func (o *ManagementConfig) HasRoutingDefaultOptimize() bool`

HasRoutingDefaultOptimize returns a boolean if a field has been set.

### GetRoutingProfiles

`func (o *ManagementConfig) GetRoutingProfiles() map[string]ManagedRoutingProfile`

GetRoutingProfiles returns the RoutingProfiles field if non-nil, zero value otherwise.

### GetRoutingProfilesOk

`func (o *ManagementConfig) GetRoutingProfilesOk() (*map[string]ManagedRoutingProfile, bool)`

GetRoutingProfilesOk returns a tuple with the RoutingProfiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProfiles

`func (o *ManagementConfig) SetRoutingProfiles(v map[string]ManagedRoutingProfile)`

SetRoutingProfiles sets RoutingProfiles field to given value.

### HasRoutingProfiles

`func (o *ManagementConfig) HasRoutingProfiles() bool`

HasRoutingProfiles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


