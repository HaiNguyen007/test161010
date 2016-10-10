---
title: Tài liệu không có tiêu đề
layout: post
author: hai
permalink: /tài-liệu-không-có-tiêu-đề/
source-id: 1qhpltholekrcpAc4JrGuRntaXmsUr_CwaoDUiMCFmuQ
published: true
---
**Version 5.04 (29th July 2016)**

* Updated the phpMyAdmin script installer to versions 4.6.2 and 4.4.15.6.

* SSL versions 2 and 3 and TLS versions 1.0 and 1.0 are disabled by default in the Apache configuration for new domains.

* In the post-installation wizard, if Virtualmin does not know the current MySQL pasword the admin will be prompted to enter it.

* Added a config option to redirect HTTP requests to HTTPS for new domains (if they have an SSL website enabled).

* Backups can now be deleted either from the Backup Logs page, or using the delete-backup API command.

**Version 5.03 (15th May 2016)**

* More bugfixes for Ubuntu 16 and PHP 7 support.

**Version 5.02 (April 2016)**

* Added a new script installer for Rainloop version 1.9.4.415.

* Added the generate-letsencrypt-cert API command, to request and install a cert from Let's Encrypt.

* Fixed support for mail server settings autodiscovery for Outlook clients.

* Added a Virtualmin Configuration setting to request a Let's Encrypt certificate at virtual server creation time.

* Improved support for Ubuntu 16 and MySQL 5.7.

