# HTTPS SSL

Securing the web stack with HTTPS: DNS subdomains, SSL termination on HAProxy, and HTTP to HTTPS redirection.

| File | Description |
| --- | --- |
| `0-world_wide_web` | Displays the DNS record type and destination of a domain's subdomains |
| `1-haproxy_ssl_termination` | HAProxy config terminating SSL on port 443 |
| `2-redirect_http_to_https` | HAProxy config redirecting HTTP to HTTPS with a 301 |
