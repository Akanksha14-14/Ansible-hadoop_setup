### Ansible-hadoop_setup
# Task 11.1
## Description:
11.1 Configure Hadoop and start cluster services using Ansible Playbook

## for TAsk 
**created playbook for this:**

* hadoop.YML : PLAYBOOK to create hadoop setup witout client
* hdfs-core.xml : Configuration file
* core-data.xml : Configuration file for datanode
* core-name.xml : Configuration file for namenode

hadoop-1.2.1-1.x86_64.rpm : Hadoop setup file
Imp: First make group in inventory with tag as namenode and datanode. Then play this playbook.

Inventory:

[namenode] ip ... ... ....

[datanode] ip1 ... ... ... ip2 ... ... ... ip3 ... ... ..

...

Command : ansible-playbook hadoop_infrastructure_without_client.yml

#NOTE: System should have pip and ansible before running this playbook.

Thank You

CREATER: Kaushal Soni
