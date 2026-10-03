# ManagementMetrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CollectedAt** | **string** |  | 
**Counters** | [**[]CounterSample**](CounterSample.md) |  | 
**Enabled** | **bool** |  | 
**Histograms** | [**[]HistogramSample**](HistogramSample.md) |  | 
**Selection** | [**[]SelectionHealth**](SelectionHealth.md) |  | 

## Methods

### NewManagementMetrics

`func NewManagementMetrics(collectedAt string, counters []CounterSample, enabled bool, histograms []HistogramSample, selection []SelectionHealth, ) *ManagementMetrics`

NewManagementMetrics instantiates a new ManagementMetrics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementMetricsWithDefaults

`func NewManagementMetricsWithDefaults() *ManagementMetrics`

NewManagementMetricsWithDefaults instantiates a new ManagementMetrics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCollectedAt

`func (o *ManagementMetrics) GetCollectedAt() string`

GetCollectedAt returns the CollectedAt field if non-nil, zero value otherwise.

### GetCollectedAtOk

`func (o *ManagementMetrics) GetCollectedAtOk() (*string, bool)`

GetCollectedAtOk returns a tuple with the CollectedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectedAt

`func (o *ManagementMetrics) SetCollectedAt(v string)`

SetCollectedAt sets CollectedAt field to given value.


### GetCounters

`func (o *ManagementMetrics) GetCounters() []CounterSample`

GetCounters returns the Counters field if non-nil, zero value otherwise.

### GetCountersOk

`func (o *ManagementMetrics) GetCountersOk() (*[]CounterSample, bool)`

GetCountersOk returns a tuple with the Counters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounters

`func (o *ManagementMetrics) SetCounters(v []CounterSample)`

SetCounters sets Counters field to given value.


### GetEnabled

`func (o *ManagementMetrics) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ManagementMetrics) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ManagementMetrics) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetHistograms

`func (o *ManagementMetrics) GetHistograms() []HistogramSample`

GetHistograms returns the Histograms field if non-nil, zero value otherwise.

### GetHistogramsOk

`func (o *ManagementMetrics) GetHistogramsOk() (*[]HistogramSample, bool)`

GetHistogramsOk returns a tuple with the Histograms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistograms

`func (o *ManagementMetrics) SetHistograms(v []HistogramSample)`

SetHistograms sets Histograms field to given value.


### GetSelection

`func (o *ManagementMetrics) GetSelection() []SelectionHealth`

GetSelection returns the Selection field if non-nil, zero value otherwise.

### GetSelectionOk

`func (o *ManagementMetrics) GetSelectionOk() (*[]SelectionHealth, bool)`

GetSelectionOk returns a tuple with the Selection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelection

`func (o *ManagementMetrics) SetSelection(v []SelectionHealth)`

SetSelection sets Selection field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


