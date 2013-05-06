# Migrations
All Migrations must follow these conventions if possible:

* Migrations must have the datestamp before their name.
* Filename must be separated by underscore characters (no spaces).
* Filename must be in all lower case.
* The first word must be the action keyword (create, update, delete).
* The migration must have both an 'up' function and a 'down' function defined.