## Probar la conexion
ansible all -i inventory/hosts.ini -m ping

## Ejecutar
ansible-playbook -i inventory/hosts.ini playbooks/main.yml