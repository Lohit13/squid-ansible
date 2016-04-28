SETTING UP SQUID PROXY ON LOCAL HOST
====================================

An ansible playbook to install and configure SQUID proxy and cache.

STEPS
=====
1. ansible-playbook squid.yml -i 'localhost', --ask-sudo-pass --extra-vars "user={{ENTER USER HERE}}"
2. run START.sh

AUTHORS
=======
Lohitaksh Parmar (2014059)
Kushagra Singh (2014056)