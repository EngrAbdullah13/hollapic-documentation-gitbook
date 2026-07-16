# Subscription expiration

Subscription credits are time-bound.

## Current behavior

Before credit-sensitive operations, the backend checks whether subscription credits are expired. If expired, subscription credits are cleared and the user’s remaining total is recalculated from purchased and bonus credits.

## Cancellation

If Stripe sends subscription deleted, subscription credits are cleared and the plan/status returns to a canceled/free state.

## Related guides

- [Cancellation](cancellation.md)
- [Subscription credits were not added](../troubleshooting/subscription-credits-not-added.md)
