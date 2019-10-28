# Install the ownCloud Server


When you have downloaded the correct software for your site, there are two ways to install:

1. With [Docker](https://doc.owncloud.org/server/10.3/admin_manual/installation/docker/). 
2. Manually, from the [command line]((https://doc.owncloud.com/server/10.3/admin_manual/installation/manual_installation.htm)). 


## Docker Installation

When you install the official [OwnCloud Docker image](https://hub.docker.com/r/owncloud/server/) on a local machine, you will create a short configuration file. Be sure the file has the .env extension. 

Part of this file's settings defines the admin username, password, and HTTP port. You'll need these designations to access your ownCloud server. Also, since this .env file has important security content for your site, make sure it is not easily available to unqualified users.

## Manual Installation 

As noted, if you are not using a Docker installation, you can download the correct packages for your system and perform the installation directly from the command line. 

There are many steps to this process, and you'll need to follow the full set of documented tasks carefully, as described [here](https://doc.owncloud.com/server/10.3/admin_manual/installation/manual_installation.htm).
 
---
__NOTE__

Information about the [Installation Wizard](https://doc.owncloud.org/server/10.3/admin_manual/installation/installation_wizard.html), and the [Command Line Installation](https://doc.owncloud.com/server/10.3/admin_manual/installation/command_line_installation.html), along with an [Ubuntu example](https://doc.owncloud.com/server/10.3/admin_manual/installation/ubuntu_18_04.html), each supply detailed installation directions in the main ownCloud documents. We recommend that you review all of these sections for further background information.

---

## Multiple Server Installations 

If your site requires that you perform multiple server installations, ownCloud includes an automatic configuration feature. By creating a configuration file, and setting the required file parameters, you can install multiple versions of the server. Learn more about about the [configuration file settings and parameters](https://doc.owncloud.org/server/10.3/admin_manual/configuration/server/automatic_configuration.html) at this location. 


## Where ownCloud Stores Data 

Since one of the main reasons for using ownCloud is to centralize and share data for your team or organizaiton, understanding about data storage is key. 

---
__NOTE__

In the current Admin guide, two different sections exist about External storage, as follows: 

* [Admin Manual > Configuration > External Storage](https://doc.owncloud.org/server/10.3/admin_manual/configuration/files/external_storage/)
* [Admin Manual > Enterprise > External Storage](https://doc.owncloud.org/server/10.3/admin_manual/enterprise/external_storage/)

We recommend that you check both of these sections to see what matches your site needs most closely. 

---

For example, while many sites use external storage, here is the list of topics available in the enterprise External Storage section:  

*  [LDAP](https://doc.owncloud.org/server/10.3/admin_manual/enterprise/external_storage/ldap_home_connector_configuration.html)  
*  [OneDrive](https://doc.owncloud.org/server/10.3/admin_manual/enterprise/external_storage/onedrive.html)
*  [S3 Swift](https://doc.owncloud.org/server/10.3/admin_manual/enterprise/external_storage/s3_swift_as_primary_object_store_configuration.html)
* [Sharepoint Integration](https://doc.owncloud.org/server/10.3/admin_manual/enterprise/external_storage/sharepoint-integration_configuration.html)
* [Windows Network Drives](https://doc.owncloud.org/server/10.3/admin_manual/enterprise/external_storage/windows-network-drive_configuration.html)

## Other Tasks After Installation

This Quick Guide describes the basic parts of installing your ownCloud server. However, we have not discussed other, more advanced topics, such as supported applications, SELinux, and other security and encryption requirements. Following are links to some various topics beyond those described here: 

Topic |  Location  
----- |  ------
Configuration | [Configuration Notes and Tips](https://doc.owncloud.com/server/10.3/admin_manual/installation/configuration_notes_and_tips.html)
SELinux | [Considerations for Configuration](https://doc.owncloud.com/server/10.3/admin_manual/installation/selinux_configuration.html)
SSL | [Using Let's Encrypt SSL ](https://doc.owncloud.com/server/10.3/admin_manual/installation/letsencrypt/using_letsencrypt.html)
Apache | [Configure Apache](https://doc.owncloud.com/server/10.3/admin_manual/installation/letsencrypt/apache.html)
Database Conversion | [Converting Database Type](https://doc.owncloud.com/server/10.3/admin_manual/configuration/database/db_conversion.html)
Configuring Database | [Database Configuration](https://doc.owncloud.com/server/10.3/admin_manual/configuration/database/linux_database_configuration.html)
Managing Encryption | [Encryption Tasks](https://doc.owncloud.com/server/10.3/admin_manual/configuration/files/encryption/root.html)
File | [Managing Files](https://doc.owncloud.com/server/10.3/admin_manual/configuration/files/)

