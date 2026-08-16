# \MusicAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMusic**](MusicAPI.md#CreateMusic) | **Post** /v1/music | Create a music task
[**GetMusic**](MusicAPI.md#GetMusic) | **Get** /v1/music/{music_id} | Retrieve a music task



## CreateMusic

> MusicTaskResponse CreateMusic(ctx).MusicRequest(musicRequest).IdempotencyKey(idempotencyKey).Execute()

Create a music task

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
	musicRequest := *openapiclient.NewMusicRequest([]openapiclient.InputInner1{openapiclient.Input_inner_1{LyricsInput: openapiclient.NewLyricsInput("Text_example", "Type_example")}}) // MusicRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MusicAPI.CreateMusic(context.Background()).MusicRequest(musicRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MusicAPI.CreateMusic``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMusic`: MusicTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `MusicAPI.CreateMusic`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateMusicRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **musicRequest** | [**MusicRequest**](MusicRequest.md) |  | 
 **idempotencyKey** | **string** | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. | 

### Return type

[**MusicTaskResponse**](MusicTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMusic

> MusicTaskResponse GetMusic(ctx, musicId).IfNoneMatch(ifNoneMatch).Execute()

Retrieve a music task

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
	musicId := "musicId_example" // string | Opaque music task id.
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MusicAPI.GetMusic(context.Background(), musicId).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MusicAPI.GetMusic``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMusic`: MusicTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `MusicAPI.GetMusic`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**musicId** | **string** | Opaque music task id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMusicRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**MusicTaskResponse**](MusicTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

