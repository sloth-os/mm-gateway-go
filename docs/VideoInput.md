# VideoInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | Pointer to **string** |  | [optional] [default to "reference_video"]
**Type** | **string** |  | 
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewVideoInput

`func NewVideoInput(type_ string, uri string, ) *VideoInput`

NewVideoInput instantiates a new VideoInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVideoInputWithDefaults

`func NewVideoInputWithDefaults() *VideoInput`

NewVideoInputWithDefaults instantiates a new VideoInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *VideoInput) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *VideoInput) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *VideoInput) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *VideoInput) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetType

`func (o *VideoInput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VideoInput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VideoInput) SetType(v string)`

SetType sets Type field to given value.


### GetUri

`func (o *VideoInput) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *VideoInput) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *VideoInput) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


