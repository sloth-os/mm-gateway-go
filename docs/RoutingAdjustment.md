# RoutingAdjustment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** |  | 
**Detail** | Pointer to **NullableString** |  | [optional] 
**Parameter** | **string** |  | 

## Methods

### NewRoutingAdjustment

`func NewRoutingAdjustment(action string, parameter string, ) *RoutingAdjustment`

NewRoutingAdjustment instantiates a new RoutingAdjustment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingAdjustmentWithDefaults

`func NewRoutingAdjustmentWithDefaults() *RoutingAdjustment`

NewRoutingAdjustmentWithDefaults instantiates a new RoutingAdjustment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *RoutingAdjustment) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *RoutingAdjustment) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *RoutingAdjustment) SetAction(v string)`

SetAction sets Action field to given value.


### GetDetail

`func (o *RoutingAdjustment) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *RoutingAdjustment) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *RoutingAdjustment) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *RoutingAdjustment) HasDetail() bool`

HasDetail returns a boolean if a field has been set.

### SetDetailNil

`func (o *RoutingAdjustment) SetDetailNil(b bool)`

 SetDetailNil sets the value for Detail to be an explicit nil

### UnsetDetail
`func (o *RoutingAdjustment) UnsetDetail()`

UnsetDetail ensures that no value is present for Detail, not even an explicit nil
### GetParameter

`func (o *RoutingAdjustment) GetParameter() string`

GetParameter returns the Parameter field if non-nil, zero value otherwise.

### GetParameterOk

`func (o *RoutingAdjustment) GetParameterOk() (*string, bool)`

GetParameterOk returns a tuple with the Parameter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameter

`func (o *RoutingAdjustment) SetParameter(v string)`

SetParameter sets Parameter field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


