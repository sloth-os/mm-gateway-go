# \ProxyAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProxyRequestDelete**](ProxyAPI.md#ProxyRequestDelete) | **Delete** /proxy/{domain}/{path} | Forward a request through a domain-matched proxy
[**ProxyRequestGet**](ProxyAPI.md#ProxyRequestGet) | **Get** /proxy/{domain}/{path} | Forward a request through a domain-matched proxy
[**ProxyRequestHead**](ProxyAPI.md#ProxyRequestHead) | **Head** /proxy/{domain}/{path} | Forward a request through a domain-matched proxy
[**ProxyRequestOptions**](ProxyAPI.md#ProxyRequestOptions) | **Options** /proxy/{domain}/{path} | Forward a request through a domain-matched proxy
[**ProxyRequestPatch**](ProxyAPI.md#ProxyRequestPatch) | **Patch** /proxy/{domain}/{path} | Forward a request through a domain-matched proxy
[**ProxyRequestPost**](ProxyAPI.md#ProxyRequestPost) | **Post** /proxy/{domain}/{path} | Forward a request through a domain-matched proxy
[**ProxyRequestPut**](ProxyAPI.md#ProxyRequestPut) | **Put** /proxy/{domain}/{path} | Forward a request through a domain-matched proxy



## ProxyRequestDelete

> ProxyRequestDelete(ctx, domain, path).Execute()

Forward a request through a domain-matched proxy



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
	domain := "domain_example" // string | Configured proxy domain (the upstream host segment selecting the proxy).
	path := "path_example" // string | Path forwarded to the upstream root URL.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProxyAPI.ProxyRequestDelete(context.Background(), domain, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProxyAPI.ProxyRequestDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Configured proxy domain (the upstream host segment selecting the proxy). | 
**path** | **string** | Path forwarded to the upstream root URL. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProxyRequestDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProxyRequestGet

> ProxyRequestGet(ctx, domain, path).Execute()

Forward a request through a domain-matched proxy



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
	domain := "domain_example" // string | Configured proxy domain (the upstream host segment selecting the proxy).
	path := "path_example" // string | Path forwarded to the upstream root URL.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProxyAPI.ProxyRequestGet(context.Background(), domain, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProxyAPI.ProxyRequestGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Configured proxy domain (the upstream host segment selecting the proxy). | 
**path** | **string** | Path forwarded to the upstream root URL. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProxyRequestGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProxyRequestHead

> ProxyRequestHead(ctx, domain, path).Execute()

Forward a request through a domain-matched proxy



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
	domain := "domain_example" // string | Configured proxy domain (the upstream host segment selecting the proxy).
	path := "path_example" // string | Path forwarded to the upstream root URL.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProxyAPI.ProxyRequestHead(context.Background(), domain, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProxyAPI.ProxyRequestHead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Configured proxy domain (the upstream host segment selecting the proxy). | 
**path** | **string** | Path forwarded to the upstream root URL. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProxyRequestHeadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProxyRequestOptions

> ProxyRequestOptions(ctx, domain, path).Execute()

Forward a request through a domain-matched proxy



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
	domain := "domain_example" // string | Configured proxy domain (the upstream host segment selecting the proxy).
	path := "path_example" // string | Path forwarded to the upstream root URL.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProxyAPI.ProxyRequestOptions(context.Background(), domain, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProxyAPI.ProxyRequestOptions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Configured proxy domain (the upstream host segment selecting the proxy). | 
**path** | **string** | Path forwarded to the upstream root URL. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProxyRequestOptionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProxyRequestPatch

> ProxyRequestPatch(ctx, domain, path).Execute()

Forward a request through a domain-matched proxy



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
	domain := "domain_example" // string | Configured proxy domain (the upstream host segment selecting the proxy).
	path := "path_example" // string | Path forwarded to the upstream root URL.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProxyAPI.ProxyRequestPatch(context.Background(), domain, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProxyAPI.ProxyRequestPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Configured proxy domain (the upstream host segment selecting the proxy). | 
**path** | **string** | Path forwarded to the upstream root URL. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProxyRequestPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProxyRequestPost

> ProxyRequestPost(ctx, domain, path).Execute()

Forward a request through a domain-matched proxy



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
	domain := "domain_example" // string | Configured proxy domain (the upstream host segment selecting the proxy).
	path := "path_example" // string | Path forwarded to the upstream root URL.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProxyAPI.ProxyRequestPost(context.Background(), domain, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProxyAPI.ProxyRequestPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Configured proxy domain (the upstream host segment selecting the proxy). | 
**path** | **string** | Path forwarded to the upstream root URL. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProxyRequestPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProxyRequestPut

> ProxyRequestPut(ctx, domain, path).Execute()

Forward a request through a domain-matched proxy



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
	domain := "domain_example" // string | Configured proxy domain (the upstream host segment selecting the proxy).
	path := "path_example" // string | Path forwarded to the upstream root URL.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProxyAPI.ProxyRequestPut(context.Background(), domain, path).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProxyAPI.ProxyRequestPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Configured proxy domain (the upstream host segment selecting the proxy). | 
**path** | **string** | Path forwarded to the upstream root URL. | 

### Other Parameters

Other parameters are passed through a pointer to a apiProxyRequestPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

