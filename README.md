# osm_guidelines
Guidelines to write osm ansible roles

* Prechecks required for any package installation
* If shell command is to be used then there should be some guard pattern for idempotency
* Maximum use of ansible module
* Role should not be os dependent
* Readme must be there along with a brief snippet of code that shows
* Plain text password shouldn't be there in any roles/yml files rather ansible vault must be used
