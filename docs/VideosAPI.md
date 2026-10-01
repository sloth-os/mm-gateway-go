# \VideosAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateVideo**](VideosAPI.md#CreateVideo) | **Post** /v1/videos | Create a video task
[**EstimateVideo**](VideosAPI.md#EstimateVideo) | **Post** /v1/videos/estimate | Estimate a video request
[**GetVideo**](VideosAPI.md#GetVideo) | **Get** /v1/videos/{video_id} | Retrieve a video task



## CreateVideo

> VideoTaskResponse CreateVideo(ctx).VideoRequest(videoRequest).IdempotencyKey(idempotencyKey).Execute()

Create a video task

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
	videoRequest := *openapiclient.NewVideoRequest([]openapiclient.InputInner2{openapiclient.Input_inner_2{TextInput: openapiclient.NewTextInput("Text_example", "Type_example")}}) // VideoRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.CreateVideo(context.Background()).VideoRequest(videoRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.CreateVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateVideo`: VideoTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.CreateVideo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **videoRequest** | [**VideoRequest**](VideoRequest.md) |  | 
 **idempotencyKey** | **string** | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. | 

### Return type

[**VideoTaskResponse**](VideoTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EstimateVideo

> EstimateResponse EstimateVideo(ctx).VideoRequest(videoRequest).Execute()

Estimate a video request

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
	videoRequest := *openapiclient.NewVideoRequest([]openapiclient.InputInner2{openapiclient.Input_inner_2{TextInput: openapiclient.NewTextInput("Text_example", "Type_example")}}) // VideoRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.EstimateVideo(context.Background()).VideoRequest(videoRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.EstimateVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EstimateVideo`: EstimateResponse
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.EstimateVideo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEstimateVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **videoRequest** | [**VideoRequest**](VideoRequest.md) |  | 

### Return type

[**EstimateResponse**](EstimateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVideo

> VideoTaskResponse GetVideo(ctx, videoId).IfNoneMatch(ifNoneMatch).Execute()

Retrieve a video task

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
	videoId := "videoId_example" // string | Opaque video task id.
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VideosAPI.GetVideo(context.Background(), videoId).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VideosAPI.GetVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVideo`: VideoTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `VideosAPI.GetVideo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**videoId** | **string** | Opaque video task id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**VideoTaskResponse**](VideoTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

