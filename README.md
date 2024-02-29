# Polls API

Um app de enquetes com comunicação em tempo real via websockets.

- criação de enquete (POST /polls)
- Receber dados de uma enquete (GET /polls/:id)
- Votar em uma enquete (POST /polls/:id/votes)

- Monitorar os resultados de uma enquete via websocket (ws results)

- Fastify
- Postgress (Relacional)
- Redis (vai armazenar a contagem de votos de cada opição pra cada enquete)
- Docker (Containers)
- Prisma ORM
- Zod (Validação de dados)
