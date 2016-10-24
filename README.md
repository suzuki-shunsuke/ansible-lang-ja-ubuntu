lang-ja-ubuntu
===============

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-lang-ja-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-lang-ja-ubuntu)

Install lang-ja dependencies on Ubuntu.

Notice
-------

*  In this role there is a task using "command" module in order to update locale, so the result of this task is "changed" even if no change has occured.

Requirements
------------

Nothing.

Role Variables
--------------

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.lang-ja-ubuntu
```

License
-------

MIT
