# Table of contents
* [RHCSA](rhcsa/README.md)
	* [Understand and Use Essential tools](rhcsa/01.Understand_And_Use_Essential_tools/README.md)
		* [Access a shell prompt and issue commands with correct syntax](rhcsa/01.Understand_And_Use_Essential_tools/01.Access_Shell_Issue_Commands.md)
		* [Use input-output redirection (>, >>, |, 2>, etc.)](rhcsa/01.Understand_And_Use_Essential_tools/02.Input_Output_Redirection.md)
		* [Use grep and regular expressions to analyze text](rhcsa/01.Understand_And_Use_Essential_tools/03.Grep_Regex.md)
		* [Access remote systems using ssh](rhcsa/01.Understand_And_Use_Essential_tools/04.SSH.md)
		* [Log in and switch users in multiuser targets](rhcsa/01.Understand_And_Use_Essential_tools/05.Multiuser_Target.md)
		* [Archive, compress, unpack, and uncompress files using tar, star, gzip, and bzip2](rhcsa/01.Understand_And_Use_Essential_tools/06.Archive_Compress_Unpack_Uncompress.md)
		* [Create and Edit Text Files](rhcsa/01.Understand_And_Use_Essential_tools/07.Create_Edit_Files.md)
		* [Create, delete, copy, and move files and directories
	](rhcsa/01.Understand_And_Use_Essential_tools/08.Create_Del_Copy_Move_Files_Dirs.md)
		* [Create hard and soft links](rhcsa/01.Understand_And_Use_Essential_tools/09.Hard_Soft_Links.md)
		* [List, set, and change standard ugo/rwx permissions
	](rhcsa/01.Understand_And_Use_Essential_tools/10.File_Permissions.md)
		* [Locate, read, and use system documentation including man, info, and files in /usr/share/doc](rhcsa/01.Understand_And_Use_Essential_tools/11.Using_Sys_Doc.md)


	* [Operate Running Systems](rhcsa/02.Operate_Running_Systems/README.md)
		* [Boot, reboot, and shut down a system normally](rhcsa/02.Operate_Running_Systems/01.Reboot_Shutdown.md)
		* [Boot systems into different targets manually](rhcsa/02.Operate_Running_Systems/02.Change_Targets.md)
		* [Interrupt the boot process in order to gain access to a system](rhcsa/02.Operate_Running_Systems/03.Reset_Root_Pwd_At_Boot.md)
		* [Identify CPU/memory intensive processes, adjust process priority with renice, and kill processes](rhcsa/02.Operate_Running_Systems/04.Process_management.md)
		* [Locate and interpret system log files and journals](rhcsa/02.Operate_Running_Systems/05.Logs.md)
		* [Access a virtual machine's console](rhcsa/02.Operate_Running_Systems/06.Access_VM_Console.md)
		* [Start and stop virtual machines](rhcsa/02.Operate_Running_Systems/07.Start_Stop_VM.md)
		* [Start, stop, and check the status of network services](rhcsa/02.Operate_Running_Systems/08.Manage_Network_Services.md)
		* [Securely transfer files between systems](rhcsa/02.Operate_Running_Systems/09.Securely_xfer_files.md)

	* [Configure Local Storage](rhcsa/03.Configure_Local_Storage/README.md)
		* [List, create, delete partitions on MBR and GPT disks](rhcsa/03.Configure_Local_Storage/01.Partition_Management.md)
		* [Create and remove physical volumes, assign physical volumes to volume groups, and create and delete logical volumes](rhcsa/03.Configure_Local_Storage/02.LVM.md)
		* [Configure systems to mount file systems at boot by Universally Unique ID (UUID) or label](rhcsa/03.Configure_Local_Storage/03.UUID_Label_Mount.md)
		* [Add new partitions and logical volumes, and swap to a system non-destructively](rhcsa/03.Configure_Local_Storage/04.Add_Parts_LV.md)

	* [Create and Configure Files Systems](rhcsa/04.Create_And_Configure_File_Systems/README.md)
		* [Create, mount, unmount, and use vfat, ext4, and xfs file systems](rhcsa/04.Create_And_Configure_File_Systems/01.Create_Mount_FS.md)
		* [Mount and unmount CIFS and NFS network file systems](rhcsa/04.Create_And_Configure_File_Systems/02.Network_Mounts.md)
		* [Extend existing logical volumes](rhcsa/04.Create_And_Configure_File_Systems/03.Extend_LV.md)
		* [Create and configure set-GID directories for collaboration](rhcsa/04.Create_And_Configure_File_Systems/04.Set_GID.md)
		* [Create and manage Access Control Lists (ACLs)](rhcsa/04.Create_And_Configure_File_Systems/05.ACLs.md)
		* [Diagnose and correct file permission problems](rhcsa/04.Create_And_Configure_File_Systems/06.TS_Permission.md)

	* [Deploy and Configure and Maintain Systems](rhcsa/05.Deploy_Configure_And_Maintain_Systems/README.md)
		* [Configure networking and hostname resolution statically or dynamically](rhcsa/05.Deploy_Configure_And_Maintain_Systems/01.Conf_Network.md)
		* [Schedule tasks using at and cron](rhcsa/05.Deploy_Configure_And_Maintain_Systems/02.Cron.md)
		* [Start and stop services and configure services to start automatically at boot](rhcsa/05.Deploy_Configure_And_Maintain_Systems/03.Boot_Process_MGT.md)
		* [Configure systems to boot into a specific target automatically](rhcsa/05.Deploy_Configure_And_Maintain_Systems/04.Boot_Target.md)
		* [Install Red Hat Enterprise Linux systems as virtual guests](rhcsa/05.Deploy_Configure_And_Maintain_Systems/05.Install_VM.md)
		* [Configure systems to launch virtual machines at boot](rhcsa/05.Deploy_Configure_And_Maintain_Systems/06.VM_At_Boot.md)
		* [Configure network services to start automatically at boot](rhcsa/05.Deploy_Configure_And_Maintain_Systems/07.Net_At_Boot.md)
		* [Configure a system to use time services](rhcsa/05.Deploy_Configure_And_Maintain_Systems/08.time.md)
		* [Install and update software packages from Red Hat Network, a remote repository, or from the local file system](rhcsa/05.Deploy_Configure_And_Maintain_Systems/09.Package_Management.md)
		* [Update the kernel package appropriately to ensure a bootable system](rhcsa/05.Deploy_Configure_And_Maintain_Systems/10.Kernel_Update.md)
		* [Modify the system bootloader](rhcsa/05.Deploy_Configure_And_Maintain_Systems/11.Bootloader.md)

	* [Manage Users and Groups](rhcsa/06.Manage_Users_And_Groups/README.md)
		* [Create, delete, and modify local user accounts](rhcsa/06.Manage_Users_And_Groups/01.UserAcc.md)
		* [Change passwords and adjust password aging for local user accounts](rhcsa/06.Manage_Users_And_Groups/02.passwd.md)
		* [Create, delete, and modify local groups and group memberships](rhcsa/06.Manage_Users_And_Groups/03.groups.md)
		* [Configure a system to use an existing authentication service for user and group information](rhcsa/06.Manage_Users_And_Groups/04.Auth_srv.md)


	* [Manage Security](rhcsa/07.Manage_Security/README.md)
		* [Configure firewall settings using firewall-config, firewall-cmd, or iptables](rhcsa/07.Manage_Security/01.Firewall.md)
		* [Configure key-based authentication for SSH](rhcsa/07.Manage_Security/02.Key_SSH.md)
		* [Set enforcing and permissive modes for SELinux](rhcsa/07.Manage_Security/03.SELinux_Modes.md)
		* [List and identify SELinux file and process context](rhcsa/07.Manage_Security/04.SELinux_Context.md)
		* [Restore default file contexts](rhcsa/07.Manage_Security/05.Restore_Context.md)
		* [Use boolean settings to modify system SELinux settings](rhcsa/07.Manage_Security/06.SELinux_Bool.md)
		* [Diagnose and address routine SELinux policy violations](rhcsa/07.Manage_Security/07.TS_SELinux.md)



* [selinux](README.md)

