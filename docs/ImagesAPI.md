# \ImagesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateImage**](ImagesAPI.md#CreateImage) | **Post** /v1/images | Create an image task
[**GetImage**](ImagesAPI.md#GetImage) | **Get** /v1/images/{image_id} | Retrieve an image task



## CreateImage

> ImageTaskResponse CreateImage(ctx).ImageRequest(imageRequest).IdempotencyKey(idempotencyKey).Execute()

Create an image task

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
	imageRequest := *openapiclient.NewImageRequest([]openapiclient.InputInner{openapiclient.Input_inner{ImageInput: openapiclient.NewImageInput("Type_example", "Uri_example")}}, "Model_example") // ImageRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.CreateImage(context.Background()).ImageRequest(imageRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.CreateImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateImage`: ImageTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.CreateImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **imageRequest** | [**ImageRequest**](ImageRequest.md) |  | 
 **idempotencyKey** | **string** | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. | 

### Return type

[**ImageTaskResponse**](ImageTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetImage

> ImageTaskResponse GetImage(ctx, imageId).IfNoneMatch(ifNoneMatch).Execute()

Retrieve an image task

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
	imageId := "imageId_example" // string | Opaque image task id.
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImagesAPI.GetImage(context.Background(), imageId).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImagesAPI.GetImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetImage`: ImageTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `ImagesAPI.GetImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**imageId** | **string** | Opaque image task id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**ImageTaskResponse**](ImageTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

