# 3. Backend language

Date: 2024-02-20

## Status

Accepted

## Context

As the app will be handling sensitive information, we need to prioritize data privacy and security. We should implement encryption, secure data transmission protocols, and adhere to relevant data protection regulations. the users on the app should be able to securely log in and their roles and permissions should be properly enforced.

## Decision

we will use Java with Spring boot as the backend language, as it offers security features, including authentication, authorization, encryption, and protection against vulnerabilities.

## Consequences

1.  Spring boot will allow us to implement our authorization methods.
2.  Spring boot will provide great restriction control to the app's resources based on the role and permissions.
3.  Spring boot will implement the secure password encryption feature, to protect the user's password.
4.  Spring boot is a complex framework and might require some time and additional knowledge to implement it.
