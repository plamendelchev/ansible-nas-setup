
- Run playbook
```shell
ansible-galaxy install -r requirements.yml
ansible-playbook main.yaml --ask-become-pass
```

- To implement
https://wiki.archlinux.org/title/Port_knocking#With_a_daemon_helper
https://wiki.archlinux.org/title/simple_stateful_firewall#Protection_against_spoofing_attacks
