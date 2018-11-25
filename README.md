# Provide a docker container of a fully functional Zabbix monitoring system. This is to include the Zabbix Server, Database and Web Console components in a single container.

This repository has docker file that contains Zabbix Server, database and web server in single container.

# How to use this image

Start a Zabbix server container as follows:

Create docker image
```console
    docker build  zabbix-single-container -tag final_zabbix
    docker run --name some-zabbix-applianceq -p 80:80 -p 10051:10051 <image_id>
```
# Provide an Ansible playbook that creates a host in your Zabbix system called testhost.nsw.education. 

Ansible script ansible_create_host.yml create host in zabbix system

```console
$ ansible-playbook ansible_create_host.yml
```
# Provide an Ansible playbook that creates a host in your Zabbix system called testhost.nsw.education.

Ansible script ansible_create_host.yml create host in zabbix system

```console
$ ansible-playbook ansible_create_host.yml
```
# Provide an Ansible playbook that export the “Template App Zabbix Agent” to a file called export_zabbix_agent.template

Ansible script ansible_dump_template export template to file called export_zabbix_agent.template

```console
$ ansible-playbook ansible_dump_template.yml
```

# Explain why you chose either Ansible or Python to complete Step 3. Store this sentence in a file called answer.txt in the root director

Answer.txt
