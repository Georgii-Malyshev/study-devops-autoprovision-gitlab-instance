# study-devops-autoprovision-gitlab-instance
Private project to study DevOps tools and methodolog

This playbook sets up a GitLab instance on a specified Ubuntu Server host.

For this playbook to work on your ansible control node you'll need: 
  ansible-core
  ansible-galaxy roles:
    - geerlingguy.swap (https://galaxy.ansible.com/geerlingguy/swap) - install with 'ansible-galaxy install geerlingguy.swap')
