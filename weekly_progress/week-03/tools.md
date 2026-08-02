# Proxy & Traffic Routing Quick Reference

## 🚀 FoxyProxy Quick Switch Setup
* **Name:** Burp Suite
* **Proxy Type:** HTTP
* **IP Address:** `127.0.0.1`
* **Port:** `8080`

## 💡 Troubleshooting SSL/TLS Errors
If browsers throw an `SEC_ERROR_UNKNOWN_ISSUER` error when intercepting HTTPS traffic:
* Verify that the Burp CA certificate is successfully installed under **Authorities** in the browser's certificate manager.
* Check that intercept mode (`Intercept is on`) is toggled correctly on the Burp Proxy tab.
