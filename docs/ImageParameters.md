# ImageParameters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Background** | Pointer to **NullableString** |  | [optional] 
**Compression** | Pointer to **NullableInt32** |  | [optional] 
**Delivery** | Pointer to **NullableString** |  | [optional] 
**Dimensions** | Pointer to [**NullableDimensions**](Dimensions.md) |  | [optional] 
**FileFormat** | Pointer to **NullableString** |  | [optional] 
**GuidanceScale** | Pointer to **NullableFloat32** |  | [optional] 
**InferenceSteps** | Pointer to **NullableInt32** |  | [optional] 
**NegativePrompt** | Pointer to **NullableString** |  | [optional] 
**OutputCount** | Pointer to **NullableInt32** |  | [optional] 
**Quality** | Pointer to **NullableString** |  | [optional] 
**Seed** | Pointer to **NullableInt32** |  | [optional] 
**Strength** | Pointer to **NullableFloat32** |  | [optional] 
**Style** | Pointer to **NullableString** |  | [optional] 
**Watermark** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewImageParameters

`func NewImageParameters() *ImageParameters`

NewImageParameters instantiates a new ImageParameters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageParametersWithDefaults

`func NewImageParametersWithDefaults() *ImageParameters`

NewImageParametersWithDefaults instantiates a new ImageParameters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackground

`func (o *ImageParameters) GetBackground() string`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *ImageParameters) GetBackgroundOk() (*string, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *ImageParameters) SetBackground(v string)`

SetBackground sets Background field to given value.

### HasBackground

`func (o *ImageParameters) HasBackground() bool`

HasBackground returns a boolean if a field has been set.

### SetBackgroundNil

`func (o *ImageParameters) SetBackgroundNil(b bool)`

 SetBackgroundNil sets the value for Background to be an explicit nil

### UnsetBackground
`func (o *ImageParameters) UnsetBackground()`

UnsetBackground ensures that no value is present for Background, not even an explicit nil
### GetCompression

`func (o *ImageParameters) GetCompression() int32`

GetCompression returns the Compression field if non-nil, zero value otherwise.

### GetCompressionOk

`func (o *ImageParameters) GetCompressionOk() (*int32, bool)`

GetCompressionOk returns a tuple with the Compression field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompression

`func (o *ImageParameters) SetCompression(v int32)`

SetCompression sets Compression field to given value.

### HasCompression

`func (o *ImageParameters) HasCompression() bool`

HasCompression returns a boolean if a field has been set.

### SetCompressionNil

`func (o *ImageParameters) SetCompressionNil(b bool)`

 SetCompressionNil sets the value for Compression to be an explicit nil

### UnsetCompression
`func (o *ImageParameters) UnsetCompression()`

UnsetCompression ensures that no value is present for Compression, not even an explicit nil
### GetDelivery

`func (o *ImageParameters) GetDelivery() string`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *ImageParameters) GetDeliveryOk() (*string, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *ImageParameters) SetDelivery(v string)`

SetDelivery sets Delivery field to given value.

### HasDelivery

`func (o *ImageParameters) HasDelivery() bool`

HasDelivery returns a boolean if a field has been set.

### SetDeliveryNil

`func (o *ImageParameters) SetDeliveryNil(b bool)`

 SetDeliveryNil sets the value for Delivery to be an explicit nil

### UnsetDelivery
`func (o *ImageParameters) UnsetDelivery()`

UnsetDelivery ensures that no value is present for Delivery, not even an explicit nil
### GetDimensions

`func (o *ImageParameters) GetDimensions() Dimensions`

GetDimensions returns the Dimensions field if non-nil, zero value otherwise.

### GetDimensionsOk

`func (o *ImageParameters) GetDimensionsOk() (*Dimensions, bool)`

GetDimensionsOk returns a tuple with the Dimensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDimensions

`func (o *ImageParameters) SetDimensions(v Dimensions)`

SetDimensions sets Dimensions field to given value.

### HasDimensions

`func (o *ImageParameters) HasDimensions() bool`

HasDimensions returns a boolean if a field has been set.

### SetDimensionsNil

`func (o *ImageParameters) SetDimensionsNil(b bool)`

 SetDimensionsNil sets the value for Dimensions to be an explicit nil

