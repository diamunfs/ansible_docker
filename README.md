# ansible_docker
Auto deployment with ansible to deploy docker container that contain python and nginx, afterthat it will push image to dockerhub

# running playbook
ansible-playbook deploy_dockerhost.yml -i production/  -v --ask-sudo-pass
