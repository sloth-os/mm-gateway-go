# VoiceConsent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Granted** | **bool** | The speaker authorized creation and use of this voice. | 
**Language** | Pointer to **NullableString** |  | [optional] 
**RecordingUri** | Pointer to **NullableString** | Absolute media URI. Inline media uses a base64 data URI. | [optional] 

## Methods

### NewVoiceConsent

`func NewVoiceConsent(granted bool, ) *VoiceConsent`

NewVoiceConsent instantiates a new VoiceConsent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoiceConsentWithDefaults

`func NewVoiceConsentWithDefaults() *VoiceConsent`

NewVoiceConsentWithDefaults instantiates a new VoiceConsent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGranted

`func (o *VoiceConsent) GetGranted() bool`

GetGranted returns the Granted field if non-nil, zero value otherwise.

### GetGrantedOk

`func (o *VoiceConsent) GetGrantedOk() (*bool, bool)`

GetGrantedOk returns a tuple with the Granted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGranted

`func (o *VoiceConsent) SetGranted(v bool)`

SetGranted sets Granted field to given value.


### GetLanguage

`func (o *VoiceConsent) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *VoiceConsent) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *VoiceConsent) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *VoiceConsent) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### SetLanguageNil

`func (o *VoiceConsent) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *VoiceConsent) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetRecordingUri

`func (o *VoiceConsent) GetRecordingUri() string`

GetRecordingUri returns the RecordingUri field if non-nil, zero value otherwise.

### GetRecordingUriOk

`func (o *VoiceConsent) GetRecordingUriOk() (*string, bool)`

GetRecordingUriOk returns a tuple with the RecordingUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordingUri

`func (o *VoiceConsent) SetRecordingUri(v string)`

SetRecordingUri sets RecordingUri field to given value.

### HasRecordingUri

`func (o *VoiceConsent) HasRecordingUri() bool`

HasRecordingUri returns a boolean if a field has been set.

### SetRecordingUriNil

`func (o *VoiceConsent) SetRecordingUriNil(b bool)`

 SetRecordingUriNil sets the value for RecordingUri to be an explicit nil

### UnsetRecordingUri
`func (o *VoiceConsent) UnsetRecordingUri()`

UnsetRecordingUri ensures that no value is present for RecordingUri, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


