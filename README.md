# ThingsBoard Device Extraction – Postman Starter

A minimal Postman collection + environment for extracting any ThingsBoard device’s metadata, attributes, telemetry, credentials, and relations.

## 1-Click Import
1. **Clone** or download this repo.
2. In Postman:  
   *Collections* → *Import* → choose `ThingsBoard-Device-Extraction.postman_collection.json`  
   *Environments* → *Import* → choose `ThingsBoard-Dev.postman_environment.json`.

3. In the imported **ThingsBoard-Dev** environment, fill:
   - `baseUrl`  – e.g. `https://demo.thingsboard.io`
   - `tenantEmail`
   - `tenantPassword`

4. Run the first request **01 – Login (JWT)**; the token is auto-saved.  
   All other requests will now work out of the box.

## API Docs
https://thingsboard.io/docs/reference/rest-api/
