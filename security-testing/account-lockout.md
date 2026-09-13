# Account Lockout Testing

## Objective

Test the configured Active Directory account lockout policy using a controlled test account.

## Test Procedure

1. Attempt to sign in with an incorrect password.
2. Repeat the failed attempts according to the configured threshold.
3. Verify that the account becomes locked.
4. Review the Windows security logs.
5. Unlock the account and verify normal access.

## Evidence

- Account lockout
- Security event
- Event ID
- Username
- Time of event

Screenshots will be added after testing is completed.

## Security Value

Account lockout controls help reduce the effectiveness of repeated password-guessing attempts.
