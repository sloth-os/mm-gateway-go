# MusicParameters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BitrateKbps** | Pointer to **NullableInt32** |  | [optional] 
**Bpm** | Pointer to **NullableInt32** |  | [optional] 
**DurationSeconds** | Pointer to **NullableFloat32** |  | [optional] 
**EnhanceLyrics** | Pointer to **NullableBool** |  | [optional] 
**FileFormat** | Pointer to **NullableString** |  | [optional] 
**GuidanceScale** | Pointer to **NullableFloat32** |  | [optional] 
**InferenceSteps** | Pointer to **NullableInt32** |  | [optional] 
**Instrumental** | Pointer to **NullableBool** |  | [optional] 
**Key** | Pointer to **NullableString** |  | [optional] 
**NegativePrompt** | Pointer to **NullableString** |  | [optional] 
**Novelty** | Pointer to **NullableFloat32** |  | [optional] 
**OutputCount** | Pointer to **NullableInt32** |  | [optional] 
**Provenance** | Pointer to **NullableBool** |  | [optional] 
**ReferenceAudioStrength** | Pointer to **NullableFloat32** |  | [optional] 
**RespectSectionDurations** | Pointer to **NullableBool** |  | [optional] 
**SampleRateHz** | Pointer to **NullableInt32** |  | [optional] 
**Scale** | Pointer to **NullableString** |  | [optional] 
**Seed** | Pointer to **NullableInt32** |  | [optional] 
**Style** | Pointer to **NullableString** |  | [optional] 
**StyleStrength** | Pointer to **NullableFloat32** |  | [optional] 
**TimeSignature** | Pointer to **NullableString** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 
**VocalGender** | Pointer to **NullableString** |  | [optional] 
**VocalLanguage** | Pointer to **NullableString** |  | [optional] 
**Voice** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewMusicParameters

`func NewMusicParameters() *MusicParameters`

NewMusicParameters instantiates a new MusicParameters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMusicParametersWithDefaults

`func NewMusicParametersWithDefaults() *MusicParameters`

NewMusicParametersWithDefaults instantiates a new MusicParameters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBitrateKbps

`func (o *MusicParameters) GetBitrateKbps() int32`

GetBitrateKbps returns the BitrateKbps field if non-nil, zero value otherwise.

### GetBitrateKbpsOk

`func (o *MusicParameters) GetBitrateKbpsOk() (*int32, bool)`

GetBitrateKbpsOk returns a tuple with the BitrateKbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBitrateKbps

`func (o *MusicParameters) SetBitrateKbps(v int32)`

SetBitrateKbps sets BitrateKbps field to given value.

### HasBitrateKbps

`func (o *MusicParameters) HasBitrateKbps() bool`

HasBitrateKbps returns a boolean if a field has been set.

### SetBitrateKbpsNil

`func (o *MusicParameters) SetBitrateKbpsNil(b bool)`

 SetBitrateKbpsNil sets the value for BitrateKbps to be an explicit nil

### UnsetBitrateKbps
`func (o *MusicParameters) UnsetBitrateKbps()`

UnsetBitrateKbps ensures that no value is present for BitrateKbps, not even an explicit nil
### GetBpm

`func (o *MusicParameters) GetBpm() int32`

GetBpm returns the Bpm field if non-nil, zero value otherwise.

### GetBpmOk

`func (o *MusicParameters) GetBpmOk() (*int32, bool)`

GetBpmOk returns a tuple with the Bpm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBpm

`func (o *MusicParameters) SetBpm(v int32)`

SetBpm sets Bpm field to given value.

### HasBpm

`func (o *MusicParameters) HasBpm() bool`

HasBpm returns a boolean if a field has been set.

### SetBpmNil

`func (o *MusicParameters) SetBpmNil(b bool)`

 SetBpmNil sets the value for Bpm to be an explicit nil

### UnsetBpm
`func (o *MusicParameters) UnsetBpm()`

UnsetBpm ensures that no value is present for Bpm, not even an explicit nil
### GetDurationSeconds

`func (o *MusicParameters) GetDurationSeconds() float32`

