<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_31V8rA6K6QYPz1c1D17qAWACc2B",
        "uri": "https://api.ngrok.com/tls_certificates/cert_31V8rA6K6QYPz1c1D17qAWACc2B"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2vd4qtbfkfms5atml.local-ngrok-cname.com",
      "created_at": "2025-08-19T10:07:55Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31V8rDC5GhILZ2hY5Q9TTzRadO9",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31V8rDC5GhILZ2hY5Q9TTzRadO9"
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
          "started_at": "2025-08-19T10:07:55Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2vd4qtbfkfms5atml.local-ngrok-cname.com",
      "created_at": "2025-08-19T10:07:55Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31V8r9Gdi2qgr6UjgSzBfhVXbME",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31V8r9Gdi2qgr6UjgSzBfhVXbME"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-19T10:07:24Z",
      "description": "Your dev domain",
      "domain": "grizzly-discrete-iguana.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31V8nI679uO7bCALyMln3acv81d",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31V8nI679uO7bCALyMln3acv81d"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
