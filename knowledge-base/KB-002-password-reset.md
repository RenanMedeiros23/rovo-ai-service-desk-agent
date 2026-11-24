# KB-002 — Password Reset

## Category

Identity and Access Management (IAM)

## Affected Service

Corporate User Authentication

## Symptoms

- User cannot log in.
- Password has expired.
- User has forgotten their password.
- Account is locked after multiple failed login attempts.

## Initial Troubleshooting

1. Identify the affected application or service.
2. Confirm the reported error message.
3. Verify the user's identity according to company security policies.
4. Determine whether the password has expired or the account is locked.
5. Check whether an approved self-service password reset option is available.
6. Recommend the authorized password reset procedure.

## Escalation Criteria

- Identity verification cannot be completed.
- Password reset is unsuccessful.
- Account remains locked.
- Administrative or privileged accounts are affected.
- Suspicious authentication activity is detected.

## Recommended Support Team

Identity and Access Management — Level 2.

Suspected security incidents must follow the organization's security incident response procedures.

## Service Restoration Validation

- Confirm that the user can log in successfully.
- Verify access to the affected service.
- Document the actions performed without recording credentials.

## Safety and Restrictions

- Never request or store user passwords.
- Never request MFA verification codes.
- Never bypass identity verification.
- Never disable security controls without authorization.
- Require human approval for account modifications.

## Article Status

Educational lab — simulated knowledge base article. Pending technical validation.