GetDurationSeconds returns the DurationSeconds field if non-nil, zero value otherwise.

### GetDurationSecondsOk

`func (o *MusicParameters) GetDurationSecondsOk() (*float32, bool)`

GetDurationSecondsOk returns a tuple with the DurationSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationSeconds

`func (o *MusicParameters) SetDurationSeconds(v float32)`

SetDurationSeconds sets DurationSeconds field to given value.

### HasDurationSeconds

`func (o *MusicParameters) HasDurationSeconds() bool`

HasDurationSeconds returns a boolean if a field has been set.

### SetDurationSecondsNil

`func (o *MusicParameters) SetDurationSecondsNil(b bool)`

 SetDurationSecondsNil sets the value for DurationSeconds to be an explicit nil

### UnsetDurationSeconds
`func (o *MusicParameters) UnsetDurationSeconds()`

UnsetDurationSeconds ensures that no value is present for DurationSeconds, not even an explicit nil
### GetEnhanceLyrics

`func (o *MusicParameters) GetEnhanceLyrics() bool`

GetEnhanceLyrics returns the EnhanceLyrics field if non-nil, zero value otherwise.

### GetEnhanceLyricsOk

`func (o *MusicParameters) GetEnhanceLyricsOk() (*bool, bool)`

GetEnhanceLyricsOk returns a tuple with the EnhanceLyrics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnhanceLyrics

`func (o *MusicParameters) SetEnhanceLyrics(v bool)`

SetEnhanceLyrics sets EnhanceLyrics field to given value.

### HasEnhanceLyrics

`func (o *MusicParameters) HasEnhanceLyrics() bool`

HasEnhanceLyrics returns a boolean if a field has been set.

### SetEnhanceLyricsNil

`func (o *MusicParameters) SetEnhanceLyricsNil(b bool)`

 SetEnhanceLyricsNil sets the value for EnhanceLyrics to be an explicit nil

### UnsetEnhanceLyrics
`func (o *MusicParameters) UnsetEnhanceLyrics()`

UnsetEnhanceLyrics ensures that no value is present for EnhanceLyrics, not even an explicit nil
### GetFileFormat

`func (o *MusicParameters) GetFileFormat() string`

GetFileFormat returns the FileFormat field if non-nil, zero value otherwise.

### GetFileFormatOk

`func (o *MusicParameters) GetFileFormatOk() (*string, bool)`

GetFileFormatOk returns a tuple with the FileFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileFormat

`func (o *MusicParameters) SetFileFormat(v string)`

SetFileFormat sets FileFormat field to given value.

### HasFileFormat

`func (o *MusicParameters) HasFileFormat() bool`

HasFileFormat returns a boolean if a field has been set.

### SetFileFormatNil

`func (o *MusicParameters) SetFileFormatNil(b bool)`

 SetFileFormatNil sets the value for FileFormat to be an explicit nil

### UnsetFileFormat
`func (o *MusicParameters) UnsetFileFormat()`

UnsetFileFormat ensures that no value is present for FileFormat, not even an explicit nil
### GetGuidanceScale

`func (o *MusicParameters) GetGuidanceScale() float32`

GetGuidanceScale returns the GuidanceScale field if non-nil, zero value otherwise.

### GetGuidanceScaleOk

`func (o *MusicParameters) GetGuidanceScaleOk() (*float32, bool)`

GetGuidanceScaleOk returns a tuple with the GuidanceScale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidanceScale

`func (o *MusicParameters) SetGuidanceScale(v float32)`

SetGuidanceScale sets GuidanceScale field to given value.

### HasGuidanceScale

`func (o *MusicParameters) HasGuidanceScale() bool`

HasGuidanceScale returns a boolean if a field has been set.

### SetGuidanceScaleNil

`func (o *MusicParameters) SetGuidanceScaleNil(b bool)`

 SetGuidanceScaleNil sets the value for GuidanceScale to be an explicit nil

### UnsetGuidanceScale
`func (o *MusicParameters) UnsetGuidanceScale()`

