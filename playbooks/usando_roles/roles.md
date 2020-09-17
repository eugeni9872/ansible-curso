    ├── README.md             - Explicación del funcionamiento del ROL
    ├── defaults              - Variables QUE SUMINISTRA EL USUARIO. Damos valores por defecto.
    │   └── main.yml
    ├── files                 - Otros ficheros que nuestro ROL, pero no requieren de personalización
    ├── handlers              - Handlers que puedan ser disparados por las tareas del ROL
    │   └── main.yml
    ├── meta                  - Información descriptiva del ROL (Información que se publica en GALAXY)
    │   └── main.yml
    ├── tasks                 - Tareas
    │   └── main.yml          ------ NO ES UN PLAYBOOK... solo un listado de tareas
    ├── templates             - Templates procesables con JINJA
    ├── tests                 - Pruebas unitarias del ROL
    │   ├── inventory
    │   └── test.yml          ------ PLAYBOOK
    └── vars                  - Variables INTERNAS del ROL
        └── main.yml
