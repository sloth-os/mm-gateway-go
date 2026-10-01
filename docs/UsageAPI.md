# \UsageAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetUsage**](UsageAPI.md#GetUsage) | **Get** /v1/usage | Spend and budgets of the authenticated key



## GetUsage

> UsageResponse GetUsage(ctx).Scope(scope).Execute()

Spend and budgets of the authenticated key

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
	scope := "scope_example" // string | Report only this budget scope. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsageAPI.GetUsage(context.Background()).Scope(scope).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsageAPI.GetUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsage`: UsageResponse
	fmt.Fprintf(os.Stdout, "Response from `UsageAPI.GetUsage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **scope** | **string** | Report only this budget scope. | 

### Return type

[**UsageResponse**](UsageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

