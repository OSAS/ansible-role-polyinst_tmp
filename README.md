This role setup a polyinstantiated /tmp directory, as described in [PAM documentation](http://www.linux-pam.org/Linux-PAM-html/sag-pam_namespace.html), 
or on [RHEL documentation](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Security-Enhanced_Linux/polyinstantiated-directories.html)

The goal is to prevent a whole class of attack based on shared /tmp and predictable name, especially on shared computers where multiple
user have access.

The role do not requires any configuration, and should just be deployed on a system to be used.

[![Build Status](https://travis-ci.org/OSAS/ansible-role-polyinst_tmp.svg?branch=master)](https://travis-ci.org/OSAS/ansible-role-polyinst_tmp)
