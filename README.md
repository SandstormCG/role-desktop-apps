desktop-apps
=========

Ansible galaxy role for desktop apps & configs

Role Variables
--------------

* bulk_packages --> Array with package names to install. Example:
      `bulk_packages: ["package1","package2","package2"]`
* yay_packages --> Array with packages to install through yay. Example: 
      `yay_packages: ["package1","package2","package3"]`
* user --> Username for the installation user
* vm_name --> VM name in qemu for gpu passthrough (qemu.j2)

License
-------

Yet to be determined

Author Information
------------------

[Sandstorm](https://github.com/SandstormCG)

