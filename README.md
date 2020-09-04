# michaelsasser.teamspeak

Install a teamspeak 3 Server.

## Role Variables

| Varibale                       | Description                                                 |
|--------------------------------|-------------------------------------------------------------|
| teamspeak_serveradmin_password | The serveradmin password (optional)                         |


## Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - michaelsasser.teamspeak
  vars:
    - teamspeak_serveradmin_password: MyPassword
```

## License

Copyright &copy; 2020 Michael Sasser <Info@MichaelSasser.org>. Released under
the GPLv3 license.
