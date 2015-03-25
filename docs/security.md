
#Application safety

##Encryption of data 
All data traffic and log-on information is encrypted with Secure Sockets layer (SSL 128-bits encryption)
[SERTIFIKAT DETALJER INN HER]

##User Identification 
Users are identified by a two-step authorization. Log in with chosen email address and receive a four digit code by sms .
Access
Users gets access to the company account only and have the rights to open every project therein.
To be able to edit a project created by another user you have to copy the project first.

##Hosting Environment

Heroku’s physical infrastructure is hosted and managed within Amazon’s secure data centers and utilize the Amazon Web Service (AWS) technology. Amazon continually manages risk and undergoes recurring assessments to ensure compliance with industry standards. Amazon’s data center operations have been accredited under:
•	ISO 27001
•	SOC 1 and SOC 2/SSAE 16/ISAE 3402 (Previously SAS 70 Type II)
•	PCI Level 1
•	FISMA Moderate
•	Sarbanes-Oxley (SOX)

##Physical Security

Heroku utilizes ISO 27001 and FISMA certified data centers managed by Amazon. Amazon has many years of experience in designing, constructing, and operating large-scale data centers. This experience has been applied to the AWS platform and infrastructure. AWS data centers are housed in nondescript facilities, and critical facilities have extensive setback and military grade perimeter control berms as well as other natural boundary protection. Physical access is strictly controlled both at the perimeter and at building ingress points by professional security staff utilizing video surveillance, state of the art intrusion detection systems, and other electronic means. Authorized staff must pass two-factor authentication no fewer than three times to access data center floors. All visitors and contractors are required to present identification and are signed in and continually escorted by authorized staff.
Amazon only provides data center access and information to employees who have a legitimate business need for such privileges. When an employee no longer has a business need for these privileges, his or her access is immediately revoked, even if they continue to be an employee of Amazon or Amazon Web Services. All physical and electronic access to data centers by Amazon employees is logged and audited routinely.
For additional information see: https://aws.amazon.com/security

##Firewall

Firewalls are utilized to restrict access to systems from external networks and between systems internally. By default all access is denied and only explicitly allowed ports and protocols are allowed based on business need.  Each system is assigned to a firewall security group based on the system’s function. Security groups restrict access to only the ports and protocols required for a system’s specific function to mitigate risk.
Host-based firewalls restrict customer applications from establishing localhost connections over the loopback network interface to further isolate customer applications. Host-based firewalls also provide the ability to further limit inbound and outbound connections as needed.

##Backup & Restore

Applications deployed to the Heroku platform are automatically backed up as part of the deployment process on secure, access controlled, and redundant storage.  We use these backups to deploy your application across our platform and to automatically bring your application back online in the event of an outage.
