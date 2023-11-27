## Networking

Bridge: vm is in network as a real pc in physical network
 		takes ip from dhcp on router can be a server accessed worldwide.

NAT: VMs are on a virtual switch and can access internet, cant be published as public ip or server.

Host : VMs communicate internally not connecting to internet

## Virtualization types 

type 1 : Bare Metal hypervisor using virtualization OS Like ESXI Server.

type 2 : using guest os like windows with SW like VM workstation.

## Snapshot Vs Clone
Snapshots save vm files like at certain time : 

		state of vm disks.
		contents of vm memory.
		VM Settings.
		
		
Clone : full copy of vm filesystem.

snaphot is very quick compared to clone.

##Storage
NAS : Storage on filesystem level.
SAN : storage on block level.

Thick provisioning : Phyiscal disk is the reserved on fixed size you determined.
Thin Provisioning : Size represented is less than actual size (Virtualization Only).
