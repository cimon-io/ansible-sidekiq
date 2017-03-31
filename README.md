# Ansible role for sidekiq

This sets up sidekiq systemctl service on recent ubuntu.

## Example playbook

Example usage:

    - { role: thermistor.sidekiq, sidekiq_user: beep, sidekiq_dir: /srv/www/beep.eco/beep, tags: ['sidekiq'] }


## License

MIT

