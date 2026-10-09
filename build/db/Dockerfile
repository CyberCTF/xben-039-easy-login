# The db service of upstream's docker-compose.yml (XBEN-039-24): mysql:5.7, pinned here to 5.7.44, with its
# environment values and command baked in.
FROM mysql:5.7.44
ENV MYSQL_ROOT_PASSWORD=rootpassword \
    MYSQL_DATABASE=blogDB \
    MYSQL_USER=user \
    MYSQL_PASSWORD=password
CMD ["mysqld", "--default-authentication-plugin=mysql_native_password"]
