<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-29T10:08:00Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_33MwuxmTWJbnvTBbk3pJ8RJIYvf",
        "uri": "https://api.ngrok.com/reserved_domains/rd_33MwuxmTWJbnvTBbk3pJ8RJIYvf"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_33MwvgMwqu4E8GOnCAnkKbZaHNU",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-09-29T10:08:00Z",
      "uri": "https://api.ngrok.com/endpoints/ep_33MwvgMwqu4E8GOnCAnkKbZaHNU",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-29T10:07:58Z",
      "hostport": "c7cf2560b9dc.ngrok.paid:443",
      "id": "ep_33MwvNtnCzv6JhsWMZDlOgJRHfu",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_33MwonEPYMA1qq1w7MTs3k8XgnX",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://c7cf2560b9dc.ngrok.paid",
      "tunnel": {
        "id": "tn_33MwvNtnCzv6JhsWMZDlOgJRHfu",
        "uri": "https://api.ngrok.com/tunnels/tn_33MwvNtnCzv6JhsWMZDlOgJRHfu"
      },
      "tunnel_session": {
        "id": "ts_33MwvMQGBziRRjCsTcNVPQLYLkN",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_33MwvMQGBziRRjCsTcNVPQLYLkN"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-29T10:07:58Z",
      "upstream_url": "http://localhost:80",
      "url": "https://c7cf2560b9dc.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-29T10:07:55Z",
      "domain": {
        "id": "rd_33MwuxmTWJbnvTBbk3pJ8RJIYvf",
        "uri": "https://api.ngrok.com/reserved_domains/rd_33MwuxmTWJbnvTBbk3pJ8RJIYvf"
      },
      "edge": {
        "id": "edgtls_33Mwv5An5DB4O6WJsqce0dN4bwz",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_33Mwv5An5DB4O6WJsqce0dN4bwz"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_33Mwv1XpWN5gA1hindHiT6NDLrI",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-29T10:07:55Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
