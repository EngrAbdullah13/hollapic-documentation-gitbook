# Security practices

Hollapic uses server-side authorization for sensitive actions.

## Confirmed practices

- JWT authentication middleware protects authenticated routes.
- Admin tools use `ADMIN_EMAILS`.
- Brand DNA access and workspace actions are checked server-side.
- Stripe webhook verification uses raw body parsing before JSON parsing.
- OTP codes are hashed before storage.
- Workspace selection is validated by active membership.

## Related guides

- [Developer security](../developer-guide/security.md)
- [Workspace permissions](../reference/workspace-permissions.md)
