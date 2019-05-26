# My PowerShell Commands
## Notes
- *commands are case insensitive*
- *double tabs*  

## miscellaneous
- get-command | more | -commandtype | -syntax
- get-help  
- get-history
- get-date
- get-credentials  
- converto-json

## services
- get-service   
- start-service
- stop-service
- Set-Service -Name sshd -StartupType 'Automatic'

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

## applications
### ssh-client
- ssh  
- ssh-keygen -R  

