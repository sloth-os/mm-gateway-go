# ManagementConfigResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | [**ManagementConfigOutput**](ManagementConfigOutput.md) |  | 
**Persistent** | **bool** |  | 
**Revision** | **string** |  | 

## Methods

### NewManagementConfigResponse

`func NewManagementConfigResponse(config ManagementConfigOutput, persistent bool, revision string, ) *ManagementConfigResponse`

NewManagementConfigResponse instantiates a new ManagementConfigResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagementConfigResponseWithDefaults

`func NewManagementConfigResponseWithDefaults() *ManagementConfigResponse`

NewManagementConfigResponseWithDefaults instantiates a new ManagementConfigResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *ManagementConfigResponse) GetConfig() ManagementConfigOutput`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *ManagementConfigResponse) GetConfigOk() (*ManagementConfigOutput, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *ManagementConfigResponse) SetConfig(v ManagementConfigOutput)`

SetConfig sets Config field to given value.


### GetPersistent

`func (o *ManagementConfigResponse) GetPersistent() bool`

GetPersistent returns the Persistent field if non-nil, zero value otherwise.

### GetPersistentOk

`func (o *ManagementConfigResponse) GetPersistentOk() (*bool, bool)`

GetPersistentOk returns a tuple with the Persistent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersistent

`func (o *ManagementConfigResponse) SetPersistent(v bool)`

SetPersistent sets Persistent field to given value.


### GetRevision

`func (o *ManagementConfigResponse) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ManagementConfigResponse) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ManagementConfigResponse) SetRevision(v string)`

SetRevision sets Revision field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


