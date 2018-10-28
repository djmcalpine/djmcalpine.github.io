ownCloud Quickstart Guide
=========================

[ownCloud](https://owncloud.org/) is a file sharing platform used to help you host your own private cloud server that allows you to do the following:

* Securely access, edit, store, and view your data files from any device, anywhere, and any time.

* Synchronize your files and folders and automatically upload your pictures and videos.

* Integrate third-party storage on to your private cloud, such as Microsoft OnDrive and Dropbox.

* Share files with others, and much more.

ownCloud Server Installation
============================

If you are an administrator, complete the following tasks to install and configure the ownCloud server.

Install the ownCloud Server
---------------------------

1. Go to the [ownCloud](https://owncloud.org/) website.
2. At the top right corner of the web page, click **Download**.
3. In the **Download** [ownCloud](https://owncloud.org/download/) web page that appears, scroll to the **ownCloud Server** section.
4. Choose from the following ownCloud server installation options and download the appropriate installation image to the system on which you are installing the ownCloud server:
   * **Tarball** - A common option for production environments. Select **Download Tar** to download the installation package.
   * **Docker** - A Docker image is a file, comprised of multiple layers, used to execute code in a Docker container. Go to the [ownCloud Server Docker image](https://github.com/owncloud-docker/server) for your Docker environment.
   * **Appliance**-A virtual appliance is a pre-integrated, self-contained system that is made by combining server software with just enough operating system for it to run optimally on industry standard hardware or a virtual machine. Click one of the following desired appliance images to download: **Download ESX image**, **Download VirtualBox image**, **Download QCOW2 image**, or **Download Vmware image**.
   * In the **Documentation** section, click [Installation Guide](https://doc.owncloud.org/server/latest/admin_manual/installation/).
5. In the [ownCloud 10.0.10 Server Administration Manual](https://doc.owncloud.org/server/latest/admin_manual/appliance/) page choose from the following navigation menu installation instruction options for ownCloud on the left side of the page:
   * Click [Installation](https://doc.owncloud.org/server/latest/admin_manual/installation/) to view linux server installation instructions. 
   * Click [The ownCloud X Appliance](https://doc.owncloud.org/server/latest/admin_manual/appliance/) to view appliance related installation instructions. 
6. Use the applicable tasks in the Installation section, to install the ownCloud server with the installation image you downloaded.

Configure the ownCloud Server
-----------------------------

1. On the [ownCloud 10.0.10 Server Administration Manual](https://doc.owncloud.org/server/latest/admin_manual/appliance/) page, click [Configuration](https://doc.owncloud.org/server/latest/admin_manual/configuration/) from the navigation menu on the left side of the page to view the ownCloud configuration instructions.
2. Use the applicable tasks in the [Configuration](https://doc.owncloud.org/server/latest/admin_manual/configuration/) section that are used to configure the ownCloud server.

Allow Users to Connect to the ownCloud Server
---------------------------------------------

Use this task to set LDAP server parameters that allow users to access the ownCloud server by way of HTTP:

1. On the [ownCloud 10.0.10 Server Administration Manual](https://doc.owncloud.org/server/latest/admin_manual/appliance/) page, click [Configuration](https://doc.owncloud.org/server/latest/admin_manual/configuration/) from the navigation menu.
2. In the expanded **Configuration** navigation menu, select [User Management](https://doc.owncloud.org/server/latest/admin_manual/configuration/user/).
3. Click [User Authentication with LDAP](https://doc.owncloud.org/server/latest/admin_manual/configuration/user/user_auth_ldap.html) to configure the LDAP server that is used to authenticate users so they can connect to the ownCloud server. In this task, the ownCloud server IP address and HTTP port (8080) can be specified.

Add a User to ownCloud and Enable Them to Connect to ownCloud
-------------------------------------------------------------

1. On the [ownCloud 10.0.10 Server Administration Manual](https://doc.owncloud.org/server/latest/admin_manual/appliance/) page, click [Configuration](https://doc.owncloud.org/server/latest/admin_manual/configuration/) from the navigation menu on the left side of the page to view the ownCloud configuration instructions.
2. In the expanded **Configuration** navigation menu, select [User Management](https://doc.owncloud.org/server/latest/admin_manual/configuration/user/).
3. In the expanded **User Management** index that appears to the right of the navigation menu, click [Creating a New User](https://doc.owncloud.org/server/latest/admin_manual/configuration/user/user_configuration.html#creating-a-new-user).
4. Follow the instructions on how to add a new user in the [Creating a New User page](https://doc.owncloud.org/server/latest/admin_manual/configuration/user/user_configuration.html#creating-a-new-user).
5. Scroll down the page to the [Managing Groups](https://doc.owncloud.org/server/latest/admin_manual/configuration/user/user_configuration.html#managing-groups) section.
6. Use the instructions there to add the user you created to a group. Once a user is assigned to a group, they can immediately access file shares that belong to their new groups.

User Client Installation
========================

If you are a user who wants to connect to ownCloud, complete the following tasks to access your user account from a desktop or mobile device.

Access Your ownCloud User Account from a Desktop
------------------------------------------------

1. Go to the [ownCloud](https://owncloud.org/) website.
2. At the top right corner of the web page, click **Download**.
3. In the [Download ownCloud web page](https://owncloud.org/download/) that appears, scroll to the **ownCloud Desktop Client** section.
4. Choose from the following ownCloud client installation options and download the appropriate installation image to the system on which you are installing the ownCloud client:
   * **ownCloud desktop client for MacOS**
   * **ownCloud desktop client for Windows**
   * **ownCloud desktop client for Linux**
5. Under the **ownCloud Desktop Client** section in the **Documentation** section, click [User Manual](https://doc.owncloud.org/desktop/latest/).
6. In the **ownCloud Client Manual page**, choose the [Installing the Desktop Synchronization Client](https://doc.owncloud.org/desktop/latest/installing.html) navigation menu on the left side of the page to view installation instructions.
7. Use the applicable tasks in the **Installing the Desktop Synchronization Client** page, to install the ownCloud client with the installation image you downloaded.

Access Your ownCloud User Account from your Mobile Device
---------------------------------------------------------

1. Go to the [ownCloud](https://owncloud.org/) website.
2. At the top right corner of the web page, click **Download**.
3. In the [Download ownCloud web page](https://owncloud.org/download/) that appears, scroll to the **ownCloud Mobile Apps** section.
4. Choose from the following ownCloud client mobile application options and download the appropriate application to the mobile device on which you are installing the ownCloud client:
   * **iOS** – Scan or select the QR code with your Apple iOS device to go to the Apple App store.
   * **Android** – Scan or select the QR code with your Android device to go to the Google Play store.
5. Under the **ownCloud Mobile Apps** section in the **Documentation** section, select from the following installation instruction options:
   * **iOS** – [iOS app manual](https://doc.owncloud.org/ios/ios<em>app.html). 
   * **Android** – [Android app manual](https://doc.owncloud.org/android/android</em>app.html).
6. Use each app manual to learn how to use the ownCloud application on your device.