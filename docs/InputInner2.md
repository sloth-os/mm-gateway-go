# InputInner2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** |  | 
**Type** | **string** |  | 
**Role** | Pointer to **string** |  | [optional] [default to "reference_video"]
**Uri** | **string** | Absolute media URI. Inline media uses a base64 data URI. | 

## Methods

### NewInputInner2

`func NewInputInner2(text string, type_ string, uri string, ) *InputInner2`

NewInputInner2 instantiates a new InputInner2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInputInner2WithDefaults

`func NewInputInner2WithDefaults() *InputInner2`

NewInputInner2WithDefaults instantiates a new InputInner2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *InputInner2) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *InputInner2) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *InputInner2) SetText(v string)`

SetText sets Text field to given value.


### GetType

`func (o *InputInner2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InputInner2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InputInner2) SetType(v string)`

SetType sets Type field to given value.


### GetRole

`func (o *InputInner2) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *InputInner2) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *InputInner2) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *InputInner2) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetUri

`func (o *InputInner2) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *InputInner2) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *InputInner2) SetUri(v string)`

SetUri sets Uri field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


