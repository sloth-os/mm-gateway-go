# VideoImageInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | Pointer to **string** |  | [optional] [default to "first_frame"]
**Type** | **string** |  | 
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewVideoImageInput

`func NewVideoImageInput(type_ string, uri string, ) *VideoImageInput`

NewVideoImageInput instantiates a new VideoImageInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVideoImageInputWithDefaults

`func NewVideoImageInputWithDefaults() *VideoImageInput`

NewVideoImageInputWithDefaults instantiates a new VideoImageInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *VideoImageInput) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *VideoImageInput) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *VideoImageInput) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *VideoImageInput) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetType

`func (o *VideoImageInput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VideoImageInput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VideoImageInput) SetType(v string)`

SetType sets Type field to given value.


### GetUri

`func (o *VideoImageInput) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *VideoImageInput) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *VideoImageInput) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


