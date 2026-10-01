# UsagePeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**End** | Pointer to **NullableTime** |  | [optional] 
**Kind** | **string** |  | 
**Start** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewUsagePeriod

`func NewUsagePeriod(kind string, ) *UsagePeriod`

NewUsagePeriod instantiates a new UsagePeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUsagePeriodWithDefaults

`func NewUsagePeriodWithDefaults() *UsagePeriod`

NewUsagePeriodWithDefaults instantiates a new UsagePeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnd

`func (o *UsagePeriod) GetEnd() time.Time`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *UsagePeriod) GetEndOk() (*time.Time, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *UsagePeriod) SetEnd(v time.Time)`

SetEnd sets End field to given value.

### HasEnd

`func (o *UsagePeriod) HasEnd() bool`

HasEnd returns a boolean if a field has been set.

### SetEndNil

`func (o *UsagePeriod) SetEndNil(b bool)`

 SetEndNil sets the value for End to be an explicit nil

### UnsetEnd
`func (o *UsagePeriod) UnsetEnd()`

UnsetEnd ensures that no value is present for End, not even an explicit nil
### GetKind

`func (o *UsagePeriod) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *UsagePeriod) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *UsagePeriod) SetKind(v string)`

SetKind sets Kind field to given value.


### GetStart

`func (o *UsagePeriod) GetStart() time.Time`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *UsagePeriod) GetStartOk() (*time.Time, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *UsagePeriod) SetStart(v time.Time)`

SetStart sets Start field to given value.

### HasStart

`func (o *UsagePeriod) HasStart() bool`

HasStart returns a boolean if a field has been set.

### SetStartNil

`func (o *UsagePeriod) SetStartNil(b bool)`

 SetStartNil sets the value for Start to be an explicit nil

### UnsetStart
`func (o *UsagePeriod) UnsetStart()`

UnsetStart ensures that no value is present for Start, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


