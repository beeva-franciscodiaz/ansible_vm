# La idea de este repo es aprovisionar una máquina virtual, en contreto Ubuntu Server, por medio de Ansible.

    La estructura de directorios básica de Ansible será:

    .
    ├── hosts <- inventory
    ├── playbook.yml <-playbook
    └── roles
        └── vm <- rol vm
            ├── files
            │   └── index.php
            └── tasks
                └── main.yml <- fichero de tareas
