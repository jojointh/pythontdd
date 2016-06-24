Prerequisite for client machine

- python (version 2.x required in order to run ansible and fabric)
- ansible
- fabric (pip install fabric)



Example for deploy code to staging server

    ./depoly_tools/fab deploy:host=surasak@staging.camerait.com



Provisioning staging server

    ./deploy_tools/ansible-playbook -i ansible.inventory provision.ansible.yaml --limit=staging
