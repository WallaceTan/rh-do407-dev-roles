```
$ ansible-playbook --syntax-check use-vhost-role.yml
$ ansible-playbook use-vhost-role.yml
$ ansible all -a 'yum list installed httpd'
$ ansible webservers -a 'systemctl is-active httpd'
$ ansible webservers -a 'systemctl is-enabled httpd'
$ ansible webservers -a 'cat /etc/httpd/conf.d/vhosts.conf'
```
Page 249 lab: ansible-galaxy
```
$ ansible-galaxy install -p roles -r install-role.yml
$ ansible-galaxy init --offline -p roles empty.example
```
