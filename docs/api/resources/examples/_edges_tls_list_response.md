<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-19T10:08:22Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_31V8uabQwdtJ0jdERKV6kxRE6wh",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31V8uabQwdtJ0jdERKV6kxRE6wh"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_31V8tDIbWp6vAumabeUG8ucCtT8",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_31V8tDIbWp6vAumabeUG8ucCtT8"
        },
        "enabled": true
      },
      "created_at": "2025-08-19T10:08:11Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_31V8tBjbMKUWSmuoyp7MO3g3VPW",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31V8tBjbMKUWSmuoyp7MO3g3VPW"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