UnsetGuidanceScale ensures that no value is present for GuidanceScale, not even an explicit nil
### GetInferenceSteps

`func (o *MusicParameters) GetInferenceSteps() int32`

GetInferenceSteps returns the InferenceSteps field if non-nil, zero value otherwise.

### GetInferenceStepsOk

`func (o *MusicParameters) GetInferenceStepsOk() (*int32, bool)`

GetInferenceStepsOk returns a tuple with the InferenceSteps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInferenceSteps

`func (o *MusicParameters) SetInferenceSteps(v int32)`

SetInferenceSteps sets InferenceSteps field to given value.

### HasInferenceSteps

`func (o *MusicParameters) HasInferenceSteps() bool`

HasInferenceSteps returns a boolean if a field has been set.

### SetInferenceStepsNil

`func (o *MusicParameters) SetInferenceStepsNil(b bool)`

 SetInferenceStepsNil sets the value for InferenceSteps to be an explicit nil

### UnsetInferenceSteps
`func (o *MusicParameters) UnsetInferenceSteps()`

UnsetInferenceSteps ensures that no value is present for InferenceSteps, not even an explicit nil
### GetInstrumental

`func (o *MusicParameters) GetInstrumental() bool`

GetInstrumental returns the Instrumental field if non-nil, zero value otherwise.

### GetInstrumentalOk

`func (o *MusicParameters) GetInstrumentalOk() (*bool, bool)`

GetInstrumentalOk returns a tuple with the Instrumental field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstrumental

`func (o *MusicParameters) SetInstrumental(v bool)`

SetInstrumental sets Instrumental field to given value.

### HasInstrumental

`func (o *MusicParameters) HasInstrumental() bool`

HasInstrumental returns a boolean if a field has been set.

### SetInstrumentalNil

`func (o *MusicParameters) SetInstrumentalNil(b bool)`

 SetInstrumentalNil sets the value for Instrumental to be an explicit nil

### UnsetInstrumental
`func (o *MusicParameters) UnsetInstrumental()`

UnsetInstrumental ensures that no value is present for Instrumental, not even an explicit nil
### GetKey

`func (o *MusicParameters) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *MusicParameters) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *MusicParameters) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *MusicParameters) HasKey() bool`

HasKey returns a boolean if a field has been set.

### SetKeyNil

`func (o *MusicParameters) SetKeyNil(b bool)`

 SetKeyNil sets the value for Key to be an explicit nil

### UnsetKey
`func (o *MusicParameters) UnsetKey()`

UnsetKey ensures that no value is present for Key, not even an explicit nil
### GetNegativePrompt

`func (o *MusicParameters) GetNegativePrompt() string`

GetNegativePrompt returns the NegativePrompt field if non-nil, zero value otherwise.

### GetNegativePromptOk

`func (o *MusicParameters) GetNegativePromptOk() (*string, bool)`

GetNegativePromptOk returns a tuple with the NegativePrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativePrompt

`func (o *MusicParameters) SetNegativePrompt(v string)`

SetNegativePrompt sets NegativePrompt field to given value.

### HasNegativePrompt

`func (o *MusicParameters) HasNegativePrompt() bool`

HasNegativePrompt returns a boolean if a field has been set.

### SetNegativePromptNil

`func (o *MusicParameters) SetNegativePromptNil(b bool)`

 SetNegativePromptNil sets the value for NegativePrompt to be an explicit nil

### UnsetNegativePrompt
`func (o *MusicParameters) UnsetNegativePrompt()`

UnsetNegativePrompt ensures that no value is present for NegativePrompt, not even an explicit nil
### GetNovelty

`func (o *MusicParameters) GetNovelty() float32`

GetNovelty returns the Novelty field if non-nil, zero value otherwise.

### GetNoveltyOk

`func (o *MusicParameters) GetNoveltyOk() (*float32, bool)`

GetNoveltyOk returns a tuple with the Novelty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNovelty

`func (o *MusicParameters) SetNovelty(v float32)`

SetNovelty sets Novelty field to given value.

### HasNovelty

`func (o *MusicParameters) HasNovelty() bool`

