# PluginOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | Pointer to **map[string]interface{}** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] [default to true]
**FailureMode** | Pointer to **string** |  | [optional] [default to "closed"]
**Order** | Pointer to **int32** |  | [optional] [default to 0]
**TimeoutMs** | Pointer to **int32** |  | [optional] [default to 1000]

## Methods

### NewPluginOptions

`func NewPluginOptions() *PluginOptions`

NewPluginOptions instantiates a new PluginOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginOptionsWithDefaults

`func NewPluginOptionsWithDefaults() *PluginOptions`

NewPluginOptionsWithDefaults instantiates a new PluginOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *PluginOptions) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *PluginOptions) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *PluginOptions) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.

### HasConfig

`func (o *PluginOptions) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetEnabled

`func (o *PluginOptions) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *PluginOptions) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *PluginOptions) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *PluginOptions) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetFailureMode

`func (o *PluginOptions) GetFailureMode() string`

GetFailureMode returns the FailureMode field if non-nil, zero value otherwise.

### GetFailureModeOk

`func (o *PluginOptions) GetFailureModeOk() (*string, bool)`

GetFailureModeOk returns a tuple with the FailureMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureMode

`func (o *PluginOptions) SetFailureMode(v string)`

SetFailureMode sets FailureMode field to given value.

### HasFailureMode

`func (o *PluginOptions) HasFailureMode() bool`

HasFailureMode returns a boolean if a field has been set.

### GetOrder

`func (o *PluginOptions) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *PluginOptions) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *PluginOptions) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *PluginOptions) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTimeoutMs

`func (o *PluginOptions) GetTimeoutMs() int32`

GetTimeoutMs returns the TimeoutMs field if non-nil, zero value otherwise.

### GetTimeoutMsOk

`func (o *PluginOptions) GetTimeoutMsOk() (*int32, bool)`

GetTimeoutMsOk returns a tuple with the TimeoutMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeoutMs

`func (o *PluginOptions) SetTimeoutMs(v int32)`

SetTimeoutMs sets TimeoutMs field to given value.

### HasTimeoutMs

`func (o *PluginOptions) HasTimeoutMs() bool`

HasTimeoutMs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


