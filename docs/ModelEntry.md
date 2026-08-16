# ModelEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Modality** | **string** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "model"]

## Methods

### NewModelEntry

`func NewModelEntry(id string, modality string, ) *ModelEntry`

NewModelEntry instantiates a new ModelEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelEntryWithDefaults

`func NewModelEntryWithDefaults() *ModelEntry`

NewModelEntryWithDefaults instantiates a new ModelEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ModelEntry) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ModelEntry) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ModelEntry) SetId(v string)`

SetId sets Id field to given value.


### GetModality

`func (o *ModelEntry) GetModality() string`

GetModality returns the Modality field if non-nil, zero value otherwise.

### GetModalityOk

`func (o *ModelEntry) GetModalityOk() (*string, bool)`

GetModalityOk returns a tuple with the Modality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModality

`func (o *ModelEntry) SetModality(v string)`

SetModality sets Modality field to given value.


### GetObject

`func (o *ModelEntry) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ModelEntry) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ModelEntry) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *ModelEntry) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


