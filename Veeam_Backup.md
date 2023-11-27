## Backup Notes:

* Incremental backup: changes since last full backup.
* Incremental backup is always added to full backup. (incremental backup needs full backup to operate)
* Reverse Incremental backup: full backup is sooner and incremental backups are far away like every week for a year ago.
* Reverse incremental backup is not very common.
* Differential backup: changes since last full backup.
* Always backup on different media on different site.
* Repository Server can be a VM or Physical.
* NAS ex: CIFS, NFS and SMB.
* SAN ex: FC, ISCSI.
* You Can always install veeam on server and install veeam console on your pc for more performance and access remotely.
* Object Storage like amazon S3, azure Blob storage.
* VEEAM can backup SQL Transactions.
* backup retention is to backup files up to 14 days only and in day 15 the first day will be merged with second day exactly like cctv recording.
* Every backup process is given duration to finish but not always accurate.
* VEEAM free - backup and replication only
	Backup Strategy:
		3 2 1 Strategy:
			3 copies of data (production - backup - another backup)
			2 Different Media
			1 offsite
		
		3 2 1 0 Strategy:
