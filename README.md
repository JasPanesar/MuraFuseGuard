MuraFuseGuard
======================

The FuseGuard Web Application Firewall for ColdFusion is a set of code designed to run inside your existing CFML web applications to block, filter, or log potentially malicious requests.

Installation is as simple as adding a few lines of code to your Application.cfm or Application.cfc file, and optionally creating a database (see the install.txt file for details). Configuration, and all of the actual filtering, is done with ColdFusion so you don't need to learn a new XML language or complicated user interfaces. The Foundeo WAF (Web Application Firewall) is designed for easy implementation and extension

REQUIRES:
Adobe ColdFusion 9 or 10
Railo 3 and up
Mura Core Version 6.0.5345 and up

This plugin connects a Mura to an existing FuseGuard instance. So you must first configure FuseGuard on your webserver before using this plugin. To do this:

1. You must purchase FuseGuard.
2. Place the fuseguard package in your web root.
3. Configure FuseGuard.  It does not need to use the same datasource.
4. Install this plugin.


For more details please visit the following URL:

http://foundeo.com/security/
