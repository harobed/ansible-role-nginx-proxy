# jwilder/nginx-proxy Ansible Role

This Ansible Role install [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy).

Installation is based on [docker-compose.yml](templates/docker-compose.yml) file.

See [Ansible Role Sentry Example](https://github.com/harobed/ansible-role-sentry-example) to understand how to use this role.

Use  `--extra-vars "nginx_proxy_uninstall=true"` to uninstall Nginx-Proxy.
