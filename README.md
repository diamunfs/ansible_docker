# ansible_docker
Automation deployment with ansible to deploy docker container that contain python and nginx, aftethat it will automate push image to dockerhub

# running playbook
ansible-playbook deploy_dockerhost.yml -i production/  -v --ask-sudo-pass
