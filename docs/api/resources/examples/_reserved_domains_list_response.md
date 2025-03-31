<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2v4snepEEaDWInKnJuzXEJDCCOW",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2v4snepEEaDWInKnJuzXEJDCCOW"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.wkascs29tquh7f5g.local-ngrok-cname.com",
			"created_at": "2025-03-31T10:10:48Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2v4snoAncxrAgj7jq6p24nlmMz8",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2v4snoAncxrAgj7jq6p24nlmMz8"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-03-31T10:10:49Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.wkascs29tquh7f5g.local-ngrok-cname.com",
			"created_at": "2025-03-31T10:10:49Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2v4snlEg8cSbjatqby77xXRd7KO",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2v4snlEg8cSbjatqby77xXRd7KO"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
