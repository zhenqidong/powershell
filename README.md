# My PowerShell Commands
## Notes
- *commands are case insensitive*

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
