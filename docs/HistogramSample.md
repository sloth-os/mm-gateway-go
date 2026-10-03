# HistogramSample

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Labels** | **map[string]string** |  | 
**Max** | **float32** |  | 
**Mean** | **float32** |  | 
**Min** | **float32** |  | 
**Name** | **string** |  | 
**Sum** | **float32** |  | 

## Methods

### NewHistogramSample

`func NewHistogramSample(count int32, labels map[string]string, max float32, mean float32, min float32, name string, sum float32, ) *HistogramSample`

NewHistogramSample instantiates a new HistogramSample object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistogramSampleWithDefaults

`func NewHistogramSampleWithDefaults() *HistogramSample`

NewHistogramSampleWithDefaults instantiates a new HistogramSample object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *HistogramSample) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *HistogramSample) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *HistogramSample) SetCount(v int32)`

SetCount sets Count field to given value.


### GetLabels

`func (o *HistogramSample) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *HistogramSample) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *HistogramSample) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.


### GetMax

`func (o *HistogramSample) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *HistogramSample) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *HistogramSample) SetMax(v float32)`

SetMax sets Max field to given value.


### GetMean

`func (o *HistogramSample) GetMean() float32`

GetMean returns the Mean field if non-nil, zero value otherwise.

### GetMeanOk

`func (o *HistogramSample) GetMeanOk() (*float32, bool)`

GetMeanOk returns a tuple with the Mean field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMean

`func (o *HistogramSample) SetMean(v float32)`

SetMean sets Mean field to given value.


### GetMin

`func (o *HistogramSample) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *HistogramSample) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *HistogramSample) SetMin(v float32)`

SetMin sets Min field to given value.


### GetName

`func (o *HistogramSample) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *HistogramSample) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *HistogramSample) SetName(v string)`

SetName sets Name field to given value.


### GetSum

`func (o *HistogramSample) GetSum() float32`

GetSum returns the Sum field if non-nil, zero value otherwise.

### GetSumOk

`func (o *HistogramSample) GetSumOk() (*float32, bool)`

GetSumOk returns a tuple with the Sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSum

`func (o *HistogramSample) SetSum(v float32)`

SetSum sets Sum field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


