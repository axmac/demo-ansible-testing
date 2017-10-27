![TravisCI build status](https://travis-ci.org/axmac/demo-ansible-testing.svg?branch=master)

# About

Simple playbook demonstrating testing an Ansible task using a Docker container.

# Setup

    $ pip install docker-py
    $ ansible-galaxy install -r requirements.yml

# Run

    $ ansible-playbook provision_docker_test.yml
