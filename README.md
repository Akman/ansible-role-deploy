# Ansible Role: deploy

Deploy Web Application on Linux

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    # deploy_www_root: "/var/www/domain.com"

    Application root directory

    # deploy_tmp_root: "/var/tmp/domain.com"

    Application temp directory

    # deploy_current: "current"

    Symbolic link name to current release directory created in `deploy_www_root` directory

## Dependencies

## Example Playbook

    - hosts: all
      roles:
        - Akman.deploy

*Inside vars/main.yml*:

    deploy_www_root: "/var/www/domain.com"
    deploy_tmp_root: "/var/tmp/domain.com"
    deploy_current: "current"

## License

MIT / BSD

## Author Information

This role was created in 2018 by Alexander Kapitman
