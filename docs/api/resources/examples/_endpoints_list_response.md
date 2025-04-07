<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
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
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-07T10:07:07Z",
			"hostport": "9558a085745d.ngrok.paid:443",
			"id": "ep_2vOeDQlS94s1CrbQiQ8RhQILhr2",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2vOeB9riFFcuQJfyPW4WYc2fa8x",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://9558a085745d.ngrok.paid",
			"tunnel": {
				"id": "tn_2vOeDQlS94s1CrbQiQ8RhQILhr2",
				"uri": "https://api.ngrok.com/tunnels/tn_2vOeDQlS94s1CrbQiQ8RhQILhr2"
			},
			"tunnel_session": {
				"id": "ts_2vOeDOPRaLNGEqmjRqdCfRfuyrp",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2vOeDOPRaLNGEqmjRqdCfRfuyrp"
			},
			"type": "ephemeral",
			"updated_at": "2025-04-07T10:07:07Z",
			"upstream_url": "http://localhost:80",
			"url": "https://9558a085745d.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-04-07T10:07:05Z",
			"domain": {
				"id": "rd_2vOeDG1lrr1RveI4hmwi0fePTlK",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2vOeDG1lrr1RveI4hmwi0fePTlK"
			},
			"edge": {
				"id": "edgtls_2vOeDFTGN3vWuDmtKdKGWZgc8g6",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2vOeDFTGN3vWuDmtKdKGWZgc8g6"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2vOeD9jrP7uNBQUDg6IRyCRhqul",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-04-07T10:07:05Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
