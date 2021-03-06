[![Build status](https://ci.appveyor.com/api/projects/status/0tuhgefw1g1u6umw?svg=true)](https://ci.appveyor.com/project/MSAdministrator/createprofile)
# CreateProfile
PowerShell Module that uses WINAPI to create system profiles

## SHORT DESCRIPTION
A PowerShell module to create a new local user profile before a user logs into a machine

## LONG DESCRIPTION
A PowerShell module that will create a new local user account and map it to a SID.  After that it will auto-login/create the user profile so that the user's profile is now mapped before they have even logged into a machine.

## DETAILED DESCRIPTION
A PowerShell module that will create a new local user account and map it to a SID.  After that it will auto-login/create the user profile so that the user's profile is now mapped before they have even logged into a machine.

## Example

```
> Import-Module .\CreateProfile\CreateProfile.psm1
> New-Profile -UserName 'Josh Thom' -Password 'P@ssw0rd123'
```