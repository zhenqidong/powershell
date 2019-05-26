# scripting
----
## general
- get-ExecutionPolicy
- set-ExecutionPolicy restricted/unrestricted
----
## examples 
[comment]: <> ( need 3 spaces to create nested list)
[comment]: <> ( blank line below the first list item can create loose list vs tight list)
1. foreach loop
   1. test

      ```
      $extensions=code --list-extensions
      $extensions=code | ForEach-Object($extensions){
        echo $_
      }
      ```  
   1. test1   
1. for loop
1. if then
1. xyz
