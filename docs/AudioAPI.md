# \AudioAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAudio**](AudioAPI.md#CreateAudio) | **Post** /v1/audio | Create a speech task
[**CreateVoice**](AudioAPI.md#CreateVoice) | **Post** /v1/voices | Clone a reusable voice
[**EstimateAudio**](AudioAPI.md#EstimateAudio) | **Post** /v1/audio/estimate | Estimate a speech request
[**EstimateVoice**](AudioAPI.md#EstimateVoice) | **Post** /v1/voices/estimate | Estimate voice cloning
[**GetAudio**](AudioAPI.md#GetAudio) | **Get** /v1/audio/{audio_id} | Retrieve a speech task
[**GetVoice**](AudioAPI.md#GetVoice) | **Get** /v1/voices/{voice_id} | Retrieve a voice or clone task
[**ListVoices**](AudioAPI.md#ListVoices) | **Get** /v1/voices | List usable voice presets and owned clones



## CreateAudio

> AudioTaskResponse CreateAudio(ctx).AudioRequest(audioRequest).IdempotencyKey(idempotencyKey).Execute()

Create a speech task

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
	audioRequest := *openapiclient.NewAudioRequest([]openapiclient.TextInput{*openapiclient.NewTextInput("Text_example", "Type_example")}) // AudioRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AudioAPI.CreateAudio(context.Background()).AudioRequest(audioRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AudioAPI.CreateAudio``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAudio`: AudioTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `AudioAPI.CreateAudio`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAudioRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **audioRequest** | [**AudioRequest**](AudioRequest.md) |  | 
 **idempotencyKey** | **string** | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. | 

### Return type

[**AudioTaskResponse**](AudioTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateVoice

> VoiceResponse CreateVoice(ctx).VoiceCloneRequest(voiceCloneRequest).IdempotencyKey(idempotencyKey).Execute()

Clone a reusable voice

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
	voiceCloneRequest := *openapiclient.NewVoiceCloneRequest(*openapiclient.NewVoiceConsent(false), []openapiclient.VoiceSampleInput{*openapiclient.NewVoiceSampleInput("Type_example", "Uri_example")}, *openapiclient.NewVoiceParameters("Name_example")) // VoiceCloneRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AudioAPI.CreateVoice(context.Background()).VoiceCloneRequest(voiceCloneRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AudioAPI.CreateVoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateVoice`: VoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AudioAPI.CreateVoice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateVoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **voiceCloneRequest** | [**VoiceCloneRequest**](VoiceCloneRequest.md) |  | 
 **idempotencyKey** | **string** | Client-generated key used to safely retry this create request. Reuse with a different body returns 409. | 

### Return type

[**VoiceResponse**](VoiceResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EstimateAudio

> EstimateResponse EstimateAudio(ctx).AudioRequest(audioRequest).Execute()

Estimate a speech request

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
	audioRequest := *openapiclient.NewAudioRequest([]openapiclient.TextInput{*openapiclient.NewTextInput("Text_example", "Type_example")}) // AudioRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AudioAPI.EstimateAudio(context.Background()).AudioRequest(audioRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AudioAPI.EstimateAudio``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EstimateAudio`: EstimateResponse
	fmt.Fprintf(os.Stdout, "Response from `AudioAPI.EstimateAudio`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEstimateAudioRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **audioRequest** | [**AudioRequest**](AudioRequest.md) |  | 

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


## EstimateVoice

> EstimateResponse EstimateVoice(ctx).VoiceCloneRequest(voiceCloneRequest).Execute()

Estimate voice cloning

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
	voiceCloneRequest := *openapiclient.NewVoiceCloneRequest(*openapiclient.NewVoiceConsent(false), []openapiclient.VoiceSampleInput{*openapiclient.NewVoiceSampleInput("Type_example", "Uri_example")}, *openapiclient.NewVoiceParameters("Name_example")) // VoiceCloneRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AudioAPI.EstimateVoice(context.Background()).VoiceCloneRequest(voiceCloneRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AudioAPI.EstimateVoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EstimateVoice`: EstimateResponse
	fmt.Fprintf(os.Stdout, "Response from `AudioAPI.EstimateVoice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEstimateVoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **voiceCloneRequest** | [**VoiceCloneRequest**](VoiceCloneRequest.md) |  | 

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


## GetAudio

> AudioTaskResponse GetAudio(ctx, audioId).IfNoneMatch(ifNoneMatch).Execute()

Retrieve a speech task

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
	audioId := "audioId_example" // string | Opaque speech task id.
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AudioAPI.GetAudio(context.Background(), audioId).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AudioAPI.GetAudio``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAudio`: AudioTaskResponse
	fmt.Fprintf(os.Stdout, "Response from `AudioAPI.GetAudio`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**audioId** | **string** | Opaque speech task id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAudioRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**AudioTaskResponse**](AudioTaskResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVoice

> VoiceResponse GetVoice(ctx, voiceId).IfNoneMatch(ifNoneMatch).Execute()

Retrieve a voice or clone task

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
	voiceId := "voiceId_example" // string | Gateway voice id.
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AudioAPI.GetVoice(context.Background(), voiceId).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AudioAPI.GetVoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVoice`: VoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AudioAPI.GetVoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**voiceId** | **string** | Gateway voice id. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**VoiceResponse**](VoiceResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListVoices

> VoiceListResponse ListVoices(ctx).IfNoneMatch(ifNoneMatch).Execute()

List usable voice presets and owned clones

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
	ifNoneMatch := "ifNoneMatch_example" // string | Previously returned ETag; unchanged resources return 304. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AudioAPI.ListVoices(context.Background()).IfNoneMatch(ifNoneMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AudioAPI.ListVoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListVoices`: VoiceListResponse
	fmt.Fprintf(os.Stdout, "Response from `AudioAPI.ListVoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListVoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ifNoneMatch** | **string** | Previously returned ETag; unchanged resources return 304. | 

### Return type

[**VoiceListResponse**](VoiceListResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

