# My PowerShell Commands
## Notes
- *commands are case insensitive*
- *double tabs*  

## miscellaneous
- gcm=get-command | more | -commandtype | -syntax
- get-help  
- get-history
- get-date
- get-credentials  
- converto-json

## piping
- more | select | ? |

## operator
- split

## services
- get-service   
- start-service
- stop-service
- Set-Service -Name sshd -StartupType 'Automatic'
- get-process name

## app & features
- Find a specific feature   
  ```Get-WindowsCapability -Online | ? Name -like 'OpenSSH*'```  
- Next command go here

## Network
- check firewall rule  
  ```Get-NetFirewallRule -Name *ssh*```  
- Next command go here

## file system
- Get-ChildItem -Path C:\WINDOWS\System32 | Out-Host -Paging
- Get-Location | Get-Member  [gm=get-member]
``` 
in order to refer to any members of PathInfo object returned by get-location, asssign it to a variable first
  - $a=get-location
  - $a.gethashcode() 
```
## applications
### ssh-client
- ssh  
- ssh-keygen -R  

