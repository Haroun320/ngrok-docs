<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"bindings": ["public"],
	"created_at": "2025-04-07T10:07:10Z",
	"description": "sample cloud endpoint",
	"domain": {
		"id": "rd_2vOeDG1lrr1RveI4hmwi0fePTlK",
		"uri": "https://api.ngrok.com/reserved_domains/rd_2vOeDG1lrr1RveI4hmwi0fePTlK"
	},
	"hostport": "endpoint-example2.com:443",
	"id": "ep_2vOeDntvMg85b7WNdhqidSJ9tkP",
	"metadata": "{\"environment\": \"staging\"}",
	"pooling_enabled": false,
	"proto": "https",
	"public_url": "https://endpoint-example2.com",
	"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
	"type": "cloud",
	"updated_at": "2025-04-07T10:07:10Z",
	"uri": "https://api.ngrok.com/endpoints/ep_2vOeDntvMg85b7WNdhqidSJ9tkP",
	"url": "https://endpoint-example2.com"
}
```
