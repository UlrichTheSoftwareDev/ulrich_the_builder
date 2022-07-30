# ulrich_the_builder

##For Hbase only

#update vars file

```group_vars/all.yml```

#update template file

```roles/hbase_master/templates/```

```roles/hbase_slave/templates/```

#update inventory file

```inventory/inventory_production```

```
ansible-playbook -i inventory/inventory_production master.yml

ansible-playbook -i inventory/inventory_production nodes.yml

/opt/hbase/hbase-2.4.12/bin/start-hbase.sh 
```
