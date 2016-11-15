# Ansible Role: Drupal Console on CentOS 7

Installs, updates and initialize Drupal Console.

## Requirements

Tested CentOS 7

## Role Variables

Available variables are listed below, along with default values `defaults/main.yml`


Drupal Console .phar location. The default location `/usr/local/bin/drupal` is accesible on PATH.

    drupal_console_path: /usr/local/bin/drupal

Update Drupal Console.

    drupal_console_keep_updated: false

Initialize Drupal console for the users on the list.

    drupal_console_config:
      - name: "vagrant"
        path: "/home/vagrant/.console"

## Dependencies

php > 5.6

## License

MIT

## Author Information

Apostolos Tovletoglou [ansible-role-git](https://github.com/tovletoglou/ansible-role-drupalconsole)
