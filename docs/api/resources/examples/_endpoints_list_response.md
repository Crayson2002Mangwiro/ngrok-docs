<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-03-31T10:11:09Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2v4spc15xaHpEy4M8G1stquhMg8",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2v4spc15xaHpEy4M8G1stquhMg8"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2v4sqEzws3dM1wSSW1yIh091bDg",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-03-31T10:11:09Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2v4sqEzws3dM1wSSW1yIh091bDg",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-31T10:11:07Z",
			"hostport": "2da933b5c321.ngrok.paid:443",
			"id": "ep_2v4sq47MMvC627DLO3Tswx9OheC",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2v4snbPkCmMRz1WMJjDgacJLkoa",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://2da933b5c321.ngrok.paid",
			"tunnel": {
				"id": "tn_2v4sq47MMvC627DLO3Tswx9OheC",
				"uri": "https://api.ngrok.com/tunnels/tn_2v4sq47MMvC627DLO3Tswx9OheC"
			},
			"tunnel_session": {
				"id": "ts_2v4sq1vSwpaSLK1G238HPdxfwgl",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2v4sq1vSwpaSLK1G238HPdxfwgl"
			},
			"type": "ephemeral",
			"updated_at": "2025-03-31T10:11:07Z",
			"upstream_url": "http://localhost:80",
			"url": "https://2da933b5c321.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-31T10:11:05Z",
			"domain": {
				"id": "rd_2v4spc15xaHpEy4M8G1stquhMg8",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2v4spc15xaHpEy4M8G1stquhMg8"
			},
			"edge": {
				"id": "edgtls_2v4spi3KJF8jTkycdbfWAtHHSZC",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2v4spi3KJF8jTkycdbfWAtHHSZC"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2v4spdNAMy40QCw41IioCcUAnzH",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-03-31T10:11:05Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
