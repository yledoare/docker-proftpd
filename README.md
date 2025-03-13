# docker-proftpd

Simple way to install a proftp server on an host.

# Using

* Run certbot to build your certificates 

* In tester-ssl/docker-compose.yml:

uncomment lines

change yourdmain.com to your domain

change 1.2.3.4 to your IP

* Then run :

``
docker-compose up -d 
``
