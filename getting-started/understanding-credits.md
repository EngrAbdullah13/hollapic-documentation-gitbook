# Understanding credits

Credits control image generation. A workspace must have enough available credits before a generation can start.

## Credit buckets

Hollapic tracks subscription credits, purchased credits, and bonus credits separately. The visible total is the sum of those buckets after subscription expiry checks.

## Credit usage order

The backend consumes subscription credits first because they can expire. Purchased and bonus credits are used after subscription credits.

## Shared workspaces

Collaborators use the owner workspace credit rules. Limited collaborators can only spend their own remaining allocation. Owners and full-credit collaborators use the free/shared pool.

## Related guides

- [How credits work](../plans-and-billing/how-credits-work.md)
- [Credit rules](../reference/credit-rules.md)
- [Limited credit access](../teams-and-workspaces/limited-credit-access.md)
