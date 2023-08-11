# mysqlはパフォーマンススキーマ=ONだから重いので、mariadbにした
# mariadbはデフォルトでパフォーマンススキーマ=off
# FROM mysql/mysql-server:8.0
FROM mariadb:11.0.2

ENV TZ UTC

COPY ./docker/db/my.conf /etc/my.conf
