Ansible Playbooks to build a 3 node Kubernetes Cluster.

Replace IP's in Hosts Files

una vez hecho el pull/clone entrar a .ssh y cambiar los permisos de id_rsa.pem con el siguiente comando: 

chmod 600 id_rsa.pem

hacer un ping y poner que se confia en todos los nodos 
ansible -i hosts -m ping cluster_hosts

