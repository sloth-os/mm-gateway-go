# VideoParameters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CameraMotion** | Pointer to **NullableString** |  | [optional] 
**Dimensions** | Pointer to [**NullableDimensions**](Dimensions.md) |  | [optional] 
**DurationSeconds** | Pointer to **NullableFloat32** |  | [optional] 
**EnhancePrompt** | Pointer to **NullableBool** |  | [optional] 
**FileFormat** | Pointer to **NullableString** |  | [optional] 
**Fps** | Pointer to **NullableInt32** |  | [optional] 
**FrameCount** | Pointer to **NullableInt32** |  | [optional] 
**GuidanceScale** | Pointer to **NullableFloat32** |  | [optional] 
**IncludeAudio** | Pointer to **NullableBool** |  | [optional] 
**IncludeLastFrame** | Pointer to **NullableBool** |  | [optional] 
**MotionIntensity** | Pointer to **NullableInt32** |  | [optional] 
**NegativePrompt** | Pointer to **NullableString** |  | [optional] 
**Seed** | Pointer to **NullableInt32** |  | [optional] 
**Watermark** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewVideoParameters

`func NewVideoParameters() *VideoParameters`

NewVideoParameters instantiates a new VideoParameters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVideoParametersWithDefaults

`func NewVideoParametersWithDefaults() *VideoParameters`

NewVideoParametersWithDefaults instantiates a new VideoParameters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCameraMotion

`func (o *VideoParameters) GetCameraMotion() string`

GetCameraMotion returns the CameraMotion field if non-nil, zero value otherwise.

### GetCameraMotionOk

`func (o *VideoParameters) GetCameraMotionOk() (*string, bool)`

GetCameraMotionOk returns a tuple with the CameraMotion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCameraMotion

`func (o *VideoParameters) SetCameraMotion(v string)`

SetCameraMotion sets CameraMotion field to given value.

### HasCameraMotion

`func (o *VideoParameters) HasCameraMotion() bool`

HasCameraMotion returns a boolean if a field has been set.

### SetCameraMotionNil

`func (o *VideoParameters) SetCameraMotionNil(b bool)`

 SetCameraMotionNil sets the value for CameraMotion to be an explicit nil

### UnsetCameraMotion
`func (o *VideoParameters) UnsetCameraMotion()`

UnsetCameraMotion ensures that no value is present for CameraMotion, not even an explicit nil
### GetDimensions

