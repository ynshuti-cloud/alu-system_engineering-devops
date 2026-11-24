# load_balancer

Load balancing project (alu-system_engineering-devops).

| File | Purpose |
|------|---------|
| `0-custom_http_response_header` | Installs nginx and adds an `X-Served-By` header with the server hostname |
| `1-install_load_balancer` | Installs HAProxy and balances web-01 and web-02 with roundrobin |
