# Ansible Role: symfony_deploy

Deploy Web Application on Linux

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    # deploy_www_root: "/var/www/domain.com"

    Application root directory

    # deploy_tmp_root: "/var/tmp/domain.com"

    Application temp directory

    # deploy_doc_root: "/var/www/domain.com/current"

    Symbolic link name to current release directory

## Dependencies

## Example Playbook

    - hosts: all
      roles:
        - Akman.symfony_deploy

*Inside vars/main.yml*:

    deploy_www_root: "/var/www/domain.com"
    deploy_tmp_root: "/var/tmp/domain.com"
    deploy_doc_root: "/var/www/domain.com/current"

## License

MIT / BSD

## Author Information

This role was created in 2018 by Alexander Kapitman
