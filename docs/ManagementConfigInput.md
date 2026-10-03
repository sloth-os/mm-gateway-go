# ManagementConfigInput

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

### NewManagementConfigInput

`func NewManagementConfigInput() *ManagementConfigInput`

NewManagementConfigInput instantiates a new ManagementConfigInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementConfigInputWithDefaults

`func NewManagementConfigInputWithDefaults() *ManagementConfigInput`

NewManagementConfigInputWithDefaults instantiates a new ManagementConfigInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackends

`func (o *ManagementConfigInput) GetBackends() []ManagedBackend`

GetBackends returns the Backends field if non-nil, zero value otherwise.

### GetBackendsOk

`func (o *ManagementConfigInput) GetBackendsOk() (*[]ManagedBackend, bool)`

GetBackendsOk returns a tuple with the Backends field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackends

`func (o *ManagementConfigInput) SetBackends(v []ManagedBackend)`

SetBackends sets Backends field to given value.

### HasBackends

`func (o *ManagementConfigInput) HasBackends() bool`

HasBackends returns a boolean if a field has been set.

### GetBudgetAllowUnpriced

`func (o *ManagementConfigInput) GetBudgetAllowUnpriced() bool`

GetBudgetAllowUnpriced returns the BudgetAllowUnpriced field if non-nil, zero value otherwise.

### GetBudgetAllowUnpricedOk

`func (o *ManagementConfigInput) GetBudgetAllowUnpricedOk() (*bool, bool)`

GetBudgetAllowUnpricedOk returns a tuple with the BudgetAllowUnpriced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudgetAllowUnpriced

`func (o *ManagementConfigInput) SetBudgetAllowUnpriced(v bool)`

SetBudgetAllowUnpriced sets BudgetAllowUnpriced field to given value.

### HasBudgetAllowUnpriced

`func (o *ManagementConfigInput) HasBudgetAllowUnpriced() bool`

HasBudgetAllowUnpriced returns a boolean if a field has been set.

### GetCatalogModels

`func (o *ManagementConfigInput) GetCatalogModels() map[string]interface{}`

GetCatalogModels returns the CatalogModels field if non-nil, zero value otherwise.

### GetCatalogModelsOk

`func (o *ManagementConfigInput) GetCatalogModelsOk() (*map[string]interface{}, bool)`

GetCatalogModelsOk returns a tuple with the CatalogModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogModels

`func (o *ManagementConfigInput) SetCatalogModels(v map[string]interface{})`

SetCatalogModels sets CatalogModels field to given value.

### HasCatalogModels

`func (o *ManagementConfigInput) HasCatalogModels() bool`

HasCatalogModels returns a boolean if a field has been set.

### GetKeys

`func (o *ManagementConfigInput) GetKeys() []ManagedKey`

GetKeys returns the Keys field if non-nil, zero value otherwise.

### GetKeysOk

`func (o *ManagementConfigInput) GetKeysOk() (*[]ManagedKey, bool)`

GetKeysOk returns a tuple with the Keys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeys

`func (o *ManagementConfigInput) SetKeys(v []ManagedKey)`

SetKeys sets Keys field to given value.

### HasKeys

`func (o *ManagementConfigInput) HasKeys() bool`

HasKeys returns a boolean if a field has been set.

### GetOutboundProxy

`func (o *ManagementConfigInput) GetOutboundProxy() string`

GetOutboundProxy returns the OutboundProxy field if non-nil, zero value otherwise.

### GetOutboundProxyOk

`func (o *ManagementConfigInput) GetOutboundProxyOk() (*string, bool)`

GetOutboundProxyOk returns a tuple with the OutboundProxy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundProxy

`func (o *ManagementConfigInput) SetOutboundProxy(v string)`

SetOutboundProxy sets OutboundProxy field to given value.

### HasOutboundProxy

`func (o *ManagementConfigInput) HasOutboundProxy() bool`

HasOutboundProxy returns a boolean if a field has been set.

### SetOutboundProxyNil

`func (o *ManagementConfigInput) SetOutboundProxyNil(b bool)`

 SetOutboundProxyNil sets the value for OutboundProxy to be an explicit nil

### UnsetOutboundProxy
`func (o *ManagementConfigInput) UnsetOutboundProxy()`

UnsetOutboundProxy ensures that no value is present for OutboundProxy, not even an explicit nil
### GetProxies

`func (o *ManagementConfigInput) GetProxies() []ManagedProxy`

GetProxies returns the Proxies field if non-nil, zero value otherwise.

### GetProxiesOk

`func (o *ManagementConfigInput) GetProxiesOk() (*[]ManagedProxy, bool)`

GetProxiesOk returns a tuple with the Proxies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProxies

`func (o *ManagementConfigInput) SetProxies(v []ManagedProxy)`

SetProxies sets Proxies field to given value.

### HasProxies

`func (o *ManagementConfigInput) HasProxies() bool`

HasProxies returns a boolean if a field has been set.

### GetRoutingDefaultOptimize

`func (o *ManagementConfigInput) GetRoutingDefaultOptimize() string`

GetRoutingDefaultOptimize returns the RoutingDefaultOptimize field if non-nil, zero value otherwise.

### GetRoutingDefaultOptimizeOk

`func (o *ManagementConfigInput) GetRoutingDefaultOptimizeOk() (*string, bool)`

GetRoutingDefaultOptimizeOk returns a tuple with the RoutingDefaultOptimize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingDefaultOptimize

`func (o *ManagementConfigInput) SetRoutingDefaultOptimize(v string)`

SetRoutingDefaultOptimize sets RoutingDefaultOptimize field to given value.

### HasRoutingDefaultOptimize

`func (o *ManagementConfigInput) HasRoutingDefaultOptimize() bool`

HasRoutingDefaultOptimize returns a boolean if a field has been set.

### GetRoutingProfiles

`func (o *ManagementConfigInput) GetRoutingProfiles() map[string]ManagedRoutingProfile`

GetRoutingProfiles returns the RoutingProfiles field if non-nil, zero value otherwise.

### GetRoutingProfilesOk

`func (o *ManagementConfigInput) GetRoutingProfilesOk() (*map[string]ManagedRoutingProfile, bool)`

GetRoutingProfilesOk returns a tuple with the RoutingProfiles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProfiles

`func (o *ManagementConfigInput) SetRoutingProfiles(v map[string]ManagedRoutingProfile)`

SetRoutingProfiles sets RoutingProfiles field to given value.

### HasRoutingProfiles

`func (o *ManagementConfigInput) HasRoutingProfiles() bool`

HasRoutingProfiles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


