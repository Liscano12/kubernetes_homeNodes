# argo-pi
My personal Argo repo for cluster


How to init this reposetory:


Prepare main and worker nodes:
add a ansible user
give him root
create a ssh key for the ansible user

install ansible and helm on you local maschin
register your ssh public key on the main node
download the repo
add the node ips to ansible/inventory
run: ansible-playbook -i inventory main.yml
