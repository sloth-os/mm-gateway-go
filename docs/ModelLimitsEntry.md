# ModelLimitsEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Limits** | Pointer to **map[string]interface{}** | Neutral input/output limits (modalities, max prompt, max output count, supported sizes/durations, role flags, ...). | [optional] 
**Modality** | **string** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "model"]

## Methods

### NewModelLimitsEntry

`func NewModelLimitsEntry(id string, modality string, ) *ModelLimitsEntry`

NewModelLimitsEntry instantiates a new ModelLimitsEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelLimitsEntryWithDefaults

`func NewModelLimitsEntryWithDefaults() *ModelLimitsEntry`

NewModelLimitsEntryWithDefaults instantiates a new ModelLimitsEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ModelLimitsEntry) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ModelLimitsEntry) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ModelLimitsEntry) SetId(v string)`

SetId sets Id field to given value.


### GetLimits

`func (o *ModelLimitsEntry) GetLimits() map[string]interface{}`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *ModelLimitsEntry) GetLimitsOk() (*map[string]interface{}, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *ModelLimitsEntry) SetLimits(v map[string]interface{})`

SetLimits sets Limits field to given value.

### HasLimits

`func (o *ModelLimitsEntry) HasLimits() bool`

HasLimits returns a boolean if a field has been set.

### GetModality

`func (o *ModelLimitsEntry) GetModality() string`

GetModality returns the Modality field if non-nil, zero value otherwise.

### GetModalityOk

`func (o *ModelLimitsEntry) GetModalityOk() (*string, bool)`

GetModalityOk returns a tuple with the Modality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModality

`func (o *ModelLimitsEntry) SetModality(v string)`

SetModality sets Modality field to given value.


### GetObject

`func (o *ModelLimitsEntry) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ModelLimitsEntry) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ModelLimitsEntry) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *ModelLimitsEntry) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


