[Drupal VM](https://www.drupalvm.com/) is a VM for Drupal, built with Ansible.

## Drupalvm tailored for Drupal 7 running on Windows 10

### To clone a single branch
git clone -b multi-aeg --single-branch https://github.com/andrewfandrew/horsepower.git

### Instructions
- Run 'vagrant up' from inside the folder
- Run 'vagrant ssh' to login to the VM
- Run drush commands from inside the VM
- In PHPStorm create a project from existing files and navigate to the drupal folder inside the drupalvm folder
### Nota bene
- Drush is version 8 which works best on drupal 7
- use 'drush cr' to clear the cache
- use 'drush en [MODULENAME]' to enable modules
- use 'drush dl [MODULENAME]' to download modules
