<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-04-07T10:07:15Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2vOeEP9jb2P3x6wyEfcOvUee2M0",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vOeEP9jb2P3x6wyEfcOvUee2M0"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2vOeDCp65T1bB9UGjhNWSkhOBmI",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vOeDCp65T1bB9UGjhNWSkhOBmI"
				},
				"enabled": true
			},
			"created_at": "2025-04-07T10:07:05Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2vOeDFTGN3vWuDmtKdKGWZgc8g6",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2vOeDFTGN3vWuDmtKdKGWZgc8g6"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
