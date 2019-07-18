# lin_base

Common ansible handlers and defaults for other roles.


## Requirements

None


## Variables

Available variables are listed below, along with default values.


    hide_secrets: yes
TBD

    allow_sysctl: yes
TBD

    lin_ssh_port: 22
TBD

    lin_ssh_keys_files: <playbook_dir>/files/keys/ssh-*.key'
TBD

---

    systemd_dir: /etc/systemd/system
TBD

    local_bin: /usr/local/bin
TBD


## Handlers

- update system temp files
- restart ssh service
- remove temporary play files


## Tags

None


## Example Playbook

This role is only intended as a basis for inheritance.


## License

MIT


## Author Information

Created in 2018 by [IvanSible](https://github.com/ivansible)
