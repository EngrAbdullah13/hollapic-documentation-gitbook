# Log in

Hollapic login uses the same OTP flow as signup.

## Steps

1. Enter your email.
2. Request the code.
3. Enter the six-digit code.
4. Continue.

## Expected result

The backend verifies the code, marks it used, signs a seven-day JWT session token, and returns the authenticated user profile.

## Related guides

- [Login troubleshooting](login-troubleshooting.md)
- [Email OTP verification](email-otp-verification.md)
