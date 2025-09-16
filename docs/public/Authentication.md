# Authentication

This API supports JWT-based authentication for secure access to protected endpoints. API keys may also be configured for system-to-system integration.

## Authentication Flow

- Obtain a JWT token via the authentication endpoint
- Include the token in the `Authorization` header for protected requests
- API keys can be used for automated or system-level access

## Permissions

- User roles and permissions are enforced at the endpoint level
- Unauthorized requests will receive a 401 or 403 error response
