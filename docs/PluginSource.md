# PluginSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Commit** | Pointer to **NullableString** |  | [optional] 
**Kind** | **string** |  | 
**Path** | Pointer to **string** |  | [optional] [default to ""]
**Ref** | Pointer to **NullableString** |  | [optional] 
**Repository** | Pointer to **NullableString** |  | [optional] 
**Subdirectory** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewPluginSource

`func NewPluginSource(kind string, ) *PluginSource`

NewPluginSource instantiates a new PluginSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginSourceWithDefaults

`func NewPluginSourceWithDefaults() *PluginSource`

NewPluginSourceWithDefaults instantiates a new PluginSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommit

`func (o *PluginSource) GetCommit() string`

GetCommit returns the Commit field if non-nil, zero value otherwise.

### GetCommitOk

`func (o *PluginSource) GetCommitOk() (*string, bool)`

GetCommitOk returns a tuple with the Commit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommit

`func (o *PluginSource) SetCommit(v string)`

SetCommit sets Commit field to given value.

### HasCommit

`func (o *PluginSource) HasCommit() bool`

HasCommit returns a boolean if a field has been set.

### SetCommitNil

`func (o *PluginSource) SetCommitNil(b bool)`

 SetCommitNil sets the value for Commit to be an explicit nil

### UnsetCommit
`func (o *PluginSource) UnsetCommit()`

UnsetCommit ensures that no value is present for Commit, not even an explicit nil
### GetKind

`func (o *PluginSource) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *PluginSource) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *PluginSource) SetKind(v string)`

SetKind sets Kind field to given value.


### GetPath

`func (o *PluginSource) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *PluginSource) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *PluginSource) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *PluginSource) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetRef

`func (o *PluginSource) GetRef() string`

GetRef returns the Ref field if non-nil, zero value otherwise.

### GetRefOk

`func (o *PluginSource) GetRefOk() (*string, bool)`

GetRefOk returns a tuple with the Ref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRef

`func (o *PluginSource) SetRef(v string)`

SetRef sets Ref field to given value.

### HasRef

`func (o *PluginSource) HasRef() bool`

HasRef returns a boolean if a field has been set.

### SetRefNil

`func (o *PluginSource) SetRefNil(b bool)`

 SetRefNil sets the value for Ref to be an explicit nil

### UnsetRef
`func (o *PluginSource) UnsetRef()`

UnsetRef ensures that no value is present for Ref, not even an explicit nil
### GetRepository

`func (o *PluginSource) GetRepository() string`

GetRepository returns the Repository field if non-nil, zero value otherwise.

### GetRepositoryOk

`func (o *PluginSource) GetRepositoryOk() (*string, bool)`

GetRepositoryOk returns a tuple with the Repository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepository

`func (o *PluginSource) SetRepository(v string)`

SetRepository sets Repository field to given value.

### HasRepository

`func (o *PluginSource) HasRepository() bool`

HasRepository returns a boolean if a field has been set.

### SetRepositoryNil

`func (o *PluginSource) SetRepositoryNil(b bool)`

 SetRepositoryNil sets the value for Repository to be an explicit nil

### UnsetRepository
`func (o *PluginSource) UnsetRepository()`

UnsetRepository ensures that no value is present for Repository, not even an explicit nil
### GetSubdirectory

`func (o *PluginSource) GetSubdirectory() string`

GetSubdirectory returns the Subdirectory field if non-nil, zero value otherwise.

### GetSubdirectoryOk

`func (o *PluginSource) GetSubdirectoryOk() (*string, bool)`

GetSubdirectoryOk returns a tuple with the Subdirectory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubdirectory

`func (o *PluginSource) SetSubdirectory(v string)`

SetSubdirectory sets Subdirectory field to given value.

### HasSubdirectory

`func (o *PluginSource) HasSubdirectory() bool`

HasSubdirectory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


