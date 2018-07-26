# osm_guidelines
Guidelines to write osm ansible roles

This is WIP, we will keep on updating this Guidelines page over the period of time.

## README Guidelines
* It should have owner information i.e Name & Opstree Mail id
* Requirements should be clearly defined with plan i.e
  * Operating System supported    
* Pre requisite should be clearly mentioned
* Usage instructions with all possible scenarios


## Coding Guidelines
* You should use standard directory structure of Ansible role
  ```ansible-galaxy init <rolename>```
* Prechecks required for any package installation
* If shell command is to be used then there should be some guard pattern for idempotency.
* Maximum use of ansible module
* Role should not be os dependent
* Readme must be there along with a brief snippet of code that shows
* Plain text password shouldn't be there in any roles/yml files rather ansible vault must be used
* You should write test cases for your role as well(Futuristic)
