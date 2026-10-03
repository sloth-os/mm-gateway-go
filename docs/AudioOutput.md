# AudioOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Channels** | Pointer to **NullableInt32** |  | [optional] 
**DurationSeconds** | Pointer to **NullableFloat32** |  | [optional] 
**MimeType** | Pointer to **NullableString** |  | [optional] 
**SampleRateHz** | Pointer to **NullableInt32** |  | [optional] 
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewAudioOutput

`func NewAudioOutput(uri string, ) *AudioOutput`

NewAudioOutput instantiates a new AudioOutput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudioOutputWithDefaults

`func NewAudioOutputWithDefaults() *AudioOutput`

NewAudioOutputWithDefaults instantiates a new AudioOutput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChannels

`func (o *AudioOutput) GetChannels() int32`

GetChannels returns the Channels field if non-nil, zero value otherwise.

### GetChannelsOk

`func (o *AudioOutput) GetChannelsOk() (*int32, bool)`

GetChannelsOk returns a tuple with the Channels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannels

`func (o *AudioOutput) SetChannels(v int32)`

SetChannels sets Channels field to given value.

### HasChannels

`func (o *AudioOutput) HasChannels() bool`

HasChannels returns a boolean if a field has been set.

### SetChannelsNil

`func (o *AudioOutput) SetChannelsNil(b bool)`

 SetChannelsNil sets the value for Channels to be an explicit nil

### UnsetChannels
`func (o *AudioOutput) UnsetChannels()`

UnsetChannels ensures that no value is present for Channels, not even an explicit nil
### GetDurationSeconds

`func (o *AudioOutput) GetDurationSeconds() float32`

GetDurationSeconds returns the DurationSeconds field if non-nil, zero value otherwise.

### GetDurationSecondsOk

`func (o *AudioOutput) GetDurationSecondsOk() (*float32, bool)`

GetDurationSecondsOk returns a tuple with the DurationSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationSeconds

`func (o *AudioOutput) SetDurationSeconds(v float32)`

SetDurationSeconds sets DurationSeconds field to given value.

### HasDurationSeconds

`func (o *AudioOutput) HasDurationSeconds() bool`

HasDurationSeconds returns a boolean if a field has been set.

### SetDurationSecondsNil

`func (o *AudioOutput) SetDurationSecondsNil(b bool)`

 SetDurationSecondsNil sets the value for DurationSeconds to be an explicit nil

### UnsetDurationSeconds
`func (o *AudioOutput) UnsetDurationSeconds()`

UnsetDurationSeconds ensures that no value is present for DurationSeconds, not even an explicit nil
### GetMimeType

`func (o *AudioOutput) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *AudioOutput) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *AudioOutput) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *AudioOutput) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *AudioOutput) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *AudioOutput) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetSampleRateHz

`func (o *AudioOutput) GetSampleRateHz() int32`

GetSampleRateHz returns the SampleRateHz field if non-nil, zero value otherwise.

### GetSampleRateHzOk

`func (o *AudioOutput) GetSampleRateHzOk() (*int32, bool)`

GetSampleRateHzOk returns a tuple with the SampleRateHz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleRateHz

`func (o *AudioOutput) SetSampleRateHz(v int32)`

SetSampleRateHz sets SampleRateHz field to given value.

### HasSampleRateHz

`func (o *AudioOutput) HasSampleRateHz() bool`

HasSampleRateHz returns a boolean if a field has been set.

### SetSampleRateHzNil

`func (o *AudioOutput) SetSampleRateHzNil(b bool)`

 SetSampleRateHzNil sets the value for SampleRateHz to be an explicit nil

### UnsetSampleRateHz
`func (o *AudioOutput) UnsetSampleRateHz()`

UnsetSampleRateHz ensures that no value is present for SampleRateHz, not even an explicit nil
### GetUri

`func (o *AudioOutput) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *AudioOutput) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *AudioOutput) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


