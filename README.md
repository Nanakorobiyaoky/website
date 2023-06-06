для запуска сервера необходимо, находясь в директории /api-gateway, выполнить следующие команды:
- npm run build
- docker pull rabbitmq:3.11.13-management
- docker pull node:18.14.0
- docker pull postgres:15.2
- docker-compose build
- docker-compose up

для запуска клиента необходимо, находясь в директории /Film-Portal, выполнить следующие команды:
- npm install
- npm run dev
