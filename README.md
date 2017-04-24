Mail Toaster
============

Configuration files, scripts, and Ansible playbooks for configuration of a Postfix+Dovecot+PostfixAdmin server.

Background
==========

This configuration is part of the presentation about an email hosting server (held at the Linuxwochen Wien
and Eisenstadt in 2017). The configuration is intended to serve as a starting point for the setup. It requires
a suitable GNU/Linux based server installation, root access (via SSH, works via sudo, too), and some initial
software packages. The configuration is targetted at Debian 8, but it can be adapted to be used with other
distributions.

The software selection used is based on:

* amavisd-new
* Apache web server
* ClamAV
* Dovecot
* MySQL (MariaDB works as well and should be preferred)
* PHP
* Postfix
* Postgrey
* SpamAssassin™
