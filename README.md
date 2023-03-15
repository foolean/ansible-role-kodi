# ansible-role-kodi

    Ansible role to manage kodi


## Requirements

    None


## Dependencies

    None


## Role Variables

    * kodi_user

    The user as which Kodi will run

    (default: kodi)


## Example Playbook

    ```yaml
    ---
    - hosts: all

      roles:
          - foolean/kodi
    ```


## Supported Operating Systems

    * Debian (11)
    * Raspbian (11)


## License

    BSD-3-Clause
