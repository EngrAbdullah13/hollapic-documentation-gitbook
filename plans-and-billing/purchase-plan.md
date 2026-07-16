# Purchase a plan

Plans are purchased through Stripe Checkout.

## Before you begin

- Sign in as the workspace owner.
- Do not switch into a collaborator workspace.

## Steps

1. Open the pricing section or pricing page.
2. Choose a plan.
3. Complete Stripe Checkout.
4. Return to Hollapic after checkout.

## Expected result

The backend receives Stripe webhook events, creates a completed payment record, and sets subscription credits for the plan.

## Related guides

- [Subscription renewals](subscription-renewals.md)
- [Stripe integration](../developer-guide/stripe-integration.md)
