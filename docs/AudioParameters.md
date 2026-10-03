# AudioParameters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BitrateKbps** | Pointer to **NullableInt32** |  | [optional] 
**Delivery** | Pointer to **NullableString** |  | [optional] 
**FileFormat** | Pointer to **NullableString** |  | [optional] 
**Instructions** | Pointer to **NullableString** |  | [optional] 
**Language** | Pointer to **NullableString** |  | [optional] 
**SampleRateHz** | Pointer to **NullableInt32** |  | [optional] 
**Seed** | Pointer to **NullableInt32** |  | [optional] 
**Speed** | Pointer to **NullableFloat32** |  | [optional] 
**Voice** | Pointer to **string** | A gateway voice id from GET /v1/voices. | [optional] [default to "default"]

## Methods

### NewAudioParameters

`func NewAudioParameters() *AudioParameters`

NewAudioParameters instantiates a new AudioParameters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudioParametersWithDefaults

`func NewAudioParametersWithDefaults() *AudioParameters`

NewAudioParametersWithDefaults instantiates a new AudioParameters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBitrateKbps

`func (o *AudioParameters) GetBitrateKbps() int32`

GetBitrateKbps returns the BitrateKbps field if non-nil, zero value otherwise.

### GetBitrateKbpsOk

`func (o *AudioParameters) GetBitrateKbpsOk() (*int32, bool)`

GetBitrateKbpsOk returns a tuple with the BitrateKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBitrateKbps

`func (o *AudioParameters) SetBitrateKbps(v int32)`

SetBitrateKbps sets BitrateKbps field to given value.

### HasBitrateKbps

`func (o *AudioParameters) HasBitrateKbps() bool`

HasBitrateKbps returns a boolean if a field has been set.

### SetBitrateKbpsNil

`func (o *AudioParameters) SetBitrateKbpsNil(b bool)`

 SetBitrateKbpsNil sets the value for BitrateKbps to be an explicit nil

### UnsetBitrateKbps
`func (o *AudioParameters) UnsetBitrateKbps()`

UnsetBitrateKbps ensures that no value is present for BitrateKbps, not even an explicit nil
### GetDelivery

`func (o *AudioParameters) GetDelivery() string`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *AudioParameters) GetDeliveryOk() (*string, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *AudioParameters) SetDelivery(v string)`

SetDelivery sets Delivery field to given value.

### HasDelivery

`func (o *AudioParameters) HasDelivery() bool`

HasDelivery returns a boolean if a field has been set.

### SetDeliveryNil

`func (o *AudioParameters) SetDeliveryNil(b bool)`

 SetDeliveryNil sets the value for Delivery to be an explicit nil

### UnsetDelivery
`func (o *AudioParameters) UnsetDelivery()`

UnsetDelivery ensures that no value is present for Delivery, not even an explicit nil
### GetFileFormat

`func (o *AudioParameters) GetFileFormat() string`

GetFileFormat returns the FileFormat field if non-nil, zero value otherwise.

### GetFileFormatOk

`func (o *AudioParameters) GetFileFormatOk() (*string, bool)`

GetFileFormatOk returns a tuple with the FileFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileFormat

`func (o *AudioParameters) SetFileFormat(v string)`

SetFileFormat sets FileFormat field to given value.

### HasFileFormat

`func (o *AudioParameters) HasFileFormat() bool`

HasFileFormat returns a boolean if a field has been set.

### SetFileFormatNil

`func (o *AudioParameters) SetFileFormatNil(b bool)`

 SetFileFormatNil sets the value for FileFormat to be an explicit nil

### UnsetFileFormat
`func (o *AudioParameters) UnsetFileFormat()`

UnsetFileFormat ensures that no value is present for FileFormat, not even an explicit nil
### GetInstructions

`func (o *AudioParameters) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *AudioParameters) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *AudioParameters) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *AudioParameters) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### SetInstructionsNil

`func (o *AudioParameters) SetInstructionsNil(b bool)`

 SetInstructionsNil sets the value for Instructions to be an explicit nil

### UnsetInstructions
`func (o *AudioParameters) UnsetInstructions()`

UnsetInstructions ensures that no value is present for Instructions, not even an explicit nil
### GetLanguage

`func (o *AudioParameters) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *AudioParameters) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *AudioParameters) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *AudioParameters) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### SetLanguageNil

`func (o *AudioParameters) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *AudioParameters) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetSampleRateHz

`func (o *AudioParameters) GetSampleRateHz() int32`

GetSampleRateHz returns the SampleRateHz field if non-nil, zero value otherwise.

### GetSampleRateHzOk

`func (o *AudioParameters) GetSampleRateHzOk() (*int32, bool)`

GetSampleRateHzOk returns a tuple with the SampleRateHz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleRateHz

`func (o *AudioParameters) SetSampleRateHz(v int32)`

SetSampleRateHz sets SampleRateHz field to given value.

### HasSampleRateHz

`func (o *AudioParameters) HasSampleRateHz() bool`

HasSampleRateHz returns a boolean if a field has been set.

### SetSampleRateHzNil

`func (o *AudioParameters) SetSampleRateHzNil(b bool)`

 SetSampleRateHzNil sets the value for SampleRateHz to be an explicit nil

### UnsetSampleRateHz
`func (o *AudioParameters) UnsetSampleRateHz()`

UnsetSampleRateHz ensures that no value is present for SampleRateHz, not even an explicit nil
### GetSeed

`func (o *AudioParameters) GetSeed() int32`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *AudioParameters) GetSeedOk() (*int32, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *AudioParameters) SetSeed(v int32)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *AudioParameters) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### SetSeedNil

`func (o *AudioParameters) SetSeedNil(b bool)`

 SetSeedNil sets the value for Seed to be an explicit nil

### UnsetSeed
`func (o *AudioParameters) UnsetSeed()`

UnsetSeed ensures that no value is present for Seed, not even an explicit nil
### GetSpeed

`func (o *AudioParameters) GetSpeed() float32`

GetSpeed returns the Speed field if non-nil, zero value otherwise.

### GetSpeedOk

`func (o *AudioParameters) GetSpeedOk() (*float32, bool)`

GetSpeedOk returns a tuple with the Speed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpeed

`func (o *AudioParameters) SetSpeed(v float32)`

SetSpeed sets Speed field to given value.

### HasSpeed

`func (o *AudioParameters) HasSpeed() bool`

HasSpeed returns a boolean if a field has been set.

### SetSpeedNil

`func (o *AudioParameters) SetSpeedNil(b bool)`

 SetSpeedNil sets the value for Speed to be an explicit nil

### UnsetSpeed
`func (o *AudioParameters) UnsetSpeed()`

UnsetSpeed ensures that no value is present for Speed, not even an explicit nil
### GetVoice

`func (o *AudioParameters) GetVoice() string`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *AudioParameters) GetVoiceOk() (*string, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *AudioParameters) SetVoice(v string)`

SetVoice sets Voice field to given value.

### HasVoice

`func (o *AudioParameters) HasVoice() bool`

HasVoice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


