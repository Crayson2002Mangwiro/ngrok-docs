<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-03-31T10:11:15Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2v4sr0EqAaVNQSov9pzmFqEUnxV",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2v4sr0EqAaVNQSov9pzmFqEUnxV"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2v4sphUpsEp1dzFwdKFWeQzq18O",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2v4sphUpsEp1dzFwdKFWeQzq18O"
				},
				"enabled": true
			},
			"created_at": "2025-03-31T10:11:04Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2v4spi3KJF8jTkycdbfWAtHHSZC",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2v4spi3KJF8jTkycdbfWAtHHSZC"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
