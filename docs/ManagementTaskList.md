# ManagementTaskList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]ManagedTask**](ManagedTask.md) |  | 
**Limit** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "list"]
**Offset** | **int32** |  | 
**Total** | **int32** |  | 

## Methods

### NewManagementTaskList

`func NewManagementTaskList(data []ManagedTask, limit int32, offset int32, total int32, ) *ManagementTaskList`

NewManagementTaskList instantiates a new ManagementTaskList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementTaskListWithDefaults

`func NewManagementTaskListWithDefaults() *ManagementTaskList`

NewManagementTaskListWithDefaults instantiates a new ManagementTaskList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ManagementTaskList) GetData() []ManagedTask`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ManagementTaskList) GetDataOk() (*[]ManagedTask, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ManagementTaskList) SetData(v []ManagedTask)`

SetData sets Data field to given value.


### GetLimit

`func (o *ManagementTaskList) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ManagementTaskList) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ManagementTaskList) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetObject

`func (o *ManagementTaskList) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ManagementTaskList) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ManagementTaskList) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *ManagementTaskList) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetOffset

`func (o *ManagementTaskList) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ManagementTaskList) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ManagementTaskList) SetOffset(v int32)`

SetOffset sets Offset field to given value.


### GetTotal

`func (o *ManagementTaskList) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ManagementTaskList) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ManagementTaskList) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


