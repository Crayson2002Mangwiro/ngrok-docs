<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
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
}
```
