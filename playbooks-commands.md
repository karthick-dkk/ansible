ansible-playbook tags.yml --tags yum    # Run only yum task in playbook
ansible-playbook tags.yml --list-tags   # list all tags in playbook
ansible-playbook tags.yml --skip-tags ntp  # Skip the specific task in playbook
ansible-playbook tags.yml -v           # Increarse verbosity level vy adding -v , -vvv
