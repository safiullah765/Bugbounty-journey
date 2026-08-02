# Burp Suite Configuration & Proxy Notes

## ⚙️ Setup Checklist
1. **Proxy Listener:** Ensure Burp is listening on `127.0.0.1:8080`.
2. **Browser Configuration:** Configure Firefox or Chromium to route traffic through the local proxy using FoxyProxy.
3. **CA Certificate Installation:** Export the PortSwigger CA certificate from `http://burp` and import it into the browser's certificate authority trust store to intercept HTTPS traffic cleanly.

## 🛠️ Key Features Used This Week
* **Target Scope:** Defining scope definitions to avoid out-of-scope traffic cluttering the HTTP history.
* **Repeater:** Manually modifying and re-sending individual HTTP requests to test server-side response behavior.
* **Intruder:** Setting up basic payload positions for fuzzing input fields.
