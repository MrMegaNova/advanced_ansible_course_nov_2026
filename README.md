## Advanced Ansible course
advencced_ansible_course_nov_2026


# Installation avec uv

### Nouveau projet
```(sh)
uv init
uv add ansible ansible-core ansible-lint
un run ansible --version
```

### Projet existant
```(sh)
uv sync
un run ansible --version
```

# Usefull Links

- [Doc ansible](https://docs.ansible.com/)

- [UV](https://docs.astral.sh/uv/getting-started/installation/)

- [Ansible Realease & maintenance](https://docs.ansible.com/projects/ansible/latest/reference_appendices/release_and_maintenance.html)

- [Ansible facts & magics vars](https://docs.ansible.com/projects/ansible/latest/playbook_guide/playbooks_vars_facts.html)

- [Doc jinja2](https://jinja.palletsprojects.com/en/stable/nativetypes/#examples)

- [Templating ansible](https://docs.ansible.com/projects/ansible/latest/playbook_guide/playbooks_templating.html)

- [Templating Jinja ansible (outdated)](https://docs.ansible.com/projects/ansible/2.9/user_guide/playbooks_templating.html)

- [Use ansible filters](https://docs.ansible.com/projects/ansible/latest/playbook_guide/playbooks_filters.html)

- [Ansible filters list](https://docs.ansible.com/projects/ansible/2.9/user_guide/playbooks_filters.html)

- [Ansible role](https://docs.ansible.com/projects/ansible/latest/playbook_guide/playbooks_reuse_roles.html)

- [Import tasks](https://docs.ansible.com/projects/ansible/latest/collections/ansible/builtin/import_tasks_module.html)

- [Include tasks](https://docs.ansible.com/projects/ansible/latest/collections/ansible/builtin/include_tasks_module.html)

- [Import playbook](https://docs.ansible.com/projects/ansible/latest/collections/ansible/builtin/import_playbook_module.html)

#### Modules: 

- [Module lineinfile](https://docs.ansible.com/projects/ansible/latest/collections/ansible/builtin/lineinfile_module.html)

- [Module apt](https://docs.ansible.com/projects/ansible/latest/collections/ansible/builtin/apt_module.html)

- [Package facts](https://docs.ansible.com/projects/ansible/3/collections/ansible/builtin/package_facts_module.html)% 