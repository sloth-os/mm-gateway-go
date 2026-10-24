# \ManagementAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteManagementBackend**](ManagementAPI.md#DeleteManagementBackend) | **Delete** /v1/management/backends/{name} | Delete Backend
[**DeleteManagementKey**](ManagementAPI.md#DeleteManagementKey) | **Delete** /v1/management/keys/{key_id} | Delete Key
[**DeleteManagementPlugin**](ManagementAPI.md#DeleteManagementPlugin) | **Delete** /v1/management/plugins/{plugin_id} | Delete Plugin
[**DeleteManagementProxy**](ManagementAPI.md#DeleteManagementProxy) | **Delete** /v1/management/proxies/{domain} | Delete Proxy
[**DiscoverManagementBackendModels**](ManagementAPI.md#DiscoverManagementBackendModels) | **Post** /v1/management/backends/discover-models | Discover Backend Models
[**GetManagementBuiltinModels**](ManagementAPI.md#GetManagementBuiltinModels) | **Get** /v1/management/backend-types/{provider_type}/models | Get Builtin Models
[**GetManagementConfig**](ManagementAPI.md#GetManagementConfig) | **Get** /v1/management/config | Get Config
[**GetManagementMetrics**](ManagementAPI.md#GetManagementMetrics) | **Get** /v1/management/metrics | Get Metrics
[**GetManagementPluginStore**](ManagementAPI.md#GetManagementPluginStore) | **Get** /v1/management/plugins | Get Store
[**GetManagementStatus**](ManagementAPI.md#GetManagementStatus) | **Get** /v1/management/status | Get Status
[**InstallManagementGitHubPlugin**](ManagementAPI.md#InstallManagementGitHubPlugin) | **Post** /v1/management/plugins/install | Install Github
[**ListManagementTasks**](ManagementAPI.md#ListManagementTasks) | **Get** /v1/management/tasks | List Tasks
[**ListManagementUsage**](ManagementAPI.md#ListManagementUsage) | **Get** /v1/management/usage | List Usage
[**PutManagementBackend**](ManagementAPI.md#PutManagementBackend) | **Put** /v1/management/backends/{name} | Put Backend
[**PutManagementKey**](ManagementAPI.md#PutManagementKey) | **Put** /v1/management/keys/{key_id} | Put Key
[**PutManagementPlugin**](ManagementAPI.md#PutManagementPlugin) | **Put** /v1/management/plugins/{plugin_id} | Put Plugin
[**PutManagementProxy**](ManagementAPI.md#PutManagementProxy) | **Put** /v1/management/proxies/{domain} | Put Proxy
[**ReloadManagementPlugin**](ManagementAPI.md#ReloadManagementPlugin) | **Post** /v1/management/plugins/{plugin_id}/reload | Reload Plugin
[**ReplaceManagementConfig**](ManagementAPI.md#ReplaceManagementConfig) | **Put** /v1/management/config | Replace Config
[**UpdateManagementGitHubPlugin**](ManagementAPI.md#UpdateManagementGitHubPlugin) | **Post** /v1/management/plugins/{plugin_id}/update | Update Plugin



## DeleteManagementBackend

> ManagementConfigResponse DeleteManagementBackend(ctx, name).IfMatch(ifMatch).Execute()

Delete Backend

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
	name := "name_example" // string | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.DeleteManagementBackend(context.Background(), name).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.DeleteManagementBackend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteManagementBackend`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.DeleteManagementBackend`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteManagementBackendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteManagementKey

> ManagementConfigResponse DeleteManagementKey(ctx, keyId).IfMatch(ifMatch).Execute()

Delete Key

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
	keyId := "keyId_example" // string | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.DeleteManagementKey(context.Background(), keyId).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.DeleteManagementKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteManagementKey`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.DeleteManagementKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteManagementKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteManagementPlugin

> PluginStore DeleteManagementPlugin(ctx, pluginId).IfMatch(ifMatch).Execute()

Delete Plugin



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
	pluginId := "pluginId_example" // string | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.DeleteManagementPlugin(context.Background(), pluginId).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.DeleteManagementPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteManagementPlugin`: PluginStore
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.DeleteManagementPlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**pluginId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteManagementPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**PluginStore**](PluginStore.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteManagementProxy

> ManagementConfigResponse DeleteManagementProxy(ctx, domain).IfMatch(ifMatch).Execute()

Delete Proxy

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
	domain := "domain_example" // string | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.DeleteManagementProxy(context.Background(), domain).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.DeleteManagementProxy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteManagementProxy`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.DeleteManagementProxy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteManagementProxyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscoverManagementBackendModels

> BackendModelDiscovery DiscoverManagementBackendModels(ctx).ManagedBackend(managedBackend).Execute()

Discover Backend Models



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
	managedBackend := *openapiclient.NewManagedBackend("Name_example", "Type_example") // ManagedBackend | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.DiscoverManagementBackendModels(context.Background()).ManagedBackend(managedBackend).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.DiscoverManagementBackendModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscoverManagementBackendModels`: BackendModelDiscovery
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.DiscoverManagementBackendModels`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDiscoverManagementBackendModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **managedBackend** | [**ManagedBackend**](ManagedBackend.md) |  | 

### Return type

[**BackendModelDiscovery**](BackendModelDiscovery.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagementBuiltinModels

> BackendModelCatalog GetManagementBuiltinModels(ctx, providerType).Execute()

Get Builtin Models

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
	providerType := "providerType_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.GetManagementBuiltinModels(context.Background(), providerType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.GetManagementBuiltinModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagementBuiltinModels`: BackendModelCatalog
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.GetManagementBuiltinModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**providerType** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagementBuiltinModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BackendModelCatalog**](BackendModelCatalog.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagementConfig

> ManagementConfigResponse GetManagementConfig(ctx).Execute()

Get Config

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
	resp, r, err := apiClient.ManagementAPI.GetManagementConfig(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.GetManagementConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagementConfig`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.GetManagementConfig`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagementConfigRequest struct via the builder pattern


### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagementMetrics

> ManagementMetrics GetManagementMetrics(ctx).Execute()

Get Metrics

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
	resp, r, err := apiClient.ManagementAPI.GetManagementMetrics(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.GetManagementMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagementMetrics`: ManagementMetrics
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.GetManagementMetrics`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagementMetricsRequest struct via the builder pattern


### Return type

[**ManagementMetrics**](ManagementMetrics.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagementPluginStore

> PluginStore GetManagementPluginStore(ctx).Execute()

Get Store



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
	resp, r, err := apiClient.ManagementAPI.GetManagementPluginStore(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.GetManagementPluginStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagementPluginStore`: PluginStore
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.GetManagementPluginStore`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagementPluginStoreRequest struct via the builder pattern


### Return type

[**PluginStore**](PluginStore.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagementStatus

> ManagementStatus GetManagementStatus(ctx).Execute()

Get Status

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
	resp, r, err := apiClient.ManagementAPI.GetManagementStatus(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.GetManagementStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagementStatus`: ManagementStatus
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.GetManagementStatus`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagementStatusRequest struct via the builder pattern


### Return type

[**ManagementStatus**](ManagementStatus.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InstallManagementGitHubPlugin

> PluginStore InstallManagementGitHubPlugin(ctx).GitHubPluginInstall(gitHubPluginInstall).IfMatch(ifMatch).Execute()

Install Github



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
	gitHubPluginInstall := *openapiclient.NewGitHubPluginInstall("Repository_example") // GitHubPluginInstall | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.InstallManagementGitHubPlugin(context.Background()).GitHubPluginInstall(gitHubPluginInstall).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.InstallManagementGitHubPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InstallManagementGitHubPlugin`: PluginStore
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.InstallManagementGitHubPlugin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInstallManagementGitHubPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **gitHubPluginInstall** | [**GitHubPluginInstall**](GitHubPluginInstall.md) |  | 
 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**PluginStore**](PluginStore.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListManagementTasks

> ManagementTaskList ListManagementTasks(ctx).Modality(modality).Status(status).KeyId(keyId).Backend(backend).Offset(offset).Limit(limit).Execute()

List Tasks

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
	modality := "modality_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	keyId := "keyId_example" // string |  (optional)
	backend := "backend_example" // string |  (optional)
	offset := int32(56) // int32 |  (optional) (default to 0)
	limit := int32(56) // int32 |  (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.ListManagementTasks(context.Background()).Modality(modality).Status(status).KeyId(keyId).Backend(backend).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.ListManagementTasks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListManagementTasks`: ManagementTaskList
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.ListManagementTasks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListManagementTasksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **modality** | **string** |  | 
 **status** | **string** |  | 
 **keyId** | **string** |  | 
 **backend** | **string** |  | 
 **offset** | **int32** |  | [default to 0]
 **limit** | **int32** |  | [default to 50]

### Return type

[**ManagementTaskList**](ManagementTaskList.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListManagementUsage

> ManagementUsageList ListManagementUsage(ctx).KeyId(keyId).Execute()

List Usage

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
	keyId := "keyId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.ListManagementUsage(context.Background()).KeyId(keyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.ListManagementUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListManagementUsage`: ManagementUsageList
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.ListManagementUsage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListManagementUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **keyId** | **string** |  | 

### Return type

[**ManagementUsageList**](ManagementUsageList.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutManagementBackend

> ManagementConfigResponse PutManagementBackend(ctx, name).ManagedBackend(managedBackend).IfMatch(ifMatch).Execute()

Put Backend

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
	name := "name_example" // string | 
	managedBackend := *openapiclient.NewManagedBackend("Name_example", "Type_example") // ManagedBackend | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.PutManagementBackend(context.Background(), name).ManagedBackend(managedBackend).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.PutManagementBackend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutManagementBackend`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.PutManagementBackend`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPutManagementBackendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedBackend** | [**ManagedBackend**](ManagedBackend.md) |  | 
 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutManagementKey

> ManagementConfigResponse PutManagementKey(ctx, keyId).ManagedKey(managedKey).IfMatch(ifMatch).Execute()

Put Key

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
	keyId := "keyId_example" // string | 
	managedKey := *openapiclient.NewManagedKey("Id_example", "Key_example") // ManagedKey | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.PutManagementKey(context.Background(), keyId).ManagedKey(managedKey).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.PutManagementKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutManagementKey`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.PutManagementKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**keyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPutManagementKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedKey** | [**ManagedKey**](ManagedKey.md) |  | 
 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutManagementPlugin

> PluginStore PutManagementPlugin(ctx, pluginId).PluginOptions(pluginOptions).IfMatch(ifMatch).Execute()

Put Plugin



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
	pluginId := "pluginId_example" // string | 
	pluginOptions := *openapiclient.NewPluginOptions() // PluginOptions | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.PutManagementPlugin(context.Background(), pluginId).PluginOptions(pluginOptions).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.PutManagementPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutManagementPlugin`: PluginStore
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.PutManagementPlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**pluginId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPutManagementPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **pluginOptions** | [**PluginOptions**](PluginOptions.md) |  | 
 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**PluginStore**](PluginStore.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutManagementProxy

> ManagementConfigResponse PutManagementProxy(ctx, domain).ManagedProxy(managedProxy).IfMatch(ifMatch).Execute()

Put Proxy

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
	domain := "domain_example" // string | 
	managedProxy := *openapiclient.NewManagedProxy("BaseUrl_example") // ManagedProxy | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.PutManagementProxy(context.Background(), domain).ManagedProxy(managedProxy).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.PutManagementProxy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutManagementProxy`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.PutManagementProxy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPutManagementProxyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedProxy** | [**ManagedProxy**](ManagedProxy.md) |  | 
 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReloadManagementPlugin

> PluginStore ReloadManagementPlugin(ctx, pluginId).IfMatch(ifMatch).Execute()

Reload Plugin



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
	pluginId := "pluginId_example" // string | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.ReloadManagementPlugin(context.Background(), pluginId).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.ReloadManagementPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReloadManagementPlugin`: PluginStore
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.ReloadManagementPlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**pluginId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReloadManagementPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**PluginStore**](PluginStore.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplaceManagementConfig

> ManagementConfigResponse ReplaceManagementConfig(ctx).ManagementConfig(managementConfig).IfMatch(ifMatch).Execute()

Replace Config

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
	managementConfig := *openapiclient.NewManagementConfig() // ManagementConfig | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.ReplaceManagementConfig(context.Background()).ManagementConfig(managementConfig).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.ReplaceManagementConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplaceManagementConfig`: ManagementConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.ReplaceManagementConfig`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiReplaceManagementConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **managementConfig** | [**ManagementConfig**](ManagementConfig.md) |  | 
 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**ManagementConfigResponse**](ManagementConfigResponse.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateManagementGitHubPlugin

> PluginStore UpdateManagementGitHubPlugin(ctx, pluginId).IfMatch(ifMatch).Execute()

Update Plugin



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
	pluginId := "pluginId_example" // string | 
	ifMatch := "ifMatch_example" // string | Current configuration revision (ETag). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagementAPI.UpdateManagementGitHubPlugin(context.Background(), pluginId).IfMatch(ifMatch).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagementAPI.UpdateManagementGitHubPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateManagementGitHubPlugin`: PluginStore
	fmt.Fprintf(os.Stdout, "Response from `ManagementAPI.UpdateManagementGitHubPlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**pluginId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateManagementGitHubPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifMatch** | **string** | Current configuration revision (ETag). | 

### Return type

[**PluginStore**](PluginStore.md)

### Authorization

[ManagementAuth](../README.md#ManagementAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

