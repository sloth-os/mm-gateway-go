# PluginManifest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiVersion** | Pointer to **string** |  | [optional] [default to "1"]
**Author** | Pointer to **string** |  | [optional] [default to ""]
**BackendTypes** | Pointer to **[]string** | Backend types for automatic authentication hooks; * matches all. | [optional] 
**DefaultConfig** | Pointer to **map[string]interface{}** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] [default to ""]
**Homepage** | Pointer to **NullableString** |  | [optional] 
**Hooks** | Pointer to **[]string** |  | [optional] 
**Id** | **string** |  | 
**Methods** | Pointer to **[]string** |  | [optional] 
**Name** | **string** |  | 
**Paths** | Pointer to **[]string** |  | [optional] 
**Providers** | Pointer to **[]string** | New provider types exported by this plugin. | [optional] 
**ResponseBody** | Pointer to **string** |  | [optional] [default to "none"]
**Version** | **string** |  | 

## Methods

### NewPluginManifest

`func NewPluginManifest(id string, name string, version string, ) *PluginManifest`

NewPluginManifest instantiates a new PluginManifest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginManifestWithDefaults

`func NewPluginManifestWithDefaults() *PluginManifest`

NewPluginManifestWithDefaults instantiates a new PluginManifest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiVersion

`func (o *PluginManifest) GetApiVersion() string`

GetApiVersion returns the ApiVersion field if non-nil, zero value otherwise.

### GetApiVersionOk

`func (o *PluginManifest) GetApiVersionOk() (*string, bool)`

GetApiVersionOk returns a tuple with the ApiVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiVersion

`func (o *PluginManifest) SetApiVersion(v string)`

SetApiVersion sets ApiVersion field to given value.

### HasApiVersion

`func (o *PluginManifest) HasApiVersion() bool`

HasApiVersion returns a boolean if a field has been set.

### GetAuthor

`func (o *PluginManifest) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *PluginManifest) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *PluginManifest) SetAuthor(v string)`

SetAuthor sets Author field to given value.

### HasAuthor

`func (o *PluginManifest) HasAuthor() bool`

HasAuthor returns a boolean if a field has been set.

### GetBackendTypes

`func (o *PluginManifest) GetBackendTypes() []string`

GetBackendTypes returns the BackendTypes field if non-nil, zero value otherwise.

### GetBackendTypesOk

`func (o *PluginManifest) GetBackendTypesOk() (*[]string, bool)`

GetBackendTypesOk returns a tuple with the BackendTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackendTypes

`func (o *PluginManifest) SetBackendTypes(v []string)`

SetBackendTypes sets BackendTypes field to given value.

### HasBackendTypes

`func (o *PluginManifest) HasBackendTypes() bool`

HasBackendTypes returns a boolean if a field has been set.

### GetDefaultConfig

`func (o *PluginManifest) GetDefaultConfig() map[string]interface{}`

GetDefaultConfig returns the DefaultConfig field if non-nil, zero value otherwise.

### GetDefaultConfigOk

`func (o *PluginManifest) GetDefaultConfigOk() (*map[string]interface{}, bool)`

GetDefaultConfigOk returns a tuple with the DefaultConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultConfig

`func (o *PluginManifest) SetDefaultConfig(v map[string]interface{})`

SetDefaultConfig sets DefaultConfig field to given value.

### HasDefaultConfig

`func (o *PluginManifest) HasDefaultConfig() bool`

HasDefaultConfig returns a boolean if a field has been set.

### GetDescription

`func (o *PluginManifest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginManifest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginManifest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PluginManifest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetHomepage

`func (o *PluginManifest) GetHomepage() string`

GetHomepage returns the Homepage field if non-nil, zero value otherwise.

### GetHomepageOk

`func (o *PluginManifest) GetHomepageOk() (*string, bool)`

GetHomepageOk returns a tuple with the Homepage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomepage

`func (o *PluginManifest) SetHomepage(v string)`

SetHomepage sets Homepage field to given value.

### HasHomepage

`func (o *PluginManifest) HasHomepage() bool`

HasHomepage returns a boolean if a field has been set.

### SetHomepageNil

`func (o *PluginManifest) SetHomepageNil(b bool)`

 SetHomepageNil sets the value for Homepage to be an explicit nil

### UnsetHomepage
`func (o *PluginManifest) UnsetHomepage()`

UnsetHomepage ensures that no value is present for Homepage, not even an explicit nil
### GetHooks

`func (o *PluginManifest) GetHooks() []string`

GetHooks returns the Hooks field if non-nil, zero value otherwise.

### GetHooksOk

`func (o *PluginManifest) GetHooksOk() (*[]string, bool)`

GetHooksOk returns a tuple with the Hooks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHooks

`func (o *PluginManifest) SetHooks(v []string)`

SetHooks sets Hooks field to given value.

### HasHooks

`func (o *PluginManifest) HasHooks() bool`

HasHooks returns a boolean if a field has been set.

### GetId

`func (o *PluginManifest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PluginManifest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PluginManifest) SetId(v string)`

SetId sets Id field to given value.


### GetMethods

`func (o *PluginManifest) GetMethods() []string`

GetMethods returns the Methods field if non-nil, zero value otherwise.

### GetMethodsOk

`func (o *PluginManifest) GetMethodsOk() (*[]string, bool)`

GetMethodsOk returns a tuple with the Methods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethods

`func (o *PluginManifest) SetMethods(v []string)`

SetMethods sets Methods field to given value.

### HasMethods

`func (o *PluginManifest) HasMethods() bool`

HasMethods returns a boolean if a field has been set.

### GetName

`func (o *PluginManifest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PluginManifest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PluginManifest) SetName(v string)`

SetName sets Name field to given value.


### GetPaths

`func (o *PluginManifest) GetPaths() []string`

GetPaths returns the Paths field if non-nil, zero value otherwise.

### GetPathsOk

`func (o *PluginManifest) GetPathsOk() (*[]string, bool)`

GetPathsOk returns a tuple with the Paths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaths

`func (o *PluginManifest) SetPaths(v []string)`

SetPaths sets Paths field to given value.

### HasPaths

`func (o *PluginManifest) HasPaths() bool`

HasPaths returns a boolean if a field has been set.

### GetProviders

`func (o *PluginManifest) GetProviders() []string`

GetProviders returns the Providers field if non-nil, zero value otherwise.

### GetProvidersOk

`func (o *PluginManifest) GetProvidersOk() (*[]string, bool)`

GetProvidersOk returns a tuple with the Providers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviders

`func (o *PluginManifest) SetProviders(v []string)`

SetProviders sets Providers field to given value.

### HasProviders

`func (o *PluginManifest) HasProviders() bool`

HasProviders returns a boolean if a field has been set.

### GetResponseBody

`func (o *PluginManifest) GetResponseBody() string`

GetResponseBody returns the ResponseBody field if non-nil, zero value otherwise.

### GetResponseBodyOk

`func (o *PluginManifest) GetResponseBodyOk() (*string, bool)`

GetResponseBodyOk returns a tuple with the ResponseBody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseBody

`func (o *PluginManifest) SetResponseBody(v string)`

SetResponseBody sets ResponseBody field to given value.

### HasResponseBody

`func (o *PluginManifest) HasResponseBody() bool`

HasResponseBody returns a boolean if a field has been set.

### GetVersion

`func (o *PluginManifest) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *PluginManifest) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *PluginManifest) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


