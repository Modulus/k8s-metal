# How
ansible-playbook rollout.yaml

cd /tmp/kubepsray

# Install via kubespray
ansible-playbook -i inventory/local/hosts.ini --become --become-user=root --ask-become-pass--user=modulus cluster.yml

