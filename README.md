<div align="center">

## User Privileges


</div>

### Description

This code can check if the user that is logged on to windows is an administrator.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[James Ridgway](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/james-ridgway.md)
**Level**          |Beginner
**User Rating**    |4.3 (17 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Security](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/security__10-14.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/james-ridgway-user-privileges__10-5554/archive/master.zip)





### Source Code

```
The following code will check to see if a user is an administrator.
    If My.User.IsInRole(ApplicationServices.BuiltInRole.Administrator) = True Then
      lblResponse.Text = "This user is an administrator."
    Else
      lblResponse.Text = "This user is not an administrator."
    End If
You can change the BuiltInRole.Administrator to one of the following to check for a different user group: -
BuiltInRole.AccountOperator
BuiltInRole.BackupOperator
BuiltInRole.Guest
BuiltInRole.PowerUser
BuiltInRole.PrintOperator
BuiltInRole.Replicator
BuiltInRole.SystemOperator
BuiltInRole.User
This code was tested on Windows Vista, this code should be compatible with Windows 2000/XP/2003 Server
```

