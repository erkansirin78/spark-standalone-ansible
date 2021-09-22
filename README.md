# spark-standalone-ansible

## Run
` ansible-playbook -i /etc/ansible/hosts install_airflow.yaml `  


## Shutdown
`ansible spark_all -i /etc/ansible/hosts -m shell -a "shutdown now"`  


