# Tags

ansible-playbook tags.yml --tags yum    # Run only yum task in playbook

ansible-playbook tags.yml --list-tags   # list all tags in playbook

ansible-playbook tags.yml --skip-tags ntp  # Skip the specific task in playbook

# Log level

ansible-playbook tags.yml -v           # Increarse verbosity level vy adding -v , -vvv

# Task

ansible-playbook tags.yml --start-at-task 'Task Name" # Start the playbook at specific tasks and onwards

ansible-playbook tags.ym --step        # Ask confirmation for each tasks

# Variable

ansible-playbook tags.yml  -e vairable_name=value   # specify the variable value in Run time 
