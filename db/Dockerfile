FROM mariadb:10.3

RUN sed -E -i -e "s/^(\s*)(bind-address\s*=.*)$/\1# \2/" /etc/mysql/my.cnf
RUN sed -E -i -e "s/^(\s*)(skip-name-resolve)/\1# \2/" /etc/mysql/conf.d/docker.cnf