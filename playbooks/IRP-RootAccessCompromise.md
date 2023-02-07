# Compromise the Root Account Access

The general guidelines on the credentials compromise is applicable to this as well. Please check [Credentials Compromise](IRP-CredCompromise.md) section for more details.

## Incident Response Process
---
### Part 1: Acquire, Preserve, Document Evidence

- In addition to the credentials compromise IRP, subscribe the root access compromise SNS topic to receive alerts on root access compromise.
- The root access hardware MFA is not available. Make sure you have the access to the same token, and make sure that the token is not misplaced or stolen.

### Part 2: Contain the Incident
- See the guidelines in [Credentials Compromise](IRP-CredCompromise.md)

### Part 3: Eradicate the Incident
- Immediately request the admins to change the root account password if the MFA device is still accisible.
- Use the AWS support line to temporarily disable the access if MFA device is not available

## Additional Resources
---
[I can't sign in because my credentials don't work ](https://aws.amazon.com/premiumsupport/knowledge-center/forgot-aws-sign-in-credentials/ )