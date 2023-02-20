# This role will deploy NGINX from source

- Specific version can define at deploy_nginx.yml file which was declared as variable (nginx_version)

- Managed hosts can be defined at inventory file which was already declared at ansible.cfg

- Need to define remote user with (-u) option, privilege esclation with (-K) option and password for that user with (-k) option
  
    Syntax:
    
      ansible-playbook deploy_nginx.yml -u <username> -k -K
