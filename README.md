# Fix-HealthMailboxes.ps1
Fix corrupted Exchange Server Health Mailboxes.

## Description
Removes/Disables HealthMailboxes that are lacking a mailbox database attribute aka corrupt.

## Parameters
### Remove  
Remove the HealthMailboxes that have an empty database attribute  

### Disable
Disables the HealthMailboxes that have an empty database attribute

## Examples
```
.\Fix-HealthMailboxes.ps1 -Remove
```
Remove the HealthMailbox(es) having an empty database attribute

## TechNet Gallery
Find the script at TechNet Gallery
* https://gallery.technet.microsoft.com/Find-and-remove-corrupt-42c8bfc2


## Credits
Written by: Thomas Stensitzki

## Social

* My Blog: http://justcantgetenough.granikos.eu
* Twitter:	https://twitter.com/stensitzki
* LinkedIn:	http://de.linkedin.com/in/thomasstensitzki
* Github:	https://github.com/Apoc70

For more Office 365, Cloud Security and Exchange Server stuff checkout services provided by Granikos

* Blog:     http://blog.granikos.eu/
* Website:	https://www.granikos.eu/en/
* Twitter:	https://twitter.com/granikos_de
