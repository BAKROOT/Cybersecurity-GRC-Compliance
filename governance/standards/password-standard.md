# Password and Authentication Standard

| Field | Value |
| --- | --- |
| Document ID | GOV-STD-001 |
| Owner | CISO |
| Status | Approved |
| Version | 1.0 |
| Supports | Access Control Policy (GOV-POL-003) |

## 1. Purpose

Defines the minimum requirements for passwords and authentication across organizational systems.

## 2. Password Requirements

| Requirement | Standard |
| --- | --- |
| Minimum length | 12 characters (user), 16+ (privileged) |
| Complexity | Encourage passphrases; screen against breached-password lists |
| Reuse | Prevent reuse of last 10 passwords |
| Expiry | No forced periodic expiry unless compromise is suspected |
| Lockout | Lock after 10 failed attempts; throttle on repeated failures |

## 3. Multi-Factor Authentication (MFA)

MFA is required for remote access, administrative and privileged access, access to email, and access to systems handling Confidential or Restricted data. Phishing-resistant MFA is preferred for privileged access.

## 4. Storage and Transmission

Passwords must be stored using a strong, salted, one-way hashing algorithm and never transmitted or logged in clear text.

## 5. Service and Shared Accounts

Service account secrets are stored in an approved secrets manager, rotated regularly, and never embedded in source code. Shared accounts are avoided; where unavoidable, access is logged and credentials are vaulted.

## 6. Exceptions

Exceptions require documented risk acceptance approved by the CISO.

## 7. Review

Reviewed at least annually.
