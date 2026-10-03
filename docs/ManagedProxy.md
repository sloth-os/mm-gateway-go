# ManagedProxy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accounts** | Pointer to [**[]ProxyAccount**](ProxyAccount.md) |  | [optional] 
**BaseUrl** | **string** |  | 
**Domain** | Pointer to **NullableString** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] [default to true]
**Headers** | Pointer to **map[string]string** |  | [optional] 
**OutboundProxy** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**Timeout** | Pointer to **float32** |  | [optional] [default to 120]

## Methods

### NewManagedProxy

`func NewManagedProxy(baseUrl string, ) *ManagedProxy`

NewManagedProxy instantiates a new ManagedProxy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedProxyWithDefaults

`func NewManagedProxyWithDefaults() *ManagedProxy`

NewManagedProxyWithDefaults instantiates a new ManagedProxy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccounts

`func (o *ManagedProxy) GetAccounts() []ProxyAccount`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *ManagedProxy) GetAccountsOk() (*[]ProxyAccount, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *ManagedProxy) SetAccounts(v []ProxyAccount)`

SetAccounts sets Accounts field to given value.

### HasAccounts

`func (o *ManagedProxy) HasAccounts() bool`

HasAccounts returns a boolean if a field has been set.

### GetBaseUrl

`func (o *ManagedProxy) GetBaseUrl() string`

GetBaseUrl returns the BaseUrl field if non-nil, zero value otherwise.

### GetBaseUrlOk

`func (o *ManagedProxy) GetBaseUrlOk() (*string, bool)`

GetBaseUrlOk returns a tuple with the BaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseUrl

`func (o *ManagedProxy) SetBaseUrl(v string)`

SetBaseUrl sets BaseUrl field to given value.


### GetDomain

`func (o *ManagedProxy) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ManagedProxy) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ManagedProxy) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *ManagedProxy) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### SetDomainNil

`func (o *ManagedProxy) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *ManagedProxy) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetEnabled

`func (o *ManagedProxy) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManagedProxy) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManagedProxy) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *ManagedProxy) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetHeaders

`func (o *ManagedProxy) GetHeaders() map[string]string`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *ManagedProxy) GetHeadersOk() (*map[string]string, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *ManagedProxy) SetHeaders(v map[string]string)`

SetHeaders sets Headers field to given value.

### HasHeaders

`func (o *ManagedProxy) HasHeaders() bool`

HasHeaders returns a boolean if a field has been set.

### GetOutboundProxy

`func (o *ManagedProxy) GetOutboundProxy() string`

GetOutboundProxy returns the OutboundProxy field if non-nil, zero value otherwise.

### GetOutboundProxyOk

`func (o *ManagedProxy) GetOutboundProxyOk() (*string, bool)`

GetOutboundProxyOk returns a tuple with the OutboundProxy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundProxy

`func (o *ManagedProxy) SetOutboundProxy(v string)`

SetOutboundProxy sets OutboundProxy field to given value.

### HasOutboundProxy

`func (o *ManagedProxy) HasOutboundProxy() bool`

HasOutboundProxy returns a boolean if a field has been set.

### SetOutboundProxyNil

`func (o *ManagedProxy) SetOutboundProxyNil(b bool)`

 SetOutboundProxyNil sets the value for OutboundProxy to be an explicit nil

### UnsetOutboundProxy
`func (o *ManagedProxy) UnsetOutboundProxy()`

UnsetOutboundProxy ensures that no value is present for OutboundProxy, not even an explicit nil
### GetTags

`func (o *ManagedProxy) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ManagedProxy) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ManagedProxy) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ManagedProxy) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetTimeout

`func (o *ManagedProxy) GetTimeout() float32`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *ManagedProxy) GetTimeoutOk() (*float32, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *ManagedProxy) SetTimeout(v float32)`

SetTimeout sets Timeout field to given value.

### HasTimeout

`func (o *ManagedProxy) HasTimeout() bool`

HasTimeout returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


