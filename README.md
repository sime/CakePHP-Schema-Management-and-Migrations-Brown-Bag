"Schema management and migrations in CakePHP" Brown Bag
=======================================================
Pollenizer 2012-02-09

### Screencast

[http://blip.tv/simonmales/cakephp-schema-management-and-migrations-brown-bag-5946713]

### Prerequisites

This exercise will be run completely from the command line. Requirements are a
working PHP-CLI executable and working MySQL database.


Ensure your database.php is appropriately configured. You can test with:

	$ ./Console/cake bake Model

Should return the following on successful configuration:

	Your database does not have any tables.

Schema commands
---------------

* `generate` schema file
	* -f param
* `create` and dump tables based on schema file
* `update` alter tables based on schema file

Caveats
-------

* Column renaming
