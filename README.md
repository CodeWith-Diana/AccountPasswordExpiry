# PROJECT 2 : Active Directory Password Expiry Notification

Password Expiry Checker 

A PowerShell script that retrieves the password expiration date of Active Directory user accounts.

## Instructions
- Check Active Directory for all accounts with password expiring in 14 days, send email to the user.

## Requirements
- PowerShell 5.1+
- Active Directory PowerShell Module (RSAT or Domain Controller)

## Usage

```powershell
.\PasswordExpiryChecker.ps1 -Username "jdoe"
