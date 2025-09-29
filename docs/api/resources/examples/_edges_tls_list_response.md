<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-29T10:08:06Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_33MwwRwmdAlpsGM1IYDjLTPNCyZ",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_33MwwRwmdAlpsGM1IYDjLTPNCyZ"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_33Mwv5DEFa2OzA1Xi2TnrYrKeQ5",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_33Mwv5DEFa2OzA1Xi2TnrYrKeQ5"
        },
        "enabled": true
      },
      "created_at": "2025-09-29T10:07:55Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_33Mwv5An5DB4O6WJsqce0dN4bwz",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_33Mwv5An5DB4O6WJsqce0dN4bwz"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
