# Security Notes

- Store API keys and model credentials in environment variables or a secret manager.
- Do not commit patient/user records or private health information.
- Validate externally supplied input before processing.
- Keep logs free of unnecessary sensitive fields.
- Review third-party model and API permissions before production deployment.
