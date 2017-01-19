# La idea de este repo es aprovisionar una máquina virtual, en contreto Ubuntu Server, por medio de Ansible.

    La estructura de directorios básica de Ansible será:

    .
    ├── hosts <- inventory - archivo donde se definen hosts, o grupos de hosts y sus variables
    ├── playbook.yml <-playbook - Este archivo es el encargado de definir todas las tareas
    └── roles <- Los roles son grupos de ficheros y tareas
        └── vm <- rol vm
            ├── files
            │   └── index.php
            └── tasks <- Dentro de este directorio se debe crear archivos y  tareas que se deben ejecutar
                └── main.yml <- fichero de tareas - Los módulos son las librerías que utiliza para controlar servicios, ficheros, paquetes o comandos

