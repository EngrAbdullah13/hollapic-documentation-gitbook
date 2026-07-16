# Failed payments

Failed subscription payments do not add new credits.

## Current behavior

Stripe payment failure events update subscription status where applicable. Existing subscription credits are not immediately removed if the user is still within an already-paid period. Credits are cleared when Stripe confirms the subscription is ended or deleted.

## Related guides

- [Subscription expiration](subscription-expiration.md)
- [Billing troubleshooting](troubleshooting.md)
