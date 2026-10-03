# VoiceListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]VoiceResponse**](VoiceResponse.md) |  | 
**Object** | Pointer to **string** |  | [optional] [default to "list"]

## Methods

### NewVoiceListResponse

`func NewVoiceListResponse(data []VoiceResponse, ) *VoiceListResponse`

NewVoiceListResponse instantiates a new VoiceListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoiceListResponseWithDefaults

`func NewVoiceListResponseWithDefaults() *VoiceListResponse`

NewVoiceListResponseWithDefaults instantiates a new VoiceListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *VoiceListResponse) GetData() []VoiceResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *VoiceListResponse) GetDataOk() (*[]VoiceResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *VoiceListResponse) SetData(v []VoiceResponse)`

SetData sets Data field to given value.


### GetObject

`func (o *VoiceListResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *VoiceListResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *VoiceListResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *VoiceListResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