### UnsetDimensions
`func (o *ImageParameters) UnsetDimensions()`

UnsetDimensions ensures that no value is present for Dimensions, not even an explicit nil
### GetFileFormat

`func (o *ImageParameters) GetFileFormat() string`

GetFileFormat returns the FileFormat field if non-nil, zero value otherwise.

### GetFileFormatOk

`func (o *ImageParameters) GetFileFormatOk() (*string, bool)`

GetFileFormatOk returns a tuple with the FileFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileFormat

`func (o *ImageParameters) SetFileFormat(v string)`

SetFileFormat sets FileFormat field to given value.

### HasFileFormat

`func (o *ImageParameters) HasFileFormat() bool`

HasFileFormat returns a boolean if a field has been set.

### SetFileFormatNil

`func (o *ImageParameters) SetFileFormatNil(b bool)`

 SetFileFormatNil sets the value for FileFormat to be an explicit nil

### UnsetFileFormat
`func (o *ImageParameters) UnsetFileFormat()`

UnsetFileFormat ensures that no value is present for FileFormat, not even an explicit nil
### GetGuidanceScale

`func (o *ImageParameters) GetGuidanceScale() float32`

GetGuidanceScale returns the GuidanceScale field if non-nil, zero value otherwise.

### GetGuidanceScaleOk

`func (o *ImageParameters) GetGuidanceScaleOk() (*float32, bool)`

GetGuidanceScaleOk returns a tuple with the GuidanceScale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidanceScale

`func (o *ImageParameters) SetGuidanceScale(v float32)`

SetGuidanceScale sets GuidanceScale field to given value.

### HasGuidanceScale

`func (o *ImageParameters) HasGuidanceScale() bool`

HasGuidanceScale returns a boolean if a field has been set.

### SetGuidanceScaleNil

`func (o *ImageParameters) SetGuidanceScaleNil(b bool)`

 SetGuidanceScaleNil sets the value for GuidanceScale to be an explicit nil

### UnsetGuidanceScale
`func (o *ImageParameters) UnsetGuidanceScale()`

UnsetGuidanceScale ensures that no value is present for GuidanceScale, not even an explicit nil
### GetInferenceSteps

`func (o *ImageParameters) GetInferenceSteps() int32`

GetInferenceSteps returns the InferenceSteps field if non-nil, zero value otherwise.

### GetInferenceStepsOk

`func (o *ImageParameters) GetInferenceStepsOk() (*int32, bool)`

GetInferenceStepsOk returns a tuple with the InferenceSteps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInferenceSteps

`func (o *ImageParameters) SetInferenceSteps(v int32)`

SetInferenceSteps sets InferenceSteps field to given value.

### HasInferenceSteps

`func (o *ImageParameters) HasInferenceSteps() bool`

HasInferenceSteps returns a boolean if a field has been set.

### SetInferenceStepsNil

`func (o *ImageParameters) SetInferenceStepsNil(b bool)`

 SetInferenceStepsNil sets the value for InferenceSteps to be an explicit nil

### UnsetInferenceSteps
`func (o *ImageParameters) UnsetInferenceSteps()`

UnsetInferenceSteps ensures that no value is present for InferenceSteps, not even an explicit nil
### GetNegativePrompt

`func (o *ImageParameters) GetNegativePrompt() string`

GetNegativePrompt returns the NegativePrompt field if non-nil, zero value otherwise.

### GetNegativePromptOk

`func (o *ImageParameters) GetNegativePromptOk() (*string, bool)`

GetNegativePromptOk returns a tuple with the NegativePrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativePrompt

`func (o *ImageParameters) SetNegativePrompt(v string)`

SetNegativePrompt sets NegativePrompt field to given value.

### HasNegativePrompt

`func (o *ImageParameters) HasNegativePrompt() bool`

HasNegativePrompt returns a boolean if a field has been set.

### SetNegativePromptNil

`func (o *ImageParameters) SetNegativePromptNil(b bool)`

 SetNegativePromptNil sets the value for NegativePrompt to be an explicit nil

### UnsetNegativePrompt
`func (o *ImageParameters) UnsetNegativePrompt()`

