Находясь в каталоге с docker-compose.yml:
docker compose up -d
# docker-compose up -d

Все три контейнера будут:
использовать одну сеть DeminMS-my-netology-hw,
запускаться в нужном порядке через depends_on,
автоматически перезапускаться (restart: unless-stopped).
