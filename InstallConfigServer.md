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

Information about the [Installation Wizard](https://doc.owncloud.org/server/10.3/admin_manual/installation/installation_wizard.html), and the [Command Line Installation](https://doc.owncloud.com/server/10.3/admin_manual/installation/command_line_installation.html), along with an [Ubuntu example](https://doc.owncloud.com/server/10.3/admin_manual/installation/ubuntu_18_04.html), all follow the detailed installation directions. We recommend that you review all of these sections for further background information.

---

## Other Tasks Following Installation

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

