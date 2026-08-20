# Order Service Repository

This repository owns the backend service for orders and its associated Keycloak client configuration.

### Keycloak Ownership
- `keycloak/client.yaml`: Defines `order-service` with `serviceAccountsEnabled: true`.
- `keycloak/roles.yaml`: Defines granular order management client roles.