HasNovelty returns a boolean if a field has been set.

### SetNoveltyNil

`func (o *MusicParameters) SetNoveltyNil(b bool)`

 SetNoveltyNil sets the value for Novelty to be an explicit nil

### UnsetNovelty
`func (o *MusicParameters) UnsetNovelty()`

UnsetNovelty ensures that no value is present for Novelty, not even an explicit nil
### GetOutputCount

`func (o *MusicParameters) GetOutputCount() int32`

GetOutputCount returns the OutputCount field if non-nil, zero value otherwise.

### GetOutputCountOk

`func (o *MusicParameters) GetOutputCountOk() (*int32, bool)`

GetOutputCountOk returns a tuple with the OutputCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputCount

`func (o *MusicParameters) SetOutputCount(v int32)`

SetOutputCount sets OutputCount field to given value.

### HasOutputCount

`func (o *MusicParameters) HasOutputCount() bool`

HasOutputCount returns a boolean if a field has been set.

### SetOutputCountNil

`func (o *MusicParameters) SetOutputCountNil(b bool)`

 SetOutputCountNil sets the value for OutputCount to be an explicit nil

### UnsetOutputCount
`func (o *MusicParameters) UnsetOutputCount()`

UnsetOutputCount ensures that no value is present for OutputCount, not even an explicit nil
### GetProvenance

`func (o *MusicParameters) GetProvenance() bool`

GetProvenance returns the Provenance field if non-nil, zero value otherwise.

### GetProvenanceOk

`func (o *MusicParameters) GetProvenanceOk() (*bool, bool)`

GetProvenanceOk returns a tuple with the Provenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvenance

`func (o *MusicParameters) SetProvenance(v bool)`

SetProvenance sets Provenance field to given value.

### HasProvenance

`func (o *MusicParameters) HasProvenance() bool`

HasProvenance returns a boolean if a field has been set.

### SetProvenanceNil

`func (o *MusicParameters) SetProvenanceNil(b bool)`

 SetProvenanceNil sets the value for Provenance to be an explicit nil

### UnsetProvenance
`func (o *MusicParameters) UnsetProvenance()`

UnsetProvenance ensures that no value is present for Provenance, not even an explicit nil
### GetReferenceAudioStrength

`func (o *MusicParameters) GetReferenceAudioStrength() float32`

GetReferenceAudioStrength returns the ReferenceAudioStrength field if non-nil, zero value otherwise.

### GetReferenceAudioStrengthOk

`func (o *MusicParameters) GetReferenceAudioStrengthOk() (*float32, bool)`

GetReferenceAudioStrengthOk returns a tuple with the ReferenceAudioStrength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceAudioStrength

`func (o *MusicParameters) SetReferenceAudioStrength(v float32)`

SetReferenceAudioStrength sets ReferenceAudioStrength field to given value.

### HasReferenceAudioStrength

`func (o *MusicParameters) HasReferenceAudioStrength() bool`

HasReferenceAudioStrength returns a boolean if a field has been set.

### SetReferenceAudioStrengthNil

`func (o *MusicParameters) SetReferenceAudioStrengthNil(b bool)`

 SetReferenceAudioStrengthNil sets the value for ReferenceAudioStrength to be an explicit nil

### UnsetReferenceAudioStrength
`func (o *MusicParameters) UnsetReferenceAudioStrength()`

UnsetReferenceAudioStrength ensures that no value is present for ReferenceAudioStrength, not even an explicit nil
### GetRespectSectionDurations

`func (o *MusicParameters) GetRespectSectionDurations() bool`

GetRespectSectionDurations returns the RespectSectionDurations field if non-nil, zero value otherwise.

### GetRespectSectionDurationsOk

`func (o *MusicParameters) GetRespectSectionDurationsOk() (*bool, bool)`

GetRespectSectionDurationsOk returns a tuple with the RespectSectionDurations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRespectSectionDurations

`func (o *MusicParameters) SetRespectSectionDurations(v bool)`

SetRespectSectionDurations sets RespectSectionDurations field to given value.

