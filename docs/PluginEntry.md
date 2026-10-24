# PluginEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Active** | Pointer to **bool** |  | [optional] [default to false]
**Calls** | Pointer to **int32** |  | [optional] [default to 0]
**Error** | Pointer to **NullableString** |  | [optional] 
**Failures** | Pointer to **int32** |  | [optional] [default to 0]
**Generation** | Pointer to **NullableString** |  | [optional] 
**Id** | **string** |  | 
**Installed** | Pointer to **bool** |  | [optional] [default to false]
**LoadedAt** | Pointer to **NullableFloat32** |  | [optional] 
**Manifest** | Pointer to [**NullablePluginManifest**](PluginManifest.md) |  | [optional] 
**Options** | Pointer to [**NullablePluginOptions**](PluginOptions.md) |  | [optional] 
**Source** | [**PluginSource**](PluginSource.md) |  | 

## Methods

### NewPluginEntry

`func NewPluginEntry(id string, source PluginSource, ) *PluginEntry`

NewPluginEntry instantiates a new PluginEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginEntryWithDefaults

`func NewPluginEntryWithDefaults() *PluginEntry`

NewPluginEntryWithDefaults instantiates a new PluginEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *PluginEntry) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *PluginEntry) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *PluginEntry) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *PluginEntry) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetCalls

`func (o *PluginEntry) GetCalls() int32`

GetCalls returns the Calls field if non-nil, zero value otherwise.

### GetCallsOk

`func (o *PluginEntry) GetCallsOk() (*int32, bool)`

GetCallsOk returns a tuple with the Calls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalls

`func (o *PluginEntry) SetCalls(v int32)`

SetCalls sets Calls field to given value.

### HasCalls

`func (o *PluginEntry) HasCalls() bool`

HasCalls returns a boolean if a field has been set.

### GetError

`func (o *PluginEntry) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PluginEntry) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PluginEntry) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *PluginEntry) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *PluginEntry) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *PluginEntry) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFailures

`func (o *PluginEntry) GetFailures() int32`

GetFailures returns the Failures field if non-nil, zero value otherwise.

### GetFailuresOk

`func (o *PluginEntry) GetFailuresOk() (*int32, bool)`

GetFailuresOk returns a tuple with the Failures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailures

`func (o *PluginEntry) SetFailures(v int32)`

SetFailures sets Failures field to given value.

### HasFailures

`func (o *PluginEntry) HasFailures() bool`

HasFailures returns a boolean if a field has been set.

### GetGeneration

`func (o *PluginEntry) GetGeneration() string`

GetGeneration returns the Generation field if non-nil, zero value otherwise.

### GetGenerationOk

`func (o *PluginEntry) GetGenerationOk() (*string, bool)`

GetGenerationOk returns a tuple with the Generation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneration

`func (o *PluginEntry) SetGeneration(v string)`

SetGeneration sets Generation field to given value.

### HasGeneration

`func (o *PluginEntry) HasGeneration() bool`

HasGeneration returns a boolean if a field has been set.

### SetGenerationNil

`func (o *PluginEntry) SetGenerationNil(b bool)`

 SetGenerationNil sets the value for Generation to be an explicit nil

### UnsetGeneration
`func (o *PluginEntry) UnsetGeneration()`

UnsetGeneration ensures that no value is present for Generation, not even an explicit nil
### GetId

`func (o *PluginEntry) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PluginEntry) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PluginEntry) SetId(v string)`

SetId sets Id field to given value.


### GetInstalled

`func (o *PluginEntry) GetInstalled() bool`

GetInstalled returns the Installed field if non-nil, zero value otherwise.

### GetInstalledOk

`func (o *PluginEntry) GetInstalledOk() (*bool, bool)`

GetInstalledOk returns a tuple with the Installed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstalled

`func (o *PluginEntry) SetInstalled(v bool)`

SetInstalled sets Installed field to given value.

### HasInstalled

`func (o *PluginEntry) HasInstalled() bool`

HasInstalled returns a boolean if a field has been set.

### GetLoadedAt

`func (o *PluginEntry) GetLoadedAt() float32`

GetLoadedAt returns the LoadedAt field if non-nil, zero value otherwise.

### GetLoadedAtOk

`func (o *PluginEntry) GetLoadedAtOk() (*float32, bool)`

GetLoadedAtOk returns a tuple with the LoadedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadedAt

`func (o *PluginEntry) SetLoadedAt(v float32)`

SetLoadedAt sets LoadedAt field to given value.

### HasLoadedAt

`func (o *PluginEntry) HasLoadedAt() bool`

HasLoadedAt returns a boolean if a field has been set.

### SetLoadedAtNil

`func (o *PluginEntry) SetLoadedAtNil(b bool)`

 SetLoadedAtNil sets the value for LoadedAt to be an explicit nil

### UnsetLoadedAt
`func (o *PluginEntry) UnsetLoadedAt()`

UnsetLoadedAt ensures that no value is present for LoadedAt, not even an explicit nil
### GetManifest

`func (o *PluginEntry) GetManifest() PluginManifest`

GetManifest returns the Manifest field if non-nil, zero value otherwise.

### GetManifestOk

`func (o *PluginEntry) GetManifestOk() (*PluginManifest, bool)`

GetManifestOk returns a tuple with the Manifest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifest

`func (o *PluginEntry) SetManifest(v PluginManifest)`

SetManifest sets Manifest field to given value.

### HasManifest

`func (o *PluginEntry) HasManifest() bool`

HasManifest returns a boolean if a field has been set.

### SetManifestNil

`func (o *PluginEntry) SetManifestNil(b bool)`

 SetManifestNil sets the value for Manifest to be an explicit nil

### UnsetManifest
`func (o *PluginEntry) UnsetManifest()`

UnsetManifest ensures that no value is present for Manifest, not even an explicit nil
### GetOptions

`func (o *PluginEntry) GetOptions() PluginOptions`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *PluginEntry) GetOptionsOk() (*PluginOptions, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *PluginEntry) SetOptions(v PluginOptions)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *PluginEntry) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### SetOptionsNil

`func (o *PluginEntry) SetOptionsNil(b bool)`

 SetOptionsNil sets the value for Options to be an explicit nil

### UnsetOptions
`func (o *PluginEntry) UnsetOptions()`

UnsetOptions ensures that no value is present for Options, not even an explicit nil
### GetSource

`func (o *PluginEntry) GetSource() PluginSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *PluginEntry) GetSourceOk() (*PluginSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *PluginEntry) SetSource(v PluginSource)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


