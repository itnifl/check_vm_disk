check_vm_disk
==================

Initial Comments
----------------

 This system uses vSphere-Perl-SDK to check ESXi VM guest free disk space and is tested on Ubuntu 16.04 LTS for use as a Nagios plugin.


Prerequisites
-------------
For the full functionality of the code, the following prerequisites must be in order:

	1. VMware-vSphere-Perl-SDK-6.0.0-3561779.x86_64.tar.gz

Installing Prerequisites
------------------------
See corresponding guides for the various prerequisites. These guides are not provided here.

Installing
----------
* Place with the other Nagios plugins (for instance: /usr/lib/nagios/plugins/).
* Make sure Nagios has access rights to execute the plugin (for instance chmod 755 /usr/lib/nagios/plugins/check_vm_disk.pl).
* Take in use with your Nagios system

Upgrading
---------
* Pull from repository and place correctly in your Nagios system.

Removing
--------
Delete this script from your system.

Maintainers
-----------
Current maintainers of this plugin:

Atle Holm (atle@team-holm.net)
