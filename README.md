[![MOLECULE LINT](https://github.com/buissetemmanuel/ansible-role-kind/actions/workflows/molecule-lint.yml/badge.svg)](https://github.com/buissetemmanuel/ansible-role-kind/actions/workflows/molecule-lint.yml)
[![RELEASE](https://github.com/buissetemmanuel/ansible-role-kind/actions/workflows/release.yml/badge.svg)](https://github.com/buissetemmanuel/ansible-role-kind/actions/workflows/release.yml)


Ansible Role Kind
=========

**[KIND](https://kind.sigs.k8s.io/)*** installation from scratch.

Goal
--------------

- manage packages if needed
- manage users if needed
- manage systems if needed

Requirements
--------------
![ansible](https://img.shields.io/badge/ansible-2.12.3-green.svg)
![molecule](https://img.shields.io/badge/molecule-4.0.4-green.svg)
![vagrant](https://img.shields.io/badge/vagrant-2.0.0-green.svg)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml) for available variables.

If you whant to manage `packages`, `users` or `systems`, use one or more variable listed below:

    packages_managed: false
    users_managed: false
    systems_managed: false

> See [molecule/default/vars/kind.yml](molecule/default/vars/kind.yml) for example variables.

Example Playbook
----------------

See [molecule/default/converge.yml](molecule/default/converge.yml) for playbook and inventory example.

License
-------

[mit license]: https://img.shields.io/badge/License-MIT-blue.svg
[![mit license]](LICENSE)

Author Information
------------------

[email]: https://img.shields.io/badge/@-emmanuel@buisset.ch-orange.svg
[![email]](mailto:emmanue@buisset.ch)
