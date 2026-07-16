# Subscription renewals

Subscription renewals are processed from Stripe `invoice.paid` events.

## Current behavior

For renewal invoices, the backend retrieves subscription metadata, resolves the user and plan, and resets subscription credits to the monthly plan amount instead of adding them on top of unused subscription credits.

## Example

If a Pro subscription has 42 subscription credits remaining at renewal, renewal resets subscription credits to the Pro monthly amount rather than setting them to 142.

## Related guides

- [Subscription expiration](subscription-expiration.md)
- [Credit allocation](credit-allocation.md)
