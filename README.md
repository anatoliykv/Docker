# Installing-HAProxy
![haproxy](http://www.haproxy.org/img/HAProxyCommunityEdition_60px.png)
HAProxy_plus_Wordpress_plus_MySQL
this are config files for installing 3 containers with Wordpress on port 80 and installing MySQL container on port 3306

comand for running haproxy Docker in this case

```
docker run -d -p 80:80 -p 3306:3306 -v $(pwd)/haproxy.cfg:/usr/local/etc/haproxy/haproxy.cfg haproxy

```
![Задание](https://github.com/anatoliykv/Installing-HAProxy/blob/master/Image%20from%20iOS%20(1).jpg)
