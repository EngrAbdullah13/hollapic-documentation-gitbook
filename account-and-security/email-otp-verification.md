# Email OTP verification

OTP codes are six-digit email codes used for signup and login.

## Important behavior

- Codes are hashed before storage.
- Old unused codes for the same email are marked used when a new code is requested.
- Verification uses the latest matching unused code.
- OTP send limiting applies only to sending new codes, not verification.

## Related guides

- [OTP sending limits](otp-sending-limits.md)
- [OTP email was not received](../troubleshooting/otp-email-not-received.md)
