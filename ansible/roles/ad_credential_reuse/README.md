# ad_credential_reuse

Sets a declared password on a selected Active Directory user. Define the same
lab-only password for the intended privileged account outside this role.

## Requirements

- Run against a Windows domain controller or management host with the
  `ActiveDirectory` PowerShell module.
- The selected user must already exist.

## Variables

```yaml
ad_credential_reuse_target_user: primary_user01
ad_credential_reuse_password: lab-only-password
```
