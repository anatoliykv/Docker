# Installing Wordpress with MySQL balansed by HAProxy deployed by Docker

![haproxy](http://www.haproxy.org/img/HAProxyCommunityEdition_60px.png)

This are config files for installing three containers with Wordpress on port 80 and installing MySQL container on port 3306 balansed by HAProxy

Command for running haproxy Docker in this case

```
docker run -d -p 80:80 -p 3306:3306 -v $(pwd)/haproxy.cfg:/usr/local/etc/haproxy/haproxy.cfg haproxy

```
![Задание](https://github.com/anatoliykv/Installing-HAProxy/blob/master/Image%20from%20iOS%20(1).jpg)
