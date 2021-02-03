FROM redis:alpine3.12
LABEL MAINTAINER="Madhu Akula" INFO="Kubernetes Goat"

COPY data.redis /data.redis
COPY start-redis.sh /start-redis.sh

CMD [ "/bin/sh", "/start-redis.sh" ]
