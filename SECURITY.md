# Security and configuration

The workflow files in this repository are sanitized n8n exports:

- Credentials are not included; n8n only stores a reference, which is removed here.
- The Cloudflare account ID in the HTTP Request URL is replaced with `YOUR_ACCOUNT_ID`.

Before importing, configure your own n8n credentials and API endpoints. Never commit API keys, tokens or account IDs.

If a key or token is ever exposed, revoke it and create a new one with the provider; deleting it from a file does not make it safe again.
