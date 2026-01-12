# Docker_uninstall-settings
Установка и настройка Docker для работы с Nginx(front) + Apache(back)

# Docker uninstall
comand: 

# Struct
docker-lamp/

├── docker-compose.yml

├── .env

├── nginx/

│   ├── Dockerfile

│   ├── nginx.conf

│   ├── sites-available/

│   │   ├── project1.conf

│   │   └── project2.conf

│   └── sites-enabled/
├── apache/
│   ├── Dockerfile
│   ├── conf.d/
│   └── sites-available/
├── php/
│   └── php.ini
├── postgres/
│   └── init/
├── projects/
│   ├── project1/
│   └── project2/
└── logs/                    # ПАПКА С ЛОГАМИ
    ├── nginx/               # Логи Nginx
    │   ├── access.log
    │   ├── error.log
    │   ├── project1_access.log
    │   ├── project1_error.log
    │   ├── project2_access.log
    │   └── project2_error.log
    ├── apache/              # Логи Apache
    │   ├── access.log
    │   ├── error.log
    │   ├── project1_access.log
    │   ├── project1_error.log
    │   ├── project2_access.log
    │   └── project2_error.log
    ├── php/                 # Логи PHP
    │   ├── project1_error.log
    │   └── project2_error.log
    ├── postgres/            # Логи PostgreSQL
    │   └── postgresql.log
    └── supervisor/          # Логи Supervisor (если используется)
