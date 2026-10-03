# ProxyRuntime

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accounts** | **[]string** |  | 
**Active** | **bool** |  | 
**Domain** | **string** |  | 
**Enabled** | **bool** |  | 

## Methods

### NewProxyRuntime

`func NewProxyRuntime(accounts []string, active bool, domain string, enabled bool, ) *ProxyRuntime`

NewProxyRuntime instantiates a new ProxyRuntime object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProxyRuntimeWithDefaults

`func NewProxyRuntimeWithDefaults() *ProxyRuntime`

NewProxyRuntimeWithDefaults instantiates a new ProxyRuntime object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccounts

`func (o *ProxyRuntime) GetAccounts() []string`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *ProxyRuntime) GetAccountsOk() (*[]string, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *ProxyRuntime) SetAccounts(v []string)`

SetAccounts sets Accounts field to given value.


### GetActive

`func (o *ProxyRuntime) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ProxyRuntime) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ProxyRuntime) SetActive(v bool)`

SetActive sets Active field to given value.


### GetDomain

`func (o *ProxyRuntime) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ProxyRuntime) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ProxyRuntime) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetEnabled

`func (o *ProxyRuntime) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ProxyRuntime) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ProxyRuntime) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


