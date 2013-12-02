Ansible playbook for installing the graphite stack on a Debian
==============================================================

Requirements
------------

 * Ansible >= 1.4

If you want to test it before deploying it :

 * Virtualbox
 * Vagrant

Test
----

Spawn a new virtualbox :

    vagrant up

Play and replay provisioning (the Ansible playbook):

    vagrant provision

Try http://192.168.33.11:8000 and enjoy you graphite installation.

You can now test [Statsd](https://github.com/etsy/statsd/) or
[Diamond](https://github.com/BrightcoveOS/Diamond), or directly speak with carbon.

Todo
----
 * Handling strange statsd carbon consolidation
 * Use SSL authentication for carbon

