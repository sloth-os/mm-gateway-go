# GitHubPluginInstall

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Options** | Pointer to [**PluginOptions**](PluginOptions.md) |  | [optional] 
**Ref** | Pointer to **string** | Branch, tag or commit to fetch. | [optional] [default to "HEAD"]
**Repository** | **string** | HTTPS GitHub repository URL. | 
**Subdirectory** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewGitHubPluginInstall

`func NewGitHubPluginInstall(repository string, ) *GitHubPluginInstall`

NewGitHubPluginInstall instantiates a new GitHubPluginInstall object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGitHubPluginInstallWithDefaults

`func NewGitHubPluginInstallWithDefaults() *GitHubPluginInstall`

NewGitHubPluginInstallWithDefaults instantiates a new GitHubPluginInstall object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOptions

`func (o *GitHubPluginInstall) GetOptions() PluginOptions`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *GitHubPluginInstall) GetOptionsOk() (*PluginOptions, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *GitHubPluginInstall) SetOptions(v PluginOptions)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *GitHubPluginInstall) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetRef

`func (o *GitHubPluginInstall) GetRef() string`

GetRef returns the Ref field if non-nil, zero value otherwise.

### GetRefOk

`func (o *GitHubPluginInstall) GetRefOk() (*string, bool)`

GetRefOk returns a tuple with the Ref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRef

`func (o *GitHubPluginInstall) SetRef(v string)`

SetRef sets Ref field to given value.

### HasRef

`func (o *GitHubPluginInstall) HasRef() bool`

HasRef returns a boolean if a field has been set.

### GetRepository

`func (o *GitHubPluginInstall) GetRepository() string`

GetRepository returns the Repository field if non-nil, zero value otherwise.

### GetRepositoryOk

`func (o *GitHubPluginInstall) GetRepositoryOk() (*string, bool)`

GetRepositoryOk returns a tuple with the Repository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepository

`func (o *GitHubPluginInstall) SetRepository(v string)`

SetRepository sets Repository field to given value.


### GetSubdirectory

`func (o *GitHubPluginInstall) GetSubdirectory() string`

GetSubdirectory returns the Subdirectory field if non-nil, zero value otherwise.

### GetSubdirectoryOk

`func (o *GitHubPluginInstall) GetSubdirectoryOk() (*string, bool)`

GetSubdirectoryOk returns a tuple with the Subdirectory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubdirectory

`func (o *GitHubPluginInstall) SetSubdirectory(v string)`

SetSubdirectory sets Subdirectory field to given value.

### HasSubdirectory

`func (o *GitHubPluginInstall) HasSubdirectory() bool`

HasSubdirectory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


