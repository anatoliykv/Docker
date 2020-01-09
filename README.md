# Installing-HAProxy
HAProxy_plus_Wordpress_plus_MySQL
this are config files for installing 3 containers with Wordpress on port 80 and installing MySQL container on pore 3306

comand for running haproxy Docker in this case
docker run -p 80:80 -p 3306:3306 -v $(pwd)/haproxy.cfg:/usr/local/etc/haproxy/haproxy.cfg haproxy
