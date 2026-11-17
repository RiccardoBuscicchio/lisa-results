# Protected static site

All content is encrypted (AES-256-GCM, key derived from a password with PBKDF2-HMAC-SHA256). Open `index.html`
over HTTP (e.g. `python3 -m http.server 8000`, then http://localhost:8000) and enter the password.
