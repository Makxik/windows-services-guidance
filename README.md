# windows-services-guidance
Guidance on disabling system services on Windows Server 2016 with Desktop Experience (https://docs.microsoft.com/en-us/windows-server/security/windows-services/security-guidelines-for-disabling-system-services-in-windows-server)
```
The Windows operating system includes many system services that provide important functionality. Different services have different default startup policies: some are started by default (automatic), some when needed (manual), and some are disabled by default and must be explicitly enabled before they can run. These defaults were chosen carefully for each service to balance performance, functionality, and security for typical customers.
```
# Important!
**(No guidance) <==> Do not disable!**
###
In this repository, you can add services that can lead to the successful boot and display of any Desktop Experience on your screen.