### HasRespectSectionDurations

`func (o *MusicParameters) HasRespectSectionDurations() bool`

HasRespectSectionDurations returns a boolean if a field has been set.

### SetRespectSectionDurationsNil

`func (o *MusicParameters) SetRespectSectionDurationsNil(b bool)`

 SetRespectSectionDurationsNil sets the value for RespectSectionDurations to be an explicit nil

### UnsetRespectSectionDurations
`func (o *MusicParameters) UnsetRespectSectionDurations()`

UnsetRespectSectionDurations ensures that no value is present for RespectSectionDurations, not even an explicit nil
### GetSampleRateHz

`func (o *MusicParameters) GetSampleRateHz() int32`

GetSampleRateHz returns the SampleRateHz field if non-nil, zero value otherwise.

### GetSampleRateHzOk

`func (o *MusicParameters) GetSampleRateHzOk() (*int32, bool)`

GetSampleRateHzOk returns a tuple with the SampleRateHz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleRateHz

`func (o *MusicParameters) SetSampleRateHz(v int32)`

SetSampleRateHz sets SampleRateHz field to given value.

### HasSampleRateHz

`func (o *MusicParameters) HasSampleRateHz() bool`

HasSampleRateHz returns a boolean if a field has been set.

### SetSampleRateHzNil

`func (o *MusicParameters) SetSampleRateHzNil(b bool)`

 SetSampleRateHzNil sets the value for SampleRateHz to be an explicit nil

### UnsetSampleRateHz
`func (o *MusicParameters) UnsetSampleRateHz()`

UnsetSampleRateHz ensures that no value is present for SampleRateHz, not even an explicit nil
### GetScale

`func (o *MusicParameters) GetScale() string`

GetScale returns the Scale field if non-nil, zero value otherwise.

### GetScaleOk

`func (o *MusicParameters) GetScaleOk() (*string, bool)`

GetScaleOk returns a tuple with the Scale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScale

`func (o *MusicParameters) SetScale(v string)`

SetScale sets Scale field to given value.

### HasScale

`func (o *MusicParameters) HasScale() bool`

HasScale returns a boolean if a field has been set.

### SetScaleNil

`func (o *MusicParameters) SetScaleNil(b bool)`

 SetScaleNil sets the value for Scale to be an explicit nil

### UnsetScale
`func (o *MusicParameters) UnsetScale()`

UnsetScale ensures that no value is present for Scale, not even an explicit nil
### GetSeed

`func (o *MusicParameters) GetSeed() int32`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *MusicParameters) GetSeedOk() (*int32, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *MusicParameters) SetSeed(v int32)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *MusicParameters) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### SetSeedNil

`func (o *MusicParameters) SetSeedNil(b bool)`

 SetSeedNil sets the value for Seed to be an explicit nil

### UnsetSeed
`func (o *MusicParameters) UnsetSeed()`

UnsetSeed ensures that no value is present for Seed, not even an explicit nil
### GetStyle

