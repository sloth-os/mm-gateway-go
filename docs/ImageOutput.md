# ImageOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MimeType** | Pointer to **NullableString** |  | [optional] 
**RevisedPrompt** | Pointer to **NullableString** |  | [optional] 
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewImageOutput

`func NewImageOutput(uri string, ) *ImageOutput`

NewImageOutput instantiates a new ImageOutput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageOutputWithDefaults

`func NewImageOutputWithDefaults() *ImageOutput`

NewImageOutputWithDefaults instantiates a new ImageOutput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMimeType

`func (o *ImageOutput) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *ImageOutput) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *ImageOutput) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *ImageOutput) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *ImageOutput) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *ImageOutput) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetRevisedPrompt

`func (o *ImageOutput) GetRevisedPrompt() string`

GetRevisedPrompt returns the RevisedPrompt field if non-nil, zero value otherwise.

### GetRevisedPromptOk

`func (o *ImageOutput) GetRevisedPromptOk() (*string, bool)`

GetRevisedPromptOk returns a tuple with the RevisedPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisedPrompt

`func (o *ImageOutput) SetRevisedPrompt(v string)`

SetRevisedPrompt sets RevisedPrompt field to given value.

### HasRevisedPrompt

`func (o *ImageOutput) HasRevisedPrompt() bool`

HasRevisedPrompt returns a boolean if a field has been set.

### SetRevisedPromptNil

`func (o *ImageOutput) SetRevisedPromptNil(b bool)`

 SetRevisedPromptNil sets the value for RevisedPrompt to be an explicit nil

### UnsetRevisedPrompt
`func (o *ImageOutput) UnsetRevisedPrompt()`

UnsetRevisedPrompt ensures that no value is present for RevisedPrompt, not even an explicit nil
### GetUri

`func (o *ImageOutput) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *ImageOutput) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *ImageOutput) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


