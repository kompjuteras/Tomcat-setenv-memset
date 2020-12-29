Tomcat-setenv-memset
=========
Ansible playbook for setup of HEAP size parameters in setenv.sh (to use 75% of total physical RAM).

Requirements
------------
Ansible server:
- Ansible 2.7+

Target machine(s):
- SSH connection with the sudo access.
- Path to your setenv.sh file (I skipped automatic finding because some machines have multiple Tomcat installations)

Example Playbook
----------------
`ansible-playbook -i hosts.inv Tomcat-setenv-memset.yml -u linux_username -k -K`

License
-------
No license, use it as you wish.

Author Information
------------------

Darko Drazovic \
LinkedIn: https://www.linkedin.com/in/darkodrazovic \
Personal: https://darkodrazovic.in.rs \
Blog: https://kompjuteras.com \
GitHub: https://github.com/kompjuteras