FROM mysql:8.0
MAINTAINER docker-db

RUN useradd -m new_user && \
echo "new_user:password" | chpasswd

COPY ./my.cnf /etc/mysql/conf.d/my.cnf