`func (o *VideoParameters) GetDimensions() Dimensions`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *VideoParameters) GetDimensionsOk() (*Dimensions, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *VideoParameters) SetDimensions(v Dimensions)`

SetDimensions sets Dimensions field to given value.

### HasDimensions

`func (o *VideoParameters) HasDimensions() bool`

HasDimensions returns a boolean if a field has been set.

### SetDimensionsNil

`func (o *VideoParameters) SetDimensionsNil(b bool)`

 SetDimensionsNil sets the value for Dimensions to be an explicit nil

### UnsetDimensions
`func (o *VideoParameters) UnsetDimensions()`

UnsetDimensions ensures that no value is present for Dimensions, not even an explicit nil
### GetDurationSeconds

`func (o *VideoParameters) GetDurationSeconds() float32`

GetDurationSeconds returns the DurationSeconds field if non-nil, zero value otherwise.

### GetDurationSecondsOk

`func (o *VideoParameters) GetDurationSecondsOk() (*float32, bool)`

GetDurationSecondsOk returns a tuple with the DurationSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationSeconds

`func (o *VideoParameters) SetDurationSeconds(v float32)`

SetDurationSeconds sets DurationSeconds field to given value.

### HasDurationSeconds

`func (o *VideoParameters) HasDurationSeconds() bool`

HasDurationSeconds returns a boolean if a field has been set.

### SetDurationSecondsNil

`func (o *VideoParameters) SetDurationSecondsNil(b bool)`

 SetDurationSecondsNil sets the value for DurationSeconds to be an explicit nil

### UnsetDurationSeconds
`func (o *VideoParameters) UnsetDurationSeconds()`

UnsetDurationSeconds ensures that no value is present for DurationSeconds, not even an explicit nil
### GetEnhancePrompt

`func (o *VideoParameters) GetEnhancePrompt() bool`

GetEnhancePrompt returns the EnhancePrompt field if non-nil, zero value otherwise.

### GetEnhancePromptOk

`func (o *VideoParameters) GetEnhancePromptOk() (*bool, bool)`

GetEnhancePromptOk returns a tuple with the EnhancePrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnhancePrompt

`func (o *VideoParameters) SetEnhancePrompt(v bool)`

SetEnhancePrompt sets EnhancePrompt field to given value.

### HasEnhancePrompt

`func (o *VideoParameters) HasEnhancePrompt() bool`

HasEnhancePrompt returns a boolean if a field has been set.

### SetEnhancePromptNil

`func (o *VideoParameters) SetEnhancePromptNil(b bool)`

 SetEnhancePromptNil sets the value for EnhancePrompt to be an explicit nil

### UnsetEnhancePrompt
`func (o *VideoParameters) UnsetEnhancePrompt()`

UnsetEnhancePrompt ensures that no value is present for EnhancePrompt, not even an explicit nil
### GetFileFormat

`func (o *VideoParameters) GetFileFormat() string`

GetFileFormat returns the FileFormat field if non-nil, zero value otherwise.

### GetFileFormatOk

`func (o *VideoParameters) GetFileFormatOk() (*string, bool)`

GetFileFormatOk returns a tuple with the FileFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileFormat

`func (o *VideoParameters) SetFileFormat(v string)`

SetFileFormat sets FileFormat field to given value.

### HasFileFormat

`func (o *VideoParameters) HasFileFormat() bool`

HasFileFormat returns a boolean if a field has been set.

### SetFileFormatNil

`func (o *VideoParameters) SetFileFormatNil(b bool)`

 SetFileFormatNil sets the value for FileFormat to be an explicit nil

### UnsetFileFormat
`func (o *VideoParameters) UnsetFileFormat()`

UnsetFileFormat ensures that no value is present for FileFormat, not even an explicit nil
### GetFps

`func (o *VideoParameters) GetFps() int32`

GetFps returns the Fps field if non-nil, zero value otherwise.

### GetFpsOk

`func (o *VideoParameters) GetFpsOk() (*int32, bool)`

GetFpsOk returns a tuple with the Fps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFps

`func (o *VideoParameters) SetFps(v int32)`

SetFps sets Fps field to given value.

### HasFps

`func (o *VideoParameters) HasFps() bool`

HasFps returns a boolean if a field has been set.

### SetFpsNil

`func (o *VideoParameters) SetFpsNil(b bool)`

 SetFpsNil sets the value for Fps to be an explicit nil

### UnsetFps
`func (o *VideoParameters) UnsetFps()`

UnsetFps ensures that no value is present for Fps, not even an explicit nil
### GetFrameCount

`func (o *VideoParameters) GetFrameCount() int32`

GetFrameCount returns the FrameCount field if non-nil, zero value otherwise.

### GetFrameCountOk

`func (o *VideoParameters) GetFrameCountOk() (*int32, bool)`

GetFrameCountOk returns a tuple with the FrameCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrameCount

`func (o *VideoParameters) SetFrameCount(v int32)`

SetFrameCount sets FrameCount field to given value.

### HasFrameCount

`func (o *VideoParameters) HasFrameCount() bool`

HasFrameCount returns a boolean if a field has been set.

### SetFrameCountNil

`func (o *VideoParameters) SetFrameCountNil(b bool)`

 SetFrameCountNil sets the value for FrameCount to be an explicit nil

### UnsetFrameCount
`func (o *VideoParameters) UnsetFrameCount()`

UnsetFrameCount ensures that no value is present for FrameCount, not even an explicit nil
### GetGuidanceScale

`func (o *VideoParameters) GetGuidanceScale() float32`

GetGuidanceScale returns the GuidanceScale field if non-nil, zero value otherwise.

### GetGuidanceScaleOk

`func (o *VideoParameters) GetGuidanceScaleOk() (*float32, bool)`

GetGuidanceScaleOk returns a tuple with the GuidanceScale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidanceScale

`func (o *VideoParameters) SetGuidanceScale(v float32)`

SetGuidanceScale sets GuidanceScale field to given value.

### HasGuidanceScale

`func (o *VideoParameters) HasGuidanceScale() bool`

HasGuidanceScale returns a boolean if a field has been set.

### SetGuidanceScaleNil

`func (o *VideoParameters) SetGuidanceScaleNil(b bool)`

 SetGuidanceScaleNil sets the value for GuidanceScale to be an explicit nil

### UnsetGuidanceScale
`func (o *VideoParameters) UnsetGuidanceScale()`

UnsetGuidanceScale ensures that no value is present for GuidanceScale, not even an explicit nil
### GetIncludeAudio

`func (o *VideoParameters) GetIncludeAudio() bool`

GetIncludeAudio returns the IncludeAudio field if non-nil, zero value otherwise.

### GetIncludeAudioOk

`func (o *VideoParameters) GetIncludeAudioOk() (*bool, bool)`

GetIncludeAudioOk returns a tuple with the IncludeAudio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeAudio

`func (o *VideoParameters) SetIncludeAudio(v bool)`

SetIncludeAudio sets IncludeAudio field to given value.

### HasIncludeAudio

`func (o *VideoParameters) HasIncludeAudio() bool`

HasIncludeAudio returns a boolean if a field has been set.

### SetIncludeAudioNil

`func (o *VideoParameters) SetIncludeAudioNil(b bool)`

 SetIncludeAudioNil sets the value for IncludeAudio to be an explicit nil

### UnsetIncludeAudio
`func (o *VideoParameters) UnsetIncludeAudio()`

UnsetIncludeAudio ensures that no value is present for IncludeAudio, not even an explicit nil
### GetIncludeLastFrame

`func (o *VideoParameters) GetIncludeLastFrame() bool`

GetIncludeLastFrame returns the IncludeLastFrame field if non-nil, zero value otherwise.

### GetIncludeLastFrameOk

`func (o *VideoParameters) GetIncludeLastFrameOk() (*bool, bool)`

GetIncludeLastFrameOk returns a tuple with the IncludeLastFrame field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeLastFrame

`func (o *VideoParameters) SetIncludeLastFrame(v bool)`

SetIncludeLastFrame sets IncludeLastFrame field to given value.

### HasIncludeLastFrame

`func (o *VideoParameters) HasIncludeLastFrame() bool`

HasIncludeLastFrame returns a boolean if a field has been set.

### SetIncludeLastFrameNil

`func (o *VideoParameters) SetIncludeLastFrameNil(b bool)`

 SetIncludeLastFrameNil sets the value for IncludeLastFrame to be an explicit nil

### UnsetIncludeLastFrame
`func (o *VideoParameters) UnsetIncludeLastFrame()`

UnsetIncludeLastFrame ensures that no value is present for IncludeLastFrame, not even an explicit nil
### GetMotionIntensity

`func (o *VideoParameters) GetMotionIntensity() int32`

GetMotionIntensity returns the MotionIntensity field if non-nil, zero value otherwise.

### GetMotionIntensityOk

`func (o *VideoParameters) GetMotionIntensityOk() (*int32, bool)`

GetMotionIntensityOk returns a tuple with the MotionIntensity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMotionIntensity

`func (o *VideoParameters) SetMotionIntensity(v int32)`

SetMotionIntensity sets MotionIntensity field to given value.

### HasMotionIntensity

`func (o *VideoParameters) HasMotionIntensity() bool`

HasMotionIntensity returns a boolean if a field has been set.

### SetMotionIntensityNil

`func (o *VideoParameters) SetMotionIntensityNil(b bool)`

 SetMotionIntensityNil sets the value for MotionIntensity to be an explicit nil

### UnsetMotionIntensity
`func (o *VideoParameters) UnsetMotionIntensity()`

UnsetMotionIntensity ensures that no value is present for MotionIntensity, not even an explicit nil
### GetNegativePrompt

`func (o *VideoParameters) GetNegativePrompt() string`

GetNegativePrompt returns the NegativePrompt field if non-nil, zero value otherwise.

### GetNegativePromptOk

`func (o *VideoParameters) GetNegativePromptOk() (*string, bool)`

GetNegativePromptOk returns a tuple with the NegativePrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativePrompt

`func (o *VideoParameters) SetNegativePrompt(v string)`

SetNegativePrompt sets NegativePrompt field to given value.

### HasNegativePrompt

`func (o *VideoParameters) HasNegativePrompt() bool`

HasNegativePrompt returns a boolean if a field has been set.

### SetNegativePromptNil

`func (o *VideoParameters) SetNegativePromptNil(b bool)`

 SetNegativePromptNil sets the value for NegativePrompt to be an explicit nil

### UnsetNegativePrompt
`func (o *VideoParameters) UnsetNegativePrompt()`

UnsetNegativePrompt ensures that no value is present for NegativePrompt, not even an explicit nil
### GetSeed

`func (o *VideoParameters) GetSeed() int32`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *VideoParameters) GetSeedOk() (*int32, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *VideoParameters) SetSeed(v int32)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *VideoParameters) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### SetSeedNil

`func (o *VideoParameters) SetSeedNil(b bool)`

 SetSeedNil sets the value for Seed to be an explicit nil

### UnsetSeed
`func (o *VideoParameters) UnsetSeed()`

UnsetSeed ensures that no value is present for Seed, not even an explicit nil
### GetWatermark

`func (o *VideoParameters) GetWatermark() bool`

GetWatermark returns the Watermark field if non-nil, zero value otherwise.

### GetWatermarkOk

`func (o *VideoParameters) GetWatermarkOk() (*bool, bool)`

GetWatermarkOk returns a tuple with the Watermark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWatermark

`func (o *VideoParameters) SetWatermark(v bool)`

SetWatermark sets Watermark field to given value.

### HasWatermark

`func (o *VideoParameters) HasWatermark() bool`

HasWatermark returns a boolean if a field has been set.

### SetWatermarkNil

`func (o *VideoParameters) SetWatermarkNil(b bool)`

 SetWatermarkNil sets the value for Watermark to be an explicit nil

### UnsetWatermark
`func (o *VideoParameters) UnsetWatermark()`

UnsetWatermark ensures that no value is present for Watermark, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


