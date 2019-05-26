# scripting
----
## general
- get-ExecutionPolicy
- set-ExecutionPolicy restricted/unrestricted
----
## examples 
1. foreach loop
  1. x
  1. y
  1. z 
  
   ```
   $extensions=code --list-extensions
   $extensions=code | ForEach-Object($extensions){
     echo $_
   }
   ```  
   
1. for loop
1. if then
1. xyz
