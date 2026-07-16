# Cancellation

Cancellation behavior depends on Stripe subscription events.

## Paid period

When a subscription is canceled at period end, already-granted subscription credits remain usable until the paid period ends.

## Subscription deleted

When Stripe confirms deletion, the backend clears subscription credits, clears expiration, sets subscription status to canceled, and sets the plan to free.

## Related guides

- [Refund policy](refund-policy.md)
- [Subscription expiration](subscription-expiration.md)
