# How to get Devcontainers running on remote service


1. start a ec2 instance 
2. update `~/.ssh/config`
3. make sure locker docker daemon is stopped
4. expose remote docker deamon `export DOCKER_HOST=ssh://ubuntu@infinity`
5. start devcontainer 
