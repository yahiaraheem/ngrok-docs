<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-19T10:08:16Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_31V8tCX2Zm5NeFo6yeVfPdJIGdv",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31V8tCX2Zm5NeFo6yeVfPdJIGdv"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31V8towBiWMNtr70wF79FOxvFCN",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-19T10:08:16Z",
      "uri": "https://api.ngrok.com/endpoints/ep_31V8towBiWMNtr70wF79FOxvFCN",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-19T10:08:13Z",
      "hostport": "c765119c21c3.ngrok.paid:443",
      "id": "ep_31V8tQHHBADVNKXkGP5wHL5rT7t",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_31V8n550tvAdgPqRVrSxBgDgYJk",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://c765119c21c3.ngrok.paid",
      "tunnel": {
        "id": "tn_31V8tQHHBADVNKXkGP5wHL5rT7t",
        "uri": "https://api.ngrok.com/tunnels/tn_31V8tQHHBADVNKXkGP5wHL5rT7t"
      },
      "tunnel_session": {
        "id": "ts_31V8tT0FV3CvEGHbAh32cfdJ5BY",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_31V8tT0FV3CvEGHbAh32cfdJ5BY"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-19T10:08:13Z",
      "upstream_url": "http://localhost:80",
      "url": "https://c765119c21c3.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-19T10:08:11Z",
      "domain": {
        "id": "rd_31V8tCX2Zm5NeFo6yeVfPdJIGdv",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31V8tCX2Zm5NeFo6yeVfPdJIGdv"
      },
      "edge": {
        "id": "edgtls_31V8tBjbMKUWSmuoyp7MO3g3VPW",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_31V8tBjbMKUWSmuoyp7MO3g3VPW"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31V8tCZppFHyyts3oXVbKK1GYoh",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-19T10:08:11Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
