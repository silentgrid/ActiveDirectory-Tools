Install the Powershell Active Directory management tools without admin rights.

Using the provided ZIP file: 
1. Download the ZIP file to the target host (please note, this is the x64 version).
2. PS > Import-Module Microsoft.ActiveDirectory.Management.dll

Use your own DLLs:
1. Download RSAT and install the Active Directory Management module
2. Copy the ActiveDirectory folder from "C:\Windows\System32\WindowsPowerShell\v1.0\Modules"
3. Copy the file "Microsoft.ActiveDirectory.Management.dll" from "C:\windows\winsxs\amd64_microsoft.activedirectory.management..." to the same ActiveDirectory folder.
