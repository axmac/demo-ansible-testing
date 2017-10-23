# About

Simple playbook demonstrating testing an Ansible task using a Docker container.

# Setup

    $ docker pull chrismeyers/centos7
    $ pip install docker-py
    $ ansible-galaxy install -r galaxy.yaml

# Run

    $ ansible-playbook provision_docker_test.yaml
