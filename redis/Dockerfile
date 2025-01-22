FROM redis:6.2-alpine

COPY redis.conf /usr/local/etc/redis/redis.conf
COPY sentinel.conf /usr/local/etc/redis/sentinel.conf

CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]
