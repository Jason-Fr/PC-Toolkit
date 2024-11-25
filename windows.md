| Version | Last Updated |
| --- | --- |
| 01.00.00 | 25/11/24 |

## Get original Windows product key

### Command Prompt
Open the cmd prompt as the administrator and run the command below
```cmd
wmic path softwareLicensingService get OA3xOriginalProductKey
```
The product key is shown under this
OA3xOriginalProductKey


### PowerShell on the command prompt

```Powershell
powershell "(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey
```

