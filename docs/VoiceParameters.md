# VoiceParameters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**RemoveBackgroundNoise** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewVoiceParameters

`func NewVoiceParameters(name string, ) *VoiceParameters`

NewVoiceParameters instantiates a new VoiceParameters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoiceParametersWithDefaults

`func NewVoiceParametersWithDefaults() *VoiceParameters`

NewVoiceParametersWithDefaults instantiates a new VoiceParameters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *VoiceParameters) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *VoiceParameters) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *VoiceParameters) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *VoiceParameters) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *VoiceParameters) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *VoiceParameters) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *VoiceParameters) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VoiceParameters) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VoiceParameters) SetName(v string)`

SetName sets Name field to given value.


### GetRemoveBackgroundNoise

`func (o *VoiceParameters) GetRemoveBackgroundNoise() bool`

GetRemoveBackgroundNoise returns the RemoveBackgroundNoise field if non-nil, zero value otherwise.

### GetRemoveBackgroundNoiseOk

`func (o *VoiceParameters) GetRemoveBackgroundNoiseOk() (*bool, bool)`

GetRemoveBackgroundNoiseOk returns a tuple with the RemoveBackgroundNoise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoveBackgroundNoise

`func (o *VoiceParameters) SetRemoveBackgroundNoise(v bool)`

SetRemoveBackgroundNoise sets RemoveBackgroundNoise field to given value.

### HasRemoveBackgroundNoise

`func (o *VoiceParameters) HasRemoveBackgroundNoise() bool`

HasRemoveBackgroundNoise returns a boolean if a field has been set.

### SetRemoveBackgroundNoiseNil

`func (o *VoiceParameters) SetRemoveBackgroundNoiseNil(b bool)`

 SetRemoveBackgroundNoiseNil sets the value for RemoveBackgroundNoise to be an explicit nil

### UnsetRemoveBackgroundNoise
`func (o *VoiceParameters) UnsetRemoveBackgroundNoise()`

UnsetRemoveBackgroundNoise ensures that no value is present for RemoveBackgroundNoise, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


