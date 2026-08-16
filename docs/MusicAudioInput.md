# MusicAudioInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | Pointer to **string** |  | [optional] [default to "reference_audio"]
**Type** | **string** |  | 
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewMusicAudioInput

`func NewMusicAudioInput(type_ string, uri string, ) *MusicAudioInput`

NewMusicAudioInput instantiates a new MusicAudioInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMusicAudioInputWithDefaults

`func NewMusicAudioInputWithDefaults() *MusicAudioInput`

NewMusicAudioInputWithDefaults instantiates a new MusicAudioInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *MusicAudioInput) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *MusicAudioInput) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *MusicAudioInput) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *MusicAudioInput) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetType

`func (o *MusicAudioInput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MusicAudioInput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MusicAudioInput) SetType(v string)`

SetType sets Type field to given value.


### GetUri

`func (o *MusicAudioInput) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *MusicAudioInput) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *MusicAudioInput) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


