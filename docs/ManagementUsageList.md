# ManagementUsageList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]ManagedUsage**](ManagedUsage.md) |  | 
**Object** | Pointer to **string** |  | [optional] [default to "list"]

## Methods

### NewManagementUsageList

`func NewManagementUsageList(data []ManagedUsage, ) *ManagementUsageList`

NewManagementUsageList instantiates a new ManagementUsageList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementUsageListWithDefaults

`func NewManagementUsageListWithDefaults() *ManagementUsageList`

NewManagementUsageListWithDefaults instantiates a new ManagementUsageList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ManagementUsageList) GetData() []ManagedUsage`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ManagementUsageList) GetDataOk() (*[]ManagedUsage, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ManagementUsageList) SetData(v []ManagedUsage)`

SetData sets Data field to given value.


### GetObject

`func (o *ManagementUsageList) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ManagementUsageList) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ManagementUsageList) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *ManagementUsageList) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


