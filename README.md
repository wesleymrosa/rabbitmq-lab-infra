# rabbitmq-lab-infra

Infraestrutura básica com Docker Compose contendo:

- 🐘 PostgreSQL 15 (porta: `5432`)
- 🐇 RabbitMQ 3 com painel de gerenciamento (portas: `5672`, `15672`)

## 🔧 Serviços

### PostgreSQL

- Banco: `pedido_db`
- Usuário: `postgres`
- Senha: `admin`

### RabbitMQ

- Host: `localhost`
- Porta: `5672` (AMQP)
- UI: [http://localhost:15672](http://localhost:15672)  
  Usuário: `guest`  
  Senha: `guest`

## 🚀 Subir a infraestrutura

```bash
docker-compose up -d
