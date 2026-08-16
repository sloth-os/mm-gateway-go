# RoutingDirective

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Profile** | **string** | Gateway-defined routing profile, such as &#x60;quality&#x60;, &#x60;fast&#x60;, or &#x60;eu&#x60;. It never names a provider or backend. | 

## Methods

### NewRoutingDirective

`func NewRoutingDirective(profile string, ) *RoutingDirective`

NewRoutingDirective instantiates a new RoutingDirective object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingDirectiveWithDefaults

`func NewRoutingDirectiveWithDefaults() *RoutingDirective`

NewRoutingDirectiveWithDefaults instantiates a new RoutingDirective object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProfile

`func (o *RoutingDirective) GetProfile() string`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *RoutingDirective) GetProfileOk() (*string, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *RoutingDirective) SetProfile(v string)`

SetProfile sets Profile field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


