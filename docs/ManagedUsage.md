# ManagedUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  | 
**KeyId** | **string** |  | 
**Usage** | [**UsageResponse**](UsageResponse.md) |  | 

## Methods

### NewManagedUsage

`func NewManagedUsage(enabled bool, keyId string, usage UsageResponse, ) *ManagedUsage`

NewManagedUsage instantiates a new ManagedUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedUsageWithDefaults

`func NewManagedUsageWithDefaults() *ManagedUsage`

NewManagedUsageWithDefaults instantiates a new ManagedUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *ManagedUsage) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManagedUsage) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManagedUsage) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetKeyId

`func (o *ManagedUsage) GetKeyId() string`

GetKeyId returns the KeyId field if non-nil, zero value otherwise.

### GetKeyIdOk

`func (o *ManagedUsage) GetKeyIdOk() (*string, bool)`

GetKeyIdOk returns a tuple with the KeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyId

`func (o *ManagedUsage) SetKeyId(v string)`

SetKeyId sets KeyId field to given value.


### GetUsage

`func (o *ManagedUsage) GetUsage() UsageResponse`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *ManagedUsage) GetUsageOk() (*UsageResponse, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *ManagedUsage) SetUsage(v UsageResponse)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


