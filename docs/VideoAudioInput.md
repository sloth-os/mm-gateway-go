# VideoAudioInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | Pointer to **string** |  | [optional] [default to "reference_audio"]
**Type** | **string** |  | 
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewVideoAudioInput

`func NewVideoAudioInput(type_ string, uri string, ) *VideoAudioInput`

NewVideoAudioInput instantiates a new VideoAudioInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVideoAudioInputWithDefaults

`func NewVideoAudioInputWithDefaults() *VideoAudioInput`

NewVideoAudioInputWithDefaults instantiates a new VideoAudioInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *VideoAudioInput) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *VideoAudioInput) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *VideoAudioInput) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *VideoAudioInput) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetType

`func (o *VideoAudioInput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VideoAudioInput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VideoAudioInput) SetType(v string)`

SetType sets Type field to given value.


### GetUri

`func (o *VideoAudioInput) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *VideoAudioInput) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *VideoAudioInput) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


