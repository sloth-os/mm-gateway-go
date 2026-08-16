# \MetaAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetHealth**](MetaAPI.md#GetHealth) | **Get** /health | Health
[**GetHealth_0**](MetaAPI.md#GetHealth_0) | **Get** /health | Health
[**GetMetrics**](MetaAPI.md#GetMetrics) | **Get** /metrics | Metrics
[**GetMetrics_0**](MetaAPI.md#GetMetrics_0) | **Get** /metrics | Metrics
[**ListModels**](MetaAPI.md#ListModels) | **Get** /v1/models | List Models
[**ListModels_0**](MetaAPI.md#ListModels_0) | **Get** /v1/models | List Models



## GetHealth

> HealthResponse GetHealth(ctx).Execute()

Health

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sloth-os/mm-gateway-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetaAPI.GetHealth(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetaAPI.GetHealth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHealth`: HealthResponse
	fmt.Fprintf(os.Stdout, "Response from `MetaAPI.GetHealth`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetHealthRequest struct via the builder pattern


### Return type

[**HealthResponse**](HealthResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetHealth_0

> HealthResponse GetHealth_0(ctx).Execute()

Health

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sloth-os/mm-gateway-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetaAPI.GetHealth_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetaAPI.GetHealth_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHealth_0`: HealthResponse
	fmt.Fprintf(os.Stdout, "Response from `MetaAPI.GetHealth_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetHealth_1Request struct via the builder pattern


### Return type

[**HealthResponse**](HealthResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMetrics

> string GetMetrics(ctx).Execute()

Metrics

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sloth-os/mm-gateway-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetaAPI.GetMetrics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetaAPI.GetMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMetrics`: string
	fmt.Fprintf(os.Stdout, "Response from `MetaAPI.GetMetrics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMetricsRequest struct via the builder pattern


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMetrics_0

> string GetMetrics_0(ctx).Execute()

Metrics

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sloth-os/mm-gateway-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetaAPI.GetMetrics_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetaAPI.GetMetrics_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMetrics_0`: string
	fmt.Fprintf(os.Stdout, "Response from `MetaAPI.GetMetrics_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMetrics_2Request struct via the builder pattern


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListModels

> ModelListResponse ListModels(ctx).Modality(modality).Authorization(authorization).XRequestId(xRequestId).IfNoneMatch(ifNoneMatch).Execute()

List Models

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sloth-os/mm-gateway-go"
)

func main() {
	modality := "modality_example" // string | Filter models by output modality. (optional)
	authorization := "authorization_example" // string | Bearer token: \"Bearer <api-key>\". (optional)
	xRequestId := "xRequestId_example" // string | Client-supplied request id (echoed back). (optional)
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetaAPI.ListModels(context.Background()).Modality(modality).Authorization(authorization).XRequestId(xRequestId).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetaAPI.ListModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListModels`: ModelListResponse
	fmt.Fprintf(os.Stdout, "Response from `MetaAPI.ListModels`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **modality** | **string** | Filter models by output modality. | 
 **authorization** | **string** | Bearer token: \&quot;Bearer &lt;api-key&gt;\&quot;. | 
 **xRequestId** | **string** | Client-supplied request id (echoed back). | 
 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**ModelListResponse**](ModelListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListModels_0

> ModelListResponse ListModels_0(ctx).Modality(modality).Authorization(authorization).XRequestId(xRequestId).IfNoneMatch(ifNoneMatch).Execute()

List Models

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sloth-os/mm-gateway-go"
)

func main() {
	modality := "modality_example" // string | Filter models by output modality. (optional)
	authorization := "authorization_example" // string | Bearer token: \"Bearer <api-key>\". (optional)
	xRequestId := "xRequestId_example" // string | Client-supplied request id (echoed back). (optional)
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetaAPI.ListModels_0(context.Background()).Modality(modality).Authorization(authorization).XRequestId(xRequestId).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetaAPI.ListModels_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListModels_0`: ModelListResponse
	fmt.Fprintf(os.Stdout, "Response from `MetaAPI.ListModels_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListModels_3Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **modality** | **string** | Filter models by output modality. | 
 **authorization** | **string** | Bearer token: \&quot;Bearer &lt;api-key&gt;\&quot;. | 
 **xRequestId** | **string** | Client-supplied request id (echoed back). | 
 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**ModelListResponse**](ModelListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

