# ansible-role-packages

A generic role to install packages on Debian (deb) based and Red Hat (RPM) based systems.

You can enable full system package upgrades to latest by enabling 

```
full_update_apt_packages: False
full_update_yum_packages: False
```

To provide a list of packages to install use:

```
debian_package_list:
  - ""
redhat_package_list:
  - ""
```