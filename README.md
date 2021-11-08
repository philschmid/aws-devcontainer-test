# How to get Devcontainers running on remote service


1. start a ec2 instance 
2. update `~/.ssh/config`
3. make sure locker docker daemon is stopped
4. expose remote docker and start devcontainer 
```bash
DOCKER_HOST=ssh://ubuntu@infinity devcontainer open
``` 
5. run dev container
6. stop ec2


## Idea for tool 

provide git repo + aws profile 

```bash
aws-dev-container philschmid/my-repo --profile x1
```

