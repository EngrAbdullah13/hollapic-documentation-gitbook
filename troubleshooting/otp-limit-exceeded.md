# OTP limit exceeded

The backend blocks additional OTP sends after four successful sends to the same email within one hour.

## What to do

Wait until the returned retry time. The error message includes the remaining wait time in minutes.

## Important behavior

This does not block verification of an already-valid code. It only blocks sending more codes.

## Related guides

- [OTP sending limits](../account-and-security/otp-sending-limits.md)
- [OTP cooldown and remaining-time behavior](../account-and-security/otp-cooldown.md)
