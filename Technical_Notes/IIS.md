# Static webserver Vs Dynamic webserver (website).
	Dynamic website: webpages that changes always(JavaScript for example),
					 always refer to a Database.
					 slow recovery.
					 easy maintain.
					 
	static: like html pages, when changed it must be uploaded again.
			no interaction with user.
			fast recovery.
			Difficult to maintain.
			
# Application Server: 
	Publish app on IIS to serve on webpage

# Security
	Most needed for web administration.

# Top-Level Domains(TLDS):
	.net .org .com .me
	com: commercial
	net: network
	org: organization
	new TLDS: .movie .love ....etc
	
# IIS Settings:
	Default Document: websites in order to select for iis service.
	site binding: refers to site ip and protocol to access it.
	ApplicationPool: setting for application running on web like asp.net, ApplicationPool version in the .net version used.
	you can convert a website to application pool.
	FTP: is accessed by username and password in server/machine installed on it.
	FTP Server: can be managed by website/CMD/Client app like filezilla.
	FTP: port 20,21 , one for data control, the other for upload.
	You can connect to ftp using windows explorer.
	You can use filezilla to access ftp server or to create one.
	SSL: uses certificate authorized by ICANN to encrypt http packets to connet https.
	ssl certificate is nothing but encryption keys authorized by an organization, and always renewed
	to be used exclusively.
	you can create your own certificate but you have to authorize it by ICANN,
	as webroswer trust only certain certificates.
	CSR: a file contains your server and public key to create private key.
	CSR file is uploaded to the certificate to be used to connect to your site.

* Performance monitor: can be used to track your site traffic.
* any transaction in webpages saved in a log file.	
* Computer name is linked to mac address and can be renamed after webserver name but not recommended for security reason.
* sitename in iis only for organizing not for use as a link.
* you can use either ports or hostnames to publish multiple websites on same server.
* hostnames can be changed in hosts file or DNS server.
* hosts file is the first step to look for DNS server.
* google uses different ip addresses change periodically to make load balance.
