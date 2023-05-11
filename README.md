# docker-ansible-runner
Ansible runner docker image

git clone https://github.com/ayen8/docker-ansible-runner ansible-runner

cd ansible-runner

make build-ansible

copy docker-compose.yml

docker compose up -d

setup ansible-runner/runneer/.ssh/ files, i.e. id_rsa id_rsa.pub from host
