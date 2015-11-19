Role Name
=========

An Ansible Role that installs Varnish on Debian Linux.

Requirements
------------

The project is using parts of the debops Project

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

tbd

Dependencies
------------

debops.secret
debops.ferm
debops.tcpwrappers

Example Playbook
----------------

The default settings assume varnish to be run on the same server as the webserver.
Varnish by default will listen to any ip address on port 6081 and forwards all requests to localhost port 8080
Be sure to set those variables to fit your needs. I will add some working examples below.

tbd

License
-------


Author Information
------------------
