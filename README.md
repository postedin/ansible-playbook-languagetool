Ansible Playbook - languagetool
=========

<https://languagetool.org>

Uses `postedin.languagetool` role. <https://github.com/postedin/ansible-role-languagetool>

Comes with a `Vagrantfile`.

Usage
--------------

Fork the repository and clone it, instructions assume being in the playbooks directory.

Optional (skip to running the playbook if using ansible on host machine):

- `vagrant up`
- `vagrant ssh`
- `cd /vagrant`

At this point the you need to add your hosts to `ansible-config/hosts` which maps to vagrant.

Run the playbook:

- `ansible-playbook playbook.yml`
