# Advanced file access permissions:
permissions for certain users/groups

Command | Info
--------|-----
setfacl -x filename u:user_taha:xw g:group_taha:rw | exclude or remove file permissions.
setfacl -m filename u:user:xw g:group:rw | Modify permissions.
setfacl -b filename | remove all permissions

# Scheduling tasks:

Command | Info
--------|-----
at 15:30 | take you to command written to be executed at 3:30 PM.
at -c 1 | print first task to be run in the cache.
at -l | list all tasks.
at now+3hours | after 3 hours from now.
at now+3weeks | after 3 weeks from now.
* check for atd service if running before using the command

# Firewalld:

Command | Info
--------|-----
firewall-cmd --permanent --add-source --add-port --add-service | different setting to be added to firewall list.
firewall-cmd --list-all | list all config.
firewall-cmd --new-zone zoneName | Create new zone for certain subnet in the network for example.

* Default built-in firewall for red-hat based distros.
* check for service status before using.
* Firewall zone available for every connection interface.
* Reload firewall after adding/removing/changing ports or ip`s.
* config files are saved in /etc/firewalld/zones/public.xml


# SELinux:

Command | Info
--------|----
sestatus|check selinux status
getenforce | show current mode for selinux.
setenforce (1,0)|turn on selinux
ls -z | showing files with thier security/context.
chcon -t | change file context type for selinux.
semanage fcontext -l | list all files context in selinux.
semanage port -l | list used ports by services.
semanage port -a -t http_port_t 9800 -p tcp | allow http on port 9800 tcp.

* Kernel Module for enhanced security for all applications in linux environment.
* check config file in /etc/selinux/config.

# fdisk: 

Command | Info
--------|-----
fdisk /dev/diskname | p to print disk info. 
 | o add mbr table to disk.
 | g add gpt to disk.
 | n new partition.
 | d delete partition.
 | q quit without saving.
 | w quit with saving.

* fdisk used to manage partition table of disks like MBR, GPT.

# make swap partition
* select a partition
* mkfs -t xfs /dev/part_name   //to make xfs filesystem for selected partition.
* mkswap /dev/part_name  //make swap
* swapon /dev/part_name  //activate swap.
* add swap in fstab file for permanent use.
* check your progress with command: free -m.

# Storage methods for better use of disks space: 
* Stratis: a tool used to make logical partitions to be used across all available disks (better than LVM).
# Stratis steps:
	$install stratis-cli, stratisd
	$stratis pool create pool_name /dev/sda1 /dev/sda2 ....etc.
	$stratis pool add_data pool_name /dev/sdb1  //add disk to pool.
	$stratis filesystem create pool_name partition1 //create partition1 from pool_name
	
# NFS (Network File Share):
* Centralized file server to be accessed by all clients.

# Changing root password: 
* boot into grub menu use 'e'

