correlate.localdev
=========

Sets up a power user and developer environment on target machines based on Correlate conventions.

* zsh
* keychain

Requirements
------------

None

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

#### shell_scaffold_force

    shell_scaffold_force: no 

Variable permits overwriting of ZSH scaffolding files:

    .setansiblerc
    .setbrewrc
    .setcolorrc
    .setenvrc
    .setlessrc
    .setsshrc
    .zshrc



Dependencies
------------

TBD

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: correlate.localdev }

License
-------

BSD/ MIT

Author Information
------------------

This role was adapted in 2015 by [Prez Cannady](http://github.com/OpenCorrelate)