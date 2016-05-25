# ansible-api
A restful http api for ansible 2.x

## What is it?
[Ansible] (https://github.com/ansible/ansible/) is a radically simple IT automation system. 
If you are triing to use it and not like CLI mode, you can try me now. This is a http api for ansible

## How to install
choose your ansble version folder, and copy files to your disk.

- bin/ansible-api --> /usr/bin/ansible-api
- lib/* --> /usr/lib/python2.x/site-packages/ansible-2.2.0-py2.x.egg/

## How to use it

- start in deamon mode: ansible-api -d > /dev/null &
- start in debug mode: ansible-api
- configuration: edit file 'bin/ansible-api' at 'config part'

## Why need to modify ansible core code

I modified these code for getting more useful data in return, then you can do more actions according to return data.
Of course, you can diff the codes. I just added a private variate to record details in process and deal with them at last.