UnsetNegativePrompt ensures that no value is present for NegativePrompt, not even an explicit nil
### GetOutputCount

`func (o *ImageParameters) GetOutputCount() int32`

GetOutputCount returns the OutputCount field if non-nil, zero value otherwise.

### GetOutputCountOk

`func (o *ImageParameters) GetOutputCountOk() (*int32, bool)`

GetOutputCountOk returns a tuple with the OutputCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputCount

`func (o *ImageParameters) SetOutputCount(v int32)`

SetOutputCount sets OutputCount field to given value.

### HasOutputCount

`func (o *ImageParameters) HasOutputCount() bool`

HasOutputCount returns a boolean if a field has been set.

### SetOutputCountNil

`func (o *ImageParameters) SetOutputCountNil(b bool)`

 SetOutputCountNil sets the value for OutputCount to be an explicit nil

### UnsetOutputCount
`func (o *ImageParameters) UnsetOutputCount()`

UnsetOutputCount ensures that no value is present for OutputCount, not even an explicit nil
### GetQuality

`func (o *ImageParameters) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *ImageParameters) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *ImageParameters) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *ImageParameters) HasQuality() bool`

HasQuality returns a boolean if a field has been set.

### SetQualityNil

`func (o *ImageParameters) SetQualityNil(b bool)`

 SetQualityNil sets the value for Quality to be an explicit nil

### UnsetQuality
`func (o *ImageParameters) UnsetQuality()`

UnsetQuality ensures that no value is present for Quality, not even an explicit nil
### GetSeed

`func (o *ImageParameters) GetSeed() int32`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *ImageParameters) GetSeedOk() (*int32, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *ImageParameters) SetSeed(v int32)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *ImageParameters) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### SetSeedNil

`func (o *ImageParameters) SetSeedNil(b bool)`

 SetSeedNil sets the value for Seed to be an explicit nil

### UnsetSeed
`func (o *ImageParameters) UnsetSeed()`

UnsetSeed ensures that no value is present for Seed, not even an explicit nil
### GetStrength

`func (o *ImageParameters) GetStrength() float32`

GetStrength returns the Strength field if non-nil, zero value otherwise.

### GetStrengthOk

`func (o *ImageParameters) GetStrengthOk() (*float32, bool)`

GetStrengthOk returns a tuple with the Strength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrength

`func (o *ImageParameters) SetStrength(v float32)`

SetStrength sets Strength field to given value.

### HasStrength

`func (o *ImageParameters) HasStrength() bool`

HasStrength returns a boolean if a field has been set.

### SetStrengthNil

`func (o *ImageParameters) SetStrengthNil(b bool)`

 SetStrengthNil sets the value for Strength to be an explicit nil

### UnsetStrength
`func (o *ImageParameters) UnsetStrength()`

UnsetStrength ensures that no value is present for Strength, not even an explicit nil
### GetStyle

`func (o *ImageParameters) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *ImageParameters) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *ImageParameters) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *ImageParameters) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### SetStyleNil

`func (o *ImageParameters) SetStyleNil(b bool)`

 SetStyleNil sets the value for Style to be an explicit nil

### UnsetStyle
`func (o *ImageParameters) UnsetStyle()`

UnsetStyle ensures that no value is present for Style, not even an explicit nil
### GetWatermark

`func (o *ImageParameters) GetWatermark() bool`

GetWatermark returns the Watermark field if non-nil, zero value otherwise.

### GetWatermarkOk

`func (o *ImageParameters) GetWatermarkOk() (*bool, bool)`

GetWatermarkOk returns a tuple with the Watermark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWatermark

`func (o *ImageParameters) SetWatermark(v bool)`

SetWatermark sets Watermark field to given value.

### HasWatermark

`func (o *ImageParameters) HasWatermark() bool`

HasWatermark returns a boolean if a field has been set.

### SetWatermarkNil

`func (o *ImageParameters) SetWatermarkNil(b bool)`

 SetWatermarkNil sets the value for Watermark to be an explicit nil

### UnsetWatermark
`func (o *ImageParameters) UnsetWatermark()`

UnsetWatermark ensures that no value is present for Watermark, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


