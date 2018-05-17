FROM daocloud.io/library/mysql:8

MAINTAINER xiyou <xiyou9981@gmail.com>

ADD mysqld.cnf /etc/mysql/mysql.conf.d/mysqld.cnf
ADD my.cnf /etc/mysql/conf.d/mysql.cnf

CMD ["mysqld"]

EXPOSE 3306