`func (o *MusicParameters) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *MusicParameters) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *MusicParameters) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *MusicParameters) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### SetStyleNil

`func (o *MusicParameters) SetStyleNil(b bool)`

 SetStyleNil sets the value for Style to be an explicit nil

### UnsetStyle
`func (o *MusicParameters) UnsetStyle()`

UnsetStyle ensures that no value is present for Style, not even an explicit nil
### GetStyleStrength

`func (o *MusicParameters) GetStyleStrength() float32`

GetStyleStrength returns the StyleStrength field if non-nil, zero value otherwise.

### GetStyleStrengthOk

`func (o *MusicParameters) GetStyleStrengthOk() (*float32, bool)`

GetStyleStrengthOk returns a tuple with the StyleStrength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyleStrength

`func (o *MusicParameters) SetStyleStrength(v float32)`

SetStyleStrength sets StyleStrength field to given value.

### HasStyleStrength

`func (o *MusicParameters) HasStyleStrength() bool`

HasStyleStrength returns a boolean if a field has been set.

### SetStyleStrengthNil

`func (o *MusicParameters) SetStyleStrengthNil(b bool)`

 SetStyleStrengthNil sets the value for StyleStrength to be an explicit nil

### UnsetStyleStrength
`func (o *MusicParameters) UnsetStyleStrength()`

UnsetStyleStrength ensures that no value is present for StyleStrength, not even an explicit nil
### GetTimeSignature

`func (o *MusicParameters) GetTimeSignature() string`

GetTimeSignature returns the TimeSignature field if non-nil, zero value otherwise.

### GetTimeSignatureOk

`func (o *MusicParameters) GetTimeSignatureOk() (*string, bool)`

GetTimeSignatureOk returns a tuple with the TimeSignature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSignature

`func (o *MusicParameters) SetTimeSignature(v string)`

SetTimeSignature sets TimeSignature field to given value.

### HasTimeSignature

`func (o *MusicParameters) HasTimeSignature() bool`

HasTimeSignature returns a boolean if a field has been set.

### SetTimeSignatureNil

`func (o *MusicParameters) SetTimeSignatureNil(b bool)`

 SetTimeSignatureNil sets the value for TimeSignature to be an explicit nil

### UnsetTimeSignature
`func (o *MusicParameters) UnsetTimeSignature()`

UnsetTimeSignature ensures that no value is present for TimeSignature, not even an explicit nil
### GetTitle

`func (o *MusicParameters) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *MusicParameters) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *MusicParameters) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *MusicParameters) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *MusicParameters) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *MusicParameters) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetVocalGender

`func (o *MusicParameters) GetVocalGender() string`

GetVocalGender returns the VocalGender field if non-nil, zero value otherwise.

### GetVocalGenderOk

`func (o *MusicParameters) GetVocalGenderOk() (*string, bool)`

GetVocalGenderOk returns a tuple with the VocalGender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVocalGender

`func (o *MusicParameters) SetVocalGender(v string)`

SetVocalGender sets VocalGender field to given value.

### HasVocalGender

`func (o *MusicParameters) HasVocalGender() bool`

HasVocalGender returns a boolean if a field has been set.

### SetVocalGenderNil

`func (o *MusicParameters) SetVocalGenderNil(b bool)`

 SetVocalGenderNil sets the value for VocalGender to be an explicit nil

### UnsetVocalGender
`func (o *MusicParameters) UnsetVocalGender()`

UnsetVocalGender ensures that no value is present for VocalGender, not even an explicit nil
### GetVocalLanguage

`func (o *MusicParameters) GetVocalLanguage() string`

GetVocalLanguage returns the VocalLanguage field if non-nil, zero value otherwise.

### GetVocalLanguageOk

`func (o *MusicParameters) GetVocalLanguageOk() (*string, bool)`

GetVocalLanguageOk returns a tuple with the VocalLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVocalLanguage

`func (o *MusicParameters) SetVocalLanguage(v string)`

SetVocalLanguage sets VocalLanguage field to given value.

### HasVocalLanguage

`func (o *MusicParameters) HasVocalLanguage() bool`

HasVocalLanguage returns a boolean if a field has been set.

### SetVocalLanguageNil

`func (o *MusicParameters) SetVocalLanguageNil(b bool)`

 SetVocalLanguageNil sets the value for VocalLanguage to be an explicit nil

### UnsetVocalLanguage
`func (o *MusicParameters) UnsetVocalLanguage()`

UnsetVocalLanguage ensures that no value is present for VocalLanguage, not even an explicit nil
### GetVoice

`func (o *MusicParameters) GetVoice() string`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *MusicParameters) GetVoiceOk() (*string, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *MusicParameters) SetVoice(v string)`

SetVoice sets Voice field to given value.

### HasVoice

`func (o *MusicParameters) HasVoice() bool`

HasVoice returns a boolean if a field has been set.

### SetVoiceNil

`func (o *MusicParameters) SetVoiceNil(b bool)`

 SetVoiceNil sets the value for Voice to be an explicit nil

### UnsetVoice
`func (o *MusicParameters) UnsetVoice()`

UnsetVoice ensures that no value is present for Voice, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


