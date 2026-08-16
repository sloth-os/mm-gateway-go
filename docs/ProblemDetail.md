# ProblemDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | Stable machine-readable gateway error code. | 
**Detail** | **string** | Human-readable detail for this occurrence. | 
**Errors** | Pointer to **[]map[string]interface{}** | Field-level validation errors, when applicable. | [optional] 
**Instance** | Pointer to **NullableString** | Previously returned ETag; unchanged resources return 304. | [optional] 
**RequestId** | Pointer to **NullableString** | Previously returned ETag; unchanged resources return 304. | [optional] 
**Status** | **int32** | HTTP response status code. | 
**Title** | **string** | Short, stable summary of the problem type. | 
**Type** | **string** | URI identifying the problem type. | 

## Methods

### NewProblemDetail

`func NewProblemDetail(code string, detail string, status int32, title string, type_ string, ) *ProblemDetail`

NewProblemDetail instantiates a new ProblemDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProblemDetailWithDefaults

`func NewProblemDetailWithDefaults() *ProblemDetail`

NewProblemDetailWithDefaults instantiates a new ProblemDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ProblemDetail) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ProblemDetail) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ProblemDetail) SetCode(v string)`

SetCode sets Code field to given value.


### GetDetail

`func (o *ProblemDetail) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *ProblemDetail) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *ProblemDetail) SetDetail(v string)`

SetDetail sets Detail field to given value.


### GetErrors

`func (o *ProblemDetail) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ProblemDetail) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ProblemDetail) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ProblemDetail) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### SetErrorsNil

`func (o *ProblemDetail) SetErrorsNil(b bool)`

 SetErrorsNil sets the value for Errors to be an explicit nil

### UnsetErrors
`func (o *ProblemDetail) UnsetErrors()`

UnsetErrors ensures that no value is present for Errors, not even an explicit nil
### GetInstance

`func (o *ProblemDetail) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *ProblemDetail) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *ProblemDetail) SetInstance(v string)`

SetInstance sets Instance field to given value.

### HasInstance

`func (o *ProblemDetail) HasInstance() bool`

HasInstance returns a boolean if a field has been set.

### SetInstanceNil

`func (o *ProblemDetail) SetInstanceNil(b bool)`

 SetInstanceNil sets the value for Instance to be an explicit nil

### UnsetInstance
`func (o *ProblemDetail) UnsetInstance()`

UnsetInstance ensures that no value is present for Instance, not even an explicit nil
### GetRequestId

`func (o *ProblemDetail) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ProblemDetail) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ProblemDetail) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ProblemDetail) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### SetRequestIdNil

`func (o *ProblemDetail) SetRequestIdNil(b bool)`

 SetRequestIdNil sets the value for RequestId to be an explicit nil

### UnsetRequestId
`func (o *ProblemDetail) UnsetRequestId()`

UnsetRequestId ensures that no value is present for RequestId, not even an explicit nil
### GetStatus

`func (o *ProblemDetail) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProblemDetail) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProblemDetail) SetStatus(v int32)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *ProblemDetail) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ProblemDetail) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ProblemDetail) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetType

`func (o *ProblemDetail) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProblemDetail) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProblemDetail) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


