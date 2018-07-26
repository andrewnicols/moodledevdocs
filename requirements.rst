Requirements
============

Moodle has support for a wide range of server environments, and supports a wide range of client-side browsers.

The exact versions supported change from version to version, but the general support statements are described here.

Supported Versions of PHP
=========================

Since Moodle 3.5 (MDL-59159), these rules apply to decide the Minimum PHP and Moodle versions supported:

#. A LTS will always require the previous LTS (or later) for upgrading.
#. The maximum PHP version supported for a branch will be the max one achieved along the life of the branch. Usually with .0 releases but may happen later (we added support for php70 with 3.0.1, for example).
#. The minimum PHP version supported for a branch will be the lower of:

  * The minimum version supported in any way by php the day of the Moodle release (so we provide slow, progressive increments).
  * The maximum PHP version supported by the previous LTS branch (so we guarantee jumping between LTS is possible without upgrading PHP at the same time).

Supported Database Servers
==========================

Moodle officially supports the following Database Engines:

* Postgres
* MariaDB
* MySQL
* MSSQL
* Oracle
