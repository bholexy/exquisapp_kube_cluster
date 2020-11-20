
Edit the host file for master node and worker node
Run the following command
	ansible-playbook setup_master_node.yml;
	ansible-playbook setup_worker_nodes.yml;
	ansible-playbook main.yml