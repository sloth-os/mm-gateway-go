# VideoOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CoverUri** | Pointer to **NullableString** | Absolute media URI. Inline media uses a base64 data URI. | [optional] 
**MimeType** | Pointer to **NullableString** |  | [optional] 
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewVideoOutput

`func NewVideoOutput(uri string, ) *VideoOutput`

NewVideoOutput instantiates a new VideoOutput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVideoOutputWithDefaults

`func NewVideoOutputWithDefaults() *VideoOutput`

NewVideoOutputWithDefaults instantiates a new VideoOutput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCoverUri

`func (o *VideoOutput) GetCoverUri() string`

GetCoverUri returns the CoverUri field if non-nil, zero value otherwise.

### GetCoverUriOk

`func (o *VideoOutput) GetCoverUriOk() (*string, bool)`

GetCoverUriOk returns a tuple with the CoverUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoverUri

`func (o *VideoOutput) SetCoverUri(v string)`

SetCoverUri sets CoverUri field to given value.

### HasCoverUri

`func (o *VideoOutput) HasCoverUri() bool`

HasCoverUri returns a boolean if a field has been set.

### SetCoverUriNil

`func (o *VideoOutput) SetCoverUriNil(b bool)`

 SetCoverUriNil sets the value for CoverUri to be an explicit nil

### UnsetCoverUri
`func (o *VideoOutput) UnsetCoverUri()`

UnsetCoverUri ensures that no value is present for CoverUri, not even an explicit nil
### GetMimeType

`func (o *VideoOutput) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *VideoOutput) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *VideoOutput) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *VideoOutput) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *VideoOutput) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *VideoOutput) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetUri

`func (o *VideoOutput) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *VideoOutput) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *VideoOutput) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


