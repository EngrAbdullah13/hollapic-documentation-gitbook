# OTP sending limits

Hollapic rate limits OTP sends by normalized email address.

## Rule

A single email address can receive a maximum of four successfully sent OTP codes within one hour. The fifth attempt returns HTTP `429 Too Many Requests` with a remaining wait time.

## Important behavior

Failed email-provider sends release the reserved send attempt and do not consume the limit.

## Related guides

- [OTP cooldown and remaining-time behavior](otp-cooldown.md)
- [OTP limit exceeded](../troubleshooting/otp-limit-exceeded.md)
