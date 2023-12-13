# Utilizar la imagen oficial de MySQL
FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD='PassWord'

ENV MYSQL_DATABASE='mantenimiento_des'

# Copiar el archivo de la base de datos exportada al contenedor
# COPY  ./mantenimiento_des_bd.sql /docker-entrypoint-initdb.d/

# Iniciar el contenedor de MySQL
CMD ["mysqld"]