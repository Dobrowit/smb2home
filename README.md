# smb2home
A script to quickly mount SMB resources from within your home directory.
```
smb2home [option]
 <share>            Mount network share <share> for the current user
 <share> -u <user>  Mount network share <share> for the user <user>
 -a                 Mount all shares (from the list -ls)
 <share> -d         Unmount share <share>
 -da                Unmount all shares (from the list -ls)
 -ls                List shares on the server for the current user
 -ls -u <user>      List shares on the server for the user <user>
 -l                 List mounted shares
 -s <ip>            Save the SMB server address
 -p <user>          Save the password for the user <user>
 -i                 Configuration information
 -h                 Help
```
