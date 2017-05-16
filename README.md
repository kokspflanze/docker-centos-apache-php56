# docker-centos-apache-php7
Docker with CentOS 7, systemd, Apache2, PHP5.6, crond, composer and pagespeed

# Pull

```
docker pull kokspflanze/centos-apache-php56
```

# Running Container

```
docker run -v /sys/fs/cgroup:/sys/fs/cgroup:ro -v /opt/docker/docker_test/data:/var/www/page  --restart=always -d -it kokspflanze/centos-apache-php56 
```