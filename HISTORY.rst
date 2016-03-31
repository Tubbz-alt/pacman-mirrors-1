.. :changelog:

History
-------

2.0 (2016-03-01)
---------------------

* Add translation support.
* Better error messages.
* --no-update option, to prevent updates when upgrading the package.
* Big refractor of code.
* Configuration file /etc/pacman-mirrors.conf is optional.
* Pep8 all the code in pacman_mirrors.py
* Reestructure the project.
* The Custom country created with interactive mode is now stored in /var/lib/pacman-mirrors/
* If a Custom country is found in /etc/pacman.d/mirrors/ its moved automatically to the new directory.
