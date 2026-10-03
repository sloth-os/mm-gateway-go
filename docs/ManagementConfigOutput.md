# ManagementConfigOutput

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

### NewManagementConfigOutput

`func NewManagementConfigOutput() *ManagementConfigOutput`

NewManagementConfigOutput instantiates a new ManagementConfigOutput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementConfigOutputWithDefaults

`func NewManagementConfigOutputWithDefaults() *ManagementConfigOutput`

NewManagementConfigOutputWithDefaults instantiates a new ManagementConfigOutput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackends

`func (o *ManagementConfigOutput) GetBackends() []ManagedBackend`

GetBackends returns the Backends field if non-nil, zero value otherwise.

### GetBackendsOk

`func (o *ManagementConfigOutput) GetBackendsOk() (*[]ManagedBackend, bool)`

GetBackendsOk returns a tuple with the Backends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackends

`func (o *ManagementConfigOutput) SetBackends(v []ManagedBackend)`

SetBackends sets Backends field to given value.

### HasBackends

`func (o *ManagementConfigOutput) HasBackends() bool`

HasBackends returns a boolean if a field has been set.

### GetBudgetAllowUnpriced

`func (o *ManagementConfigOutput) GetBudgetAllowUnpriced() bool`

GetBudgetAllowUnpriced returns the BudgetAllowUnpriced field if non-nil, zero value otherwise.

### GetBudgetAllowUnpricedOk

`func (o *ManagementConfigOutput) GetBudgetAllowUnpricedOk() (*bool, bool)`

GetBudgetAllowUnpricedOk returns a tuple with the BudgetAllowUnpriced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudgetAllowUnpriced

`func (o *ManagementConfigOutput) SetBudgetAllowUnpriced(v bool)`

SetBudgetAllowUnpriced sets BudgetAllowUnpriced field to given value.

### HasBudgetAllowUnpriced

`func (o *ManagementConfigOutput) HasBudgetAllowUnpriced() bool`

HasBudgetAllowUnpriced returns a boolean if a field has been set.

### GetCatalogModels

`func (o *ManagementConfigOutput) GetCatalogModels() map[string]interface{}`

GetCatalogModels returns the CatalogModels field if non-nil, zero value otherwise.

### GetCatalogModelsOk

`func (o *ManagementConfigOutput) GetCatalogModelsOk() (*map[string]interface{}, bool)`

GetCatalogModelsOk returns a tuple with the CatalogModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogModels

`func (o *ManagementConfigOutput) SetCatalogModels(v map[string]interface{})`

SetCatalogModels sets CatalogModels field to given value.

### HasCatalogModels

`func (o *ManagementConfigOutput) HasCatalogModels() bool`

HasCatalogModels returns a boolean if a field has been set.

### GetKeys

`func (o *ManagementConfigOutput) GetKeys() []ManagedKey`

GetKeys returns the Keys field if non-nil, zero value otherwise.

### GetKeysOk

`func (o *ManagementConfigOutput) GetKeysOk() (*[]ManagedKey, bool)`

GetKeysOk returns a tuple with the Keys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeys

`func (o *ManagementConfigOutput) SetKeys(v []ManagedKey)`

SetKeys sets Keys field to given value.

### HasKeys

`func (o *ManagementConfigOutput) HasKeys() bool`

HasKeys returns a boolean if a field has been set.

### GetOutboundProxy

`func (o *ManagementConfigOutput) GetOutboundProxy() string`

GetOutboundProxy returns the OutboundProxy field if non-nil, zero value otherwise.

### GetOutboundProxyOk

`func (o *ManagementConfigOutput) GetOutboundProxyOk() (*string, bool)`

GetOutboundProxyOk returns a tuple with the OutboundProxy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundProxy

`func (o *ManagementConfigOutput) SetOutboundProxy(v string)`

SetOutboundProxy sets OutboundProxy field to given value.

### HasOutboundProxy

`func (o *ManagementConfigOutput) HasOutboundProxy() bool`

HasOutboundProxy returns a boolean if a field has been set.

### SetOutboundProxyNil

`func (o *ManagementConfigOutput) SetOutboundProxyNil(b bool)`

 SetOutboundProxyNil sets the value for OutboundProxy to be an explicit nil

### UnsetOutboundProxy
`func (o *ManagementConfigOutput) UnsetOutboundProxy()`

UnsetOutboundProxy ensures that no value is present for OutboundProxy, not even an explicit nil
### GetProxies

`func (o *ManagementConfigOutput) GetProxies() []ManagedProxy`

GetProxies returns the Proxies field if non-nil, zero value otherwise.

### GetProxiesOk

`func (o *ManagementConfigOutput) GetProxiesOk() (*[]ManagedProxy, bool)`

GetProxiesOk returns a tuple with the Proxies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProxies

`func (o *ManagementConfigOutput) SetProxies(v []ManagedProxy)`

SetProxies sets Proxies field to given value.

### HasProxies

`func (o *ManagementConfigOutput) HasProxies() bool`

HasProxies returns a boolean if a field has been set.

### GetRoutingDefaultOptimize

`func (o *ManagementConfigOutput) GetRoutingDefaultOptimize() string`

GetRoutingDefaultOptimize returns the RoutingDefaultOptimize field if non-nil, zero value otherwise.

### GetRoutingDefaultOptimizeOk

`func (o *ManagementConfigOutput) GetRoutingDefaultOptimizeOk() (*string, bool)`

GetRoutingDefaultOptimizeOk returns a tuple with the RoutingDefaultOptimize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingDefaultOptimize

`func (o *ManagementConfigOutput) SetRoutingDefaultOptimize(v string)`

SetRoutingDefaultOptimize sets RoutingDefaultOptimize field to given value.

### HasRoutingDefaultOptimize

`func (o *ManagementConfigOutput) HasRoutingDefaultOptimize() bool`

HasRoutingDefaultOptimize returns a boolean if a field has been set.

### GetRoutingProfiles

`func (o *ManagementConfigOutput) GetRoutingProfiles() map[string]ManagedRoutingProfile`

GetRoutingProfiles returns the RoutingProfiles field if non-nil, zero value otherwise.

### GetRoutingProfilesOk

`func (o *ManagementConfigOutput) GetRoutingProfilesOk() (*map[string]ManagedRoutingProfile, bool)`

GetRoutingProfilesOk returns a tuple with the RoutingProfiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProfiles

`func (o *ManagementConfigOutput) SetRoutingProfiles(v map[string]ManagedRoutingProfile)`

SetRoutingProfiles sets RoutingProfiles field to given value.

### HasRoutingProfiles

`func (o *ManagementConfigOutput) HasRoutingProfiles() bool`

HasRoutingProfiles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


