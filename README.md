# Ansible

Docker image with [ansible-core](https://docs.ansible.com/ansible-core/devel/index.html) installed. It can be used as base image for containers providing Ansible automations.

Docker Hub: [fabos4ai/ansible-core](https://hub.docker.com/repository/docker/fabos4ai/ansible-core)

An example can be found in the `example` directory:

```
docker build -t ansible-example .
docker run ansible-example
```
