# UsageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **string** |  | [optional] [default to "USD"]
**Key** | [**BudgetState**](BudgetState.md) |  | 
**Models** | Pointer to [**[]ModelSpend**](ModelSpend.md) |  | [optional] 
**Object** | Pointer to **string** |  | [optional] [default to "usage"]
**Period** | [**UsagePeriod**](UsagePeriod.md) |  | 
**Scopes** | Pointer to [**[]BudgetState**](BudgetState.md) |  | [optional] 

## Methods

### NewUsageResponse

`func NewUsageResponse(key BudgetState, period UsagePeriod, ) *UsageResponse`

NewUsageResponse instantiates a new UsageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUsageResponseWithDefaults

`func NewUsageResponseWithDefaults() *UsageResponse`

NewUsageResponseWithDefaults instantiates a new UsageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *UsageResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *UsageResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *UsageResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *UsageResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetKey

`func (o *UsageResponse) GetKey() BudgetState`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *UsageResponse) GetKeyOk() (*BudgetState, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *UsageResponse) SetKey(v BudgetState)`

SetKey sets Key field to given value.


### GetModels

`func (o *UsageResponse) GetModels() []ModelSpend`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *UsageResponse) GetModelsOk() (*[]ModelSpend, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *UsageResponse) SetModels(v []ModelSpend)`

SetModels sets Models field to given value.

### HasModels

`func (o *UsageResponse) HasModels() bool`

HasModels returns a boolean if a field has been set.

### GetObject

`func (o *UsageResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *UsageResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *UsageResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *UsageResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetPeriod

`func (o *UsageResponse) GetPeriod() UsagePeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *UsageResponse) GetPeriodOk() (*UsagePeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *UsageResponse) SetPeriod(v UsagePeriod)`

SetPeriod sets Period field to given value.


### GetScopes

`func (o *UsageResponse) GetScopes() []BudgetState`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *UsageResponse) GetScopesOk() (*[]BudgetState, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *UsageResponse) SetScopes(v []BudgetState)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *UsageResponse) HasScopes() bool`

HasScopes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


