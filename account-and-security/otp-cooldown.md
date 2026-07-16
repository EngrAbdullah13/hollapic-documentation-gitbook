# OTP cooldown and remaining-time behavior

The frontend also shows a resend cooldown, but the server-side hourly limit is authoritative.

## Current behavior

If the hourly limit is exceeded, the backend returns a message such as:

```text
You have reached the OTP send limit for this email. Try again in 42 minutes.
```

## Important behavior

Use server time for wait calculations. Browser timers are only a convenience.

## Related guides

- [OTP sending limits](otp-sending-limits.md)
