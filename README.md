# ![alt text](./media/powershell-logo.png?raw=true) PowerShell Commands Reference

## Introduction

Welcome to the PowerShell Commands Reference! 

This reference lists the commonly used commands and is not exhaustive. Where available, the individual command files will provide examples of usage for your reference. PowerShell commands have various options and arguments. It's essential to consult the [PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/) for detailed information and usage. Enjoy!

## Commands

| Name	| Alias	| Description	| Type	|
|-------------|------|--------|--------|				
| Get-ChildItem	| dir, gci, ls	| Gets the files and folders in a file system drive.	| Cmdlet	|
| Invoke-Command	| icm	| Runs commands on local and remote computers.	| Cmdlet	|
| Import-Module	| ipmo	| Adds modules to the current session.	| Cmdlet	|
| Export-Csv	| epcsv	| Converts objects into a series of comma-separated (CSV) strings and saves the strings in a CSV file.	| Cmdlet	|
| Write-Host	| 	| Writes customized output to a host.	| Cmdlet	|
| Get-WmiObject	| gwmi	| Gets instances of WMI classes or information about the available classes.	| Cmdlet	|
| Get-Content	| cat, gc, type	| Gets the contents of a file.	| Cmdlet	|
| Get-Date	| 	| Gets the current date and time.	| Cmdlet	|
| Invoke-WebRequest	| curl, iwr, wget	| Gets content from a web page on the Internet.	| Cmdlet	|
| Start-Process	| saps, start	| Starts one or more processes on the local computer.	| Cmdlet	|
| Copy-Item	| copy, cp, cpi	| Copies an item from one location to another.	| Cmdlet	|
| Set-ExecutionPolicy	| 	| Changes the user preference for the Windows PowerShell execution policy.	| Cmdlet	|
| Out-File	| 	| Sends output to a file.	| Cmdlet	|
| Where-Object	| ?, where	| Selects objects from a collection based on their property values.	| Cmdlet	|
| Import-Csv	| ipcsv	| Creates table-like custom objects from the items in a CSV file.	| Cmdlet	|
| Send-MailMessage	| 	| Sends an email message.	| Cmdlet	|
| New-Object	| 	| Creates an instance of a Microsoft .NET Framework or COM object.	| Cmdlet	|
| Select-String	| sls	| Finds text in strings and files.	| Cmdlet	|
| Remove-Item	| del, erase, rd, ri, rm, rmdir	| Deletes files and folders.	| Cmdlet	|
| Select-Object	| select	| Selects objects or object properties.	| Cmdlet	|
| Test-Path	| 	| Determines whether all elements of a file or directory path exist.	| Cmdlet	|
| Invoke-RestMethod	| irm	| Sends an HTTP or HTTPS request to a RESTful web service.	| Cmdlet	|
| Install-Package	| 	| Installs one or more software packages.	| Cmdlet	|
| ForEach-Object	| %, foreach	| Performs an operation against each item in a collection of input objects.	| Cmdlet	|
| Write-Output	| echo, write	| Sends the specified objects to the next command in the pipeline. If the command is the last command in thepipeline, the objects are displayed in the console.	| Cmdlet	|
| Get-Process	| gps, ps	| Gets the processes that are running on the local computer or a remote computer.	| Cmdlet	|
| Get-Service	| gsv	| Gets the services on a local or remote computer.	| Cmdlet	|
| Format-Table	| ft	| Formats the output as a table.	| Cmdlet	|
| Test-Connection	| 	| Sends ICMP echo request packets ("pings") to one or more computers.	| Cmdlet	|
| New-Item	| ni	| Creates a new item.	| Cmdlet	|
| Get-EventLog	| 	| Gets the events in an event log, or a list of the event logs, on the local or remote computers.	| Cmdlet	|
| Get-WinEvent	| 	| Gets events from event logs and event tracing log files on local and remote computers.	| Cmdlet	|
| Install-Module	| 	| Downloads one or more modules from an online gallery, and installs them on the local computer.	| Function	|
| Enter-PSSession	| etsn	| Starts an interactive session with a remote computer.	| Cmdlet	|
| Get-Credential	| 	| Gets a credential object based on a user name and password.	| Cmdlet	|
| Read-Host	| 	| Reads a line of input from the console.	| Cmdlet	|
| Get-AppxPackage	| 	| Gets a list of the app packages that are installed in a user profile.	| Cmdlet	|
| Get-Acl	| 	| Gets the security descriptor for a resource, such as a file or registry key.	| Cmdlet	|
| Get-Help	| 	| Displays information about Windows PowerShell commands and concepts.	| Cmdlet	|
| Start-Job	| sajb	| Starts a Windows PowerShell background job.	| Cmdlet	|
| Add-PSSnapin	| 	| Adds one or more Windows PowerShell snap-ins to the current session.	| Cmdlet	|
| New-PSSession	| nsn	| Creates a persistent connection to a local or remote computer.	| Cmdlet	|
| Invoke-Expression	| iex	| Runs commands or expressions on the local computer.	| Cmdlet	|
| Add-Content	| ac	| Appends content, such as words or data, to a file.	| Cmdlet	|
| New-PSDrive	| mount, ndr	| Creates temporary and persistent mapped network drives.	| Cmdlet	|
| Move-Item	| mi, move, mv	| Moves an item from one location to another.	| Cmdlet	|
| Get-Item	| gi	| Gets files and folders.	| Cmdlet	|
| Compare-Object	| compare, diff	| Compares two sets of objects.	| Cmdlet	|
| Sort-Object	| sort	| Sorts objects by property values.	| Cmdlet	|
| Test-NetConnection	| 	| Displays diagnostic information for a connection.	| Function	|
| Set-Acl	| 	| Changes the security descriptor of a specified item, such as a file or a registry key.	| Cmdlet	|
| Set-Content	| sc	| Replaces the contents of a file with contents that you specify.	| Cmdlet	|
| Start-Transcript	| 	| Creates a record of all or part of a Windows PowerShell session to a text file.	| Cmdlet	|
| Get-HotFix	| 	| Gets the hotfixes that have been applied to the local and remote computers.	| Cmdlet	|
| Get-ItemProperty	| gp	| Gets the properties of a specified item.	| Cmdlet	|
| Add-Member	| 	| Adds custom properties and methods to an instance of a Windows PowerShell object.	| Cmdlet	|
| Remove-AppxPackage	| 	| Removes an app package from a user account.	| Cmdlet	|
| Rename-Item	| ren, rni	| Renames an item in a Windows PowerShell provider namespace.	| Cmdlet	|
| Add-Type	| 	| Adds a.NET Framework type (a class) to a Windows PowerShell session.	| Cmdlet	|
| Get-Member	| gm	| Gets the properties and methods of objects.	| Cmdlet	|
| ConvertTo-SecureString	| 	| Converts encrypted standard strings to secure strings. It can also convert plain text to secure strings. It isused with ConvertFrom-SecureString and Read-Host.	| Cmdlet	|
| New-SelfSignedCertificate	| 	| Creates a new self-signed certificate for testing purposes.	| Cmdlet	|
| Start-Sleep	| sleep	| Suspends the activity in a script or session for the specified period of time.	| Cmdlet	|
| Restart-Computer	| 	| Restarts ("reboots") the operating system on local and remote computers.	| Cmdlet	|
| Out-GridView	| ogv	| Sends output to an interactive table in a separate window.	| Cmdlet	|
| Format-List	| fl	| Formats the output as a list of properties in which each property appears on a new line.	| Cmdlet	|
| Set-ItemProperty	| sp	| Creates or changes the value of a property of an item.	| Cmdlet	|
| Measure-Object	| measure	| Calculates the numeric properties of objects, and the characters, words, and lines in string objects, such asfiles of text.	| Cmdlet	|
| Split-Path	| 	| Returns the specified part of a path.	| Cmdlet	|
| Get-Counter	| 	| Gets performance counter data from local and remote computers.	| Cmdlet	|
| Get-CimInstance	| 	| Gets the CIM instances of a class from a CIM server.	| Cmdlet	|
| Add-Computer	| 	| Add the local computer to a domain or workgroup.	| Cmdlet	|
| Add-AppxPackage	| 	| Adds a signed app package to a user account.	| Cmdlet	|
| ConvertTo-Html	| 	| Converts Microsoft .NET Framework objects into HTML that can be displayed in a Web browser.	| Cmdlet	|
| Import-StartLayout	| 	| Imports the layout of the Start into a mounted Windows image.	| Cmdlet	|
| Set-Location	| cd, chdir, sl	| Sets the current working location to a specified location.	| Cmdlet	|
| Get-NetAdapter	| 	| Gets the basic network adapter properties.	| Function	|
| Export-StartLayout	| 	| Exports the layout of the Start screen.	| Cmdlet	|
| Enable-PSRemoting	| 	| Configures the computer to receive remote commands.	| Cmdlet	|
| Get-Command	| gcm	| Gets all commands.	| Cmdlet	|
| Get-ExecutionPolicy	| 	| Gets the execution policies for the current session.	| Cmdlet	|
| Join-Path	| 	| Combines a path and a child path into a single path.	| Cmdlet	|
| Import-PSSession	| ipsn	| Imports commands from another session into the current session.	| Cmdlet	|
| Get-FileHash	| 	| Computes the hash value for a file by using a specified hash algorithm.	| Function	|
| Write-Error	| 	| Writes an object to the error stream.	| Cmdlet	|
| Stop-Service	| spsv	| Stops one or more running services.	| Cmdlet	|
| Stop-Process	| kill, spps	| Stops one or more running processes.	| Cmdlet	|
| Start-Service	| sasv	| Starts one or more stopped services.	| Cmdlet	|
| Unblock-File	| 	| Unblocks files that were downloaded from the Internet.	| Cmdlet	|
| Get-Disk	| 	| Gets one or more disks visible to the operating system.	| Function	|
| Get-Module	| gmo	| Gets the modules that have been imported or that can be imported into the current session.	| Cmdlet	|
| ConvertTo-Json	| 	| Converts an object to a JSON-formatted string.	| Cmdlet	|
| New-WebServiceProxy	| 	| Creates a Web service proxy object that lets you use and manage the Web service in Windows PowerShell.	| Cmdlet	|
| Reset-ComputerMachinePassword	| 	| Resets the machine account password for the computer.	| Cmdlet	|
| Get-ScheduledTask	| 	| Gets the task definition object of a scheduled task that is registered on the local computer.	| Function	|
| Write-EventLog	| 	| Writes an event to an event log.	| Cmdlet	|
| Set-Service	| 	| Starts, stops, and suspends a service, and changes its properties.	| Cmdlet	|
| Out-String	| 	| Sends objects to the host as a series of strings.	| Cmdlet	|
| Get-Printer	| 	| Retrieves a list of printers installed on a computer.	| Function	|
| Out-Null	| 	| Deletes output instead of sending it down the pipeline.	| Cmdlet	|
| Resolve-DnsName	| 	| undefined	| Cmdlet	|
| Get-WindowsUpdateLog	| 	| Merges Windows Update .etl files into a single log file.	| Function	|
| Restart-Service	| 	| Stops and then starts one or more services.	| Cmdlet	|
| Set-Variable	| set, sv	| Sets the value of a variable. Creates the variable if one with the requested name does not exist.	| Cmdlet	|
| Compress-Archive	| 	| Creates an archive, or zipped file, from specified files and folders.	| Function	|
| ConvertFrom-Json	| 	| Converts a JSON-formatted string to a custom object.	| Cmdlet	|
| New-SmbShare	| 	| Creates an SMB share.	| Function	|
| Set-Item	| si	| Changes the value of an item to the value specified in the command.	| Cmdlet	|
| Update-Help	| 	| Downloads and installs the newest help files on your computer.	| Cmdlet	|
| Group-Object	| group	| Groups objects that contain the same value for specified properties.	| Cmdlet	|
| Start-BitsTransfer	| 	| Creates a BITS transfer job.	| Cmdlet	|
| Get-Certificate	| 	| Submits a certificate request to an enrollment server and installs the response or retrieves a certificate for apreviously submitted request.	| Cmdlet	|
| Register-ScheduledTask	| 	| Registers a scheduled task definition on a local computer.	| Function	|
| Tee-Object	| tee	| Saves command output in a file or variable and also sends it down the pipeline.	| Cmdlet	|
| Test-ComputerSecureChannel	| 	| Tests and repairs the secure channel between the local computer and its domain.	| Cmdlet	|
| Measure-Command	| 	| Measures the time it takes to run script blocks and cmdlets.	| Cmdlet	|
| ConvertFrom-SecureString	| 	| Converts a secure string to an encrypted standard string.	| Cmdlet	|
| Get-Job	| gjb	| Gets Windows PowerShell background jobs that are running in the current session.	| Cmdlet	|
| Export-Clixml	| 	| Creates an XML-based representation of an object or objects and stores it in a file.	| Cmdlet	|
| ConvertTo-Csv	| 	| Converts objects into a series of comma-separated value (CSV) variable-length strings.	| Cmdlet	|
| Remove-AppxProvisionedPackage	| 	| Removes an app package (.appx) from a Windows image.	| Cmdlet	|
| New-ItemProperty	| 	| Creates a new property for an item and sets its value.	| Cmdlet	|
| Get-PhysicalDisk	| 	| Gets a list of all PhysicalDisk objects visible across any available Storage Management Providers, or optionally afiltered list.	| Function	|
| Set-TimeZone	| 	| Sets the system time zone to a specified time zone.	| Cmdlet	|
| Get-Package	| 	| Returns a list of all software packages that have been installed by using Package Management.	| Cmdlet	|
| Get-SmbShare	| 	| Retrieves the SMB shares on the computer.	| Function	|
| Get-Variable	| gv	| Gets the variables in the current console.	| Cmdlet	|
| Add-Printer	| 	| Adds a printer to the specified computer.	| Function	|
| Resolve-Path	| rvpa	| Resolves the wildcard characters in a path, and displays the path contents.	| Cmdlet	|
| Select-Xml	| 	| Finds text in an XML string or document.	| Cmdlet	|
| Get-Random	| 	| Gets a random number, or selects objects randomly from a collection.	| Cmdlet	|
| Get-PSDrive	| gdr	| Gets drives in the current session.	| Cmdlet	|
| Expand-Archive	| 	| Extracts files from a specified archive (zipped) file.	| Function	|
| Receive-Job	| rcjb	| Gets the results of the Windows PowerShell background jobs in the current session.	| Cmdlet	|
| New-NetFirewallRule	| 	| Creates a new inbound or outbound firewall rule and adds the rule to the target computer.	| Function	|
| New-NetIPAddress	| 	| Creates and configures an IP address.	| Function	|
| Get-NetIPAddress	| 	| Gets the IP address configuration.	| Function	|
| Register-ObjectEvent	| 	| Subscribes to the events that are generated by a Microsoft .NET Framework object.	| Cmdlet	|
| Get-SmbConnection	| 	| Retrieves the connections established from the SMB client to the SMB servers.	| Function	|
| New-TimeSpan	| 	| Creates a TimeSpan object.	| Cmdlet	|
| Enable-WindowsOptionalFeature	| 	| Enables a feature in a Windows image.	| Cmdlet	|
| Set-NetConnectionProfile	| 	| Changes the network category of a connection profile.	| Function	|
| New-ScheduledTaskTrigger	| 	| Creates a scheduled task trigger object.	| Function	|
| Rename-Computer	| 	| Renames a computer.	| Cmdlet	|
| Get-Event	| 	| Gets the events in the event queue.	| Cmdlet	|
| Test-WSMan	| 	| Tests whether the WinRM service is running on a local or remote computer.	| Cmdlet	|
| Get-AppxProvisionedPackage	| 	| Gets information about app packages (.appx) in an image that will be installed for each new user.	| Cmdlet	|
| Wait-Process	| 	| Waits for the processes to be stopped before accepting more input.	| Cmdlet	|
| Wait-Job	| wjb	| Suppresses the command prompt until one or all of the Windows PowerShell background jobs running in the sessionare completed.	| Cmdlet	|
| Write-Debug	| 	| Writes a debug message to the console.	| Cmdlet	|
| Import-Certificate	| 	| Imports one or more certificates into a certificate store.	| Cmdlet	|
| New-EventLog	| 	| Creates a new event log and a new event source on a local or remote computer.	| Cmdlet	|
| Get-Host	| 	| Gets an object that represents the current host program.	| Cmdlet	|
| Invoke-WmiMethod	| 	| Calls WMI methods.	| Cmdlet	|
| Update-Script	| 	| Updates a script.	| Function	|
| New-Service	| 	| Creates a new Windows service.	| Cmdlet	|
| ConvertFrom-Csv	| 	| Converts object properties in comma-separated value (CSV) format into CSV versions of the original objects.	| Cmdlet	|
| Invoke-Item	| ii	| Performs the default action on the specified item.	| Cmdlet	|
| Enable-WSManCredSSP	| 	| Enables CredSSP authentication on a computer.	| Cmdlet	|
| Get-Unique	| gu	| Returns unique items from a sorted list.	| Cmdlet	|
| Find-Package	| 	| Finds software packages in available package sources.	| Cmdlet	|
| Out-Host	| oh	| Sends output to the command line.	| Cmdlet	|
| Format-Volume	| 	| Formats one or more existing volumes or a new volume on an existing partition.	| Function	|
| Format-Custom	| fc	| Uses a customized view to format the output.	| Cmdlet	|
| Get-SmbServerConfiguration	| 	| Retrieves the SMB server configuration.	| Function	|
| Mount-DiskImage	| 	| Mounts a previously created disk image (virtual hard disk or ISO), making it appear as a normal disk.	| Function	|
| Clear-Host	| clear, cls	| Clears the display in the host program.	| Function	|
| Start-DscConfiguration	| 	| Applies configuration to nodes.	| Cmdlet	|
| Get-SmbOpenFile	| 	| Retrieves basic information about the files that are open on behalf of the clients of the SMB server.	| Function	|
| Add-VpnConnection	| 	| Adds a VPN connection to the Connection Manager phone book.	| Function	|
| Set-DnsClientServerAddress	| 	| Sets DNS server addresses associated with the TCP/IP properties on an interface.	| Function	|
| Export-ModuleMember	| 	| Specifies the module members that are exported.	| Cmdlet	|
| Get-PSSession	| gsn	| Gets the Windows PowerShell sessions on local and remote computers.	| Cmdlet	|
| Get-PSSnapin	| 	| Gets the Windows PowerShell snap-ins on the computer.	| Cmdlet	|
| Get-NetConnectionProfile	| 	| Gets a connection profile.	| Function	|
| Get-NetFirewallRule	| 	| Retrieves firewall rules from the target computer.	| Function	|
| Push-Location	| pushd	| Adds the current location to the top of a location stack.	| Cmdlet	|
| Get-Volume	| 	| Gets the specified Volume object, or all Volume objects if no filter is provided.	| Function	|
| New-NetLbfoTeam	| 	| Creates a new NIC team.	| Function	|
| Get-NetTCPConnection	| 	| Gets TCP connections.	| Function	|
| Stop-Computer	| 	| Stops (shuts down) local and remote computers.	| Cmdlet	|
| Set-StrictMode	| 	| Establishes and enforces coding rules in expressions, scripts, and script blocks.	| Cmdlet	|
| Set-NetFirewallRule	| 	| Modifies existing firewall rules.	| Function	|
| Add-AppxProvisionedPackage	| 	| Adds an app package (.appx) that will install for each new user to a Windows image.	| Cmdlet	|
| Enable-BitLocker	| 	| Enables encryption for a BitLocker volume.	| Function	|
| Get-Location	| gl, pwd	| Gets information about the current working location or a location stack.	| Cmdlet	|
| Set-NetIPInterface	| 	| Modifies an IP interface.	| Function	|
| New-VirtualDisk	| 	| Creates a new virtual disk in the specified storage pool.	| Function	|
| Remove-PSSession	| rsn	| Closes one or more Windows PowerShell sessions (PSSessions).	| Cmdlet	|
| Set-NetIPAddress	| 	| Modifies the configuration of an IP address.	| Function	|
| Register-ScheduledJob	| 	| Creates a scheduled job.	| Cmdlet	|
| Set-SmbServerConfiguration	| 	| Sets the SMB Service configuration.	| Function	|
| New-Partition	| 	| Creates a new partition on an existing Disk object.	| Function	|
| Remove-PSDrive	| rdr	| Deletes temporary Windows PowerShell drives and disconnects mapped network drives.	| Cmdlet	|
| Remove-Variable	| rv	| Deletes a variable and its value.	| Cmdlet	|
| Get-WindowsOptionalFeature	| 	| Gets information about optional features in a Windows image.	| Cmdlet	|
| Import-Clixml	| 	| Imports a CLIXML file and creates corresponding objects in Windows PowerShell.	| Cmdlet	|
| Import-PfxCertificate	| 	| Imports certificates and private keys from a Personal Information Exchange (PFX) file to the destination store.	| Cmdlet	|
| Uninstall-Package	| 	| Uninstalls one or more software packages.	| Cmdlet	|
| Set-AuthenticodeSignature	| 	| Adds an Authenticode signature to a Windows PowerShell script or other file.	| Cmdlet	|
| Set-NetAdapter	| 	| Sets the basic network adapter properties.	| Function	|
| Set-Alias	| sal	| Creates or changes an alias for a cmdlet or other command element in the current Windows PowerShell session.	| Cmdlet	|
| Set-WmiInstance	| 	| Creates or updates an instance of an existing Windows Management Instrumentation (WMI) class.	| Cmdlet	|
| Disable-WindowsOptionalFeature	| 	| Disables a feature in a Windows image.	| Cmdlet	|
| Update-Module	| 	| Downloads and installs the newest version of specified modules from an online gallery to the local computer.	| Function	|
| New-LocalUser	| 	| Creates a local user account.	| Cmdlet	|
| Mount-WindowsImage	| 	| Mounts a Windows image in a WIM or VHD file to a directory on the local computer.	| Cmdlet	|
| Get-ItemPropertyValue	| gpv	| Gets the value for one or more properties of a specified item.	| Cmdlet	|
| New-Alias	| nal	| Creates a new alias.	| Cmdlet	|
| New-JobTrigger	| 	| Creates a job trigger for a scheduled job.	| Cmdlet	|
| Get-History	| ghy, h, history	| Gets a list of the commands entered during the current session.	| Cmdlet	|
| New-CimSession	| 	| Creates a CIM session.	| Cmdlet	|
| Get-LocalGroup	| 	| Gets the local security groups.	| Cmdlet	|
| ConvertTo-Xml	| 	| Creates an XML-based representation of an object.	| Cmdlet	|
| New-PSSessionOption	| 	| Creates an object that contains advanced options for a PSSession.	| Cmdlet	|
| Add-WindowsCapability	| 	| Installs a Windows capability package on the specified operating system image.	| Cmdlet	|
| New-Variable	| nv	| Creates a new variable.	| Cmdlet	|
| Convert-Path	| cvpa	| Converts a path from a Windows PowerShell path to a Windows PowerShell provider path.	| Cmdlet	|
| Get-LocalGroupMember	| 	| Gets members from a local group.	| Cmdlet	|
| Add-WindowsPackage	| 	| Adds a single .cab or .msu file to a Windows image.	| Cmdlet	|
| Invoke-CimMethod	| 	| Invokes a method of a CIM class.	| Cmdlet	|
| ConvertFrom-String	| CFS	| Extracts and parses structured properties from string content.	| Cmdlet	|
| Export-Certificate	| 	| Exports a certificate from a certificate store into a file.	| Cmdlet	|
| Unregister-ScheduledTask	| 	| Unregisters a scheduled task.	| Function	|
| ConvertFrom-StringData	| 	| Converts a string containing one or more key and value pairs to a hash table.	| Cmdlet	|
| Install-PackageProvider	| 	| Installs one or more Package Management package providers.	| Cmdlet	|
| Get-LocalUser	| 	| Gets local user accounts.	| Cmdlet	|
| Clear-Content	| clc	| Deletes the contents of an item, but does not delete the item.	| Cmdlet	|
| Remove-Module	| rmo	| Removes modules from the current session.	| Cmdlet	|
| Get-VpnConnection	| 	| Retrieves the specified VPN connection profile information.	| Function	|
| Export-PfxCertificate	| 	| Exports a certificate or a PFXData object to a Personal Information Exchange (PFX) file.	| Cmdlet	|
| Get-NetIPConfiguration	| 	| Gets IP network configuration.	| Function	|
| Export-WindowsDriver	| 	| Exports all third-party drivers from a Windows image to a destination folder.	| Cmdlet	|
| Grant-SmbShareAccess	| 	| Adds an allow ACE for a trustee to the security descriptor of the SMB share.	| Function	|
| Initialize-Disk	| 	| Initializes a RAW disk for first time use, enabling the disk to be formatted and used to store data.	| Function	|
| Get-NetIPInterface	| 	| Gets an IP interface.	| Function	|
| Get-PfxCertificate	| 	| Gets information about .pfx certificate files on the computer.	| Cmdlet	|
| Invoke-Pester	| 	| Invokes Pester to run all tests (files containing *.Tests.ps1) recursively under the Path	| Function	|
| Add-OdbcDsn	| 	| Adds an ODBC DSN.	| Function	|
| Format-Wide	| fw	| Formats objects as a wide table that displays only one property of each object.	| Cmdlet	|
| Get-Partition	| 	| Returns a list of all partition objects visible on all disks, or optionally a filtered list using specifiedparameters.	| Function	|
| Set-Disk	| 	| Takes a Disk object or unique disk identifiers and a set of attributes, and updates the physical disk on thesystem.	| Function	|
| Get-ScheduledJob	| 	| Gets scheduled jobs on the local computer.	| Cmdlet	|
| Get-PnpDevice	| 	| Returns information about PnP devices.	| Function	|
| Get-Tpm	| 	| Gets an object that contains information about a TPM.	| Cmdlet	|
| Disable-NetAdapterBinding	| 	| Disables a binding to a network adapter.	| Function	|
| Get-PSRepository	| 	| Gets PowerShell repositories.	| Function	|
| Out-Default	| 	| Sends the output to the default formatter and to the default output cmdlet.	| Cmdlet	|
| Add-PrinterDriver	| 	| Installs a printer driver on the specified computer.	| Function	|
| Set-WinUserLanguageList	| 	| Sets the language list and associated properties for the current user account.	| Cmdlet	|
| Get-ScheduledTaskInfo	| 	| Gets run-time information for a scheduled task.	| Function	|
| Enable-NetFirewallRule	| 	| Enables a previously disabled firewall rule.	| Function	|
| Out-Printer	| lp	| Sends output to a printer.	| Cmdlet	|
| Add-PrinterPort	| 	| Installs a printer port on the specified computer.	| Function	|
| Set-WinSystemLocale	| 	| Sets the system locale (the language for non-Unicode programs) for the current computer.	| Cmdlet	|
| Find-Module	| 	| Finds modules from an online gallery that match specified criteria.	| Function	|
| Get-NetAdapterVmq	| 	| Gets the VMQ properties of a network adapter.	| Function	|
| Stop-Transcript	| 	| Stops a transcript.	| Cmdlet	|
| Get-SmbSession	| 	| Retrieves information about the SMB sessions that are currently established between the SMB server and theassociated clients.	| Function	|
| Set-PSSessionConfiguration	| 	| Changes the properties of a registered session configuration.	| Cmdlet	|
| Add-MpPreference	| 	| Modifies settings for Windows Defender.	| Function	|
| Set-SmbShare	| 	| Modifies the properties of the SMB share.	| Function	|
| Set-VpnConnection	| 	| Changes the configuration settings of an existing VPN connection profile.	| Function	|
| Start-ScheduledTask	| 	| Starts one or more instances of a scheduled task.	| Function	|
| Suspend-BitLocker	| 	| Suspends Bitlocker encryption for the specified volume.	| Function	|
| Get-SmbShareAccess	| 	| Retrieves the ACL of the SMB share.	| Function	|
| Set-PSDebug	| 	| Turns script debugging features on and off, sets the trace level, and toggles strict mode.	| Cmdlet	|
| Get-StartApps	| 	| Gets the names and AppIDs of installed apps.	| Function	|
| Add-VpnConnectionRoute	| 	| Adds a route to a VPN connection.	| Function	|
| Get-VirtualDisk	| 	| Returns a list of VirtualDisk objects, across all storage pools, across all providers, or optionally a filteredsubset based on provided criteria.	| Function	|
| Write-Information	| 	| Specifies how Windows PowerShell handles information stream data for a command.	| Cmdlet	|
| New-ScheduledTask	| 	| Creates a scheduled task instance.	| Function	|
| Set-Culture	| 	| Sets the user culture for the current user account.	| Cmdlet	|
| New-ScheduledTaskSettingsSet	| 	| Creates a new scheduled task settings object.	| Function	|
| New-ScheduledTaskAction	| 	| Creates a scheduled task action.	| Function	|
| Set-Partition	| 	| Sets attributes of a partition, such as active, read-only, and offline states.	| Function	|
| Clear-Variable	| clv	| Deletes the value of a variable.	| Cmdlet	|
| Add-KdsRootKey	| 	| Generates a new root key for the Microsoft Group KdsSvc within Active Directory.	| Cmdlet	|
| Exit-PSSession	| exsn	| Ends an interactive session with a remote computer.	| Cmdlet	|
| Add-LocalGroupMember	| 	| Adds members to a local group.	| Cmdlet	|
| Set-LocalUser	| 	| Modifies a local user account.	| Cmdlet	|
| Remove-Computer	| 	| Removes the local computer from its domain.	| Cmdlet	|
| New-NetNat	| 	| Creates a NAT object.	| Function	|
| Set-SmbClientConfiguration	| 	| Sets the SMB client configuration.	| Function	|
| Set-ScheduledTask	| 	| Modifies a scheduled task.	| Function	|
| Remove-ItemProperty	| rp	| Deletes the property and its value from an item.	| Cmdlet	|
| Set-Printer	| 	| Updates the configuration of an existing printer.	| Function	|
| Set-PhysicalDisk	| 	| Sets attributes on a specific physical disk.	| Function	|
| Set-Date	| 	| Changes the system time on the computer to a time that you specify.	| Cmdlet	|
| Repair-WindowsImage	| 	| Repairs a Windows image in a WIM or VHD file.	| Cmdlet	|
| Set-NetAdapterVmq	| 	| Sets the VMQ properties of a network adapter.	| Function	|
| Remove-WmiObject	| 	| Deletes an instance of an existing Windows Management Instrumentation (WMI) class.	| Cmdlet	|
| New-NetRoute	| 	| Creates a route in the IP routing table.	| Function	|
| Optimize-Volume	| 	| Optimizes a volume.	| Function	|
| New-Volume	| 	| Creates a volume with the specified file system.	| Function	|
| New-StoragePool	| 	| Creates a new storage pool using a group of physical disks.	| Function	|
| New-SmbMapping	| 	| Creates an SMB mapping.	| Function	|
| Set-DscLocalConfigurationManager	| 	| Applies LCM settings to nodes.	| Cmdlet	|
| New-ScheduledTaskPrincipal	| 	| Creates an object that contains a scheduled task principal.	| Function	|
| Get-Culture	| 	| Gets the current culture set in the operating system.	| Cmdlet	|
| Set-PSRepository	| 	| Sets values for a registered repository.	| Function	|
| Set-NetFirewallProfile	| 	| Configures settings that apply to the per-profile configurations of the Windows Firewall with Advanced Security.	| Function	|
| Get-Alias	| gal	| Gets the aliases for the current session.	| Cmdlet	|
| Get-DnsClientServerAddress	| 	| Gets DNS server IP addresses from the TCP/IP properties on an interface.	| Function	|
| Set-MpPreference	| 	| Configures preferences for Windows Defender scans and updates.	| Function	|
| Save-Module	| 	| Saves a module locally without installing it.	| Function	|
| Resize-Partition	| 	| Resizes a partition and the underlying file system.	| Function	|
| Repair-Volume	| 	| Performs repairs on a volume.	| Function	|
| Remove-Printer	| 	| Removes a printer from the specified computer.	| Function	|
| Remove-PhysicalDisk	| 	| Removes a physical disk from a specified storage pool.	| Function	|
| Remove-NetIPAddress	| 	| Removes an IP address and its configuration.	| Function	|
| Register-PSRepository	| 	| Registers a PowerShell repository.	| Function	|
| Get-WindowsCapability	| 	| Gets Windows capabilities for an image or a running operating system.	| Cmdlet	|
| Get-BitLockerVolume	| 	| Gets information about volumes that BitLocker can protect.	| Function	|
| Get-Clipboard	| 	| Gets the current Windows clipboard entry.	| Cmdlet	|
| Get-ComputerInfo	| 	| Gets a consolidated object of system and operating system properties.	| Cmdlet	|
| Get-InitiatorPort	| 	| Gets one or more host bus adapter (HBA) initiator ports.	| Function	|
| Get-BitsTransfer	| 	| Gets the associated BitsJob object for an existing BITS transfer job.	| Cmdlet	|
| Get-AuthenticodeSignature	| 	| Gets information about the Authenticode signature for a file.	| Cmdlet	|
| Get-AppvClientPackage	| 	| Returns App-V Client Packages.	| Cmdlet	|
| Set-WSManQuickConfig	| 	| Configures the local computer for remote management.	| Cmdlet	|
| New-Guid	| 	| Creates a GUID.	| Function	|
| Get-StorageJob	| 	| Returns information about long-running Storage module jobs, such as a repair task.	| Function	|
| Uninstall-Module	| 	| Uninstalls a module.	| Function	|
| Get-InstalledModule	| 	| Gets installed modules on a computer.	| Function	|
| Confirm-SecureBootUEFI	| 	| Confirms that Secure Boot is enabled by checking the Secure Boot status on the local computer.	| Cmdlet	|
| Set-Clipboard	| 	| Sets the current Windows clipboard entry.	| Cmdlet	|
| Get-TlsCipherSuite	| 	| Gets the list of cipher suites for TLS for a computer.	| Cmdlet	|
| Clear-Disk	| 	| Cleans a disk by removing all partition information and un-initializing it, erasing all data on the disk.	| Function	|


## License
The content of this project itself is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](LICENSE).
