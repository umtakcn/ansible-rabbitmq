Rabbitmq Cluster Playbook

You can install Rabbitmq Cluster via this Ansible role.

Role will create three node(1 Master, 2 Slave) Rabbitmq Cluster.

Two thing you need to do before run this role. First you need to specify three server ip (1 Master, 2 Slave) in inventory file. Second, you need to place Erlang, Socat, Rabbitmq-server setup files in /opt/files on Ansible server and rename its names to "erlang" ,"socat" and "rabbitmq-server". 
