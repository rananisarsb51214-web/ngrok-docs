<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
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
          "started_at": "2025-09-29T10:07:39Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.4ldgrj6dpsq91newl.local-ngrok-cname.com",
      "created_at": "2025-09-29T10:07:39Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_33Mwt3yvUFuU8yd7vukislhOA89",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_33Mwt3yvUFuU8yd7vukislhOA89"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_33MwsyqR84M5CNdtlWrewrCFiXv",
        "uri": "https://api.ngrok.com/tls_certificates/cert_33MwsyqR84M5CNdtlWrewrCFiXv"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.4ldgrj6dpsq91newl.local-ngrok-cname.com",
      "created_at": "2025-09-29T10:07:39Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_33Mwt3iQkXMSQSQAZ6lYtjKNe9c",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_33Mwt3iQkXMSQSQAZ6lYtjKNe9c"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-29T10:07:08Z",
      "description": "Your dev domain",
      "domain": "degenerative-elvina-comprehensibly.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_33MwpAalUMR9QbGii3pIO3Pnlrf",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_33MwpAalUMR9QbGii3pIO3Pnlrf"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
