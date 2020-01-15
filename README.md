# Installing Wordpress with MySQL balansed by HAProxy deployed by Docker

![haproxy](http://www.haproxy.org/img/HAProxyCommunityEdition_60px.png) ![docker](https://d1.awsstatic.com/acs/characters/Logos/Docker-Logo_Horizontel_279x131.b8a5c41e56b77706656d61080f6a0217a3ba356d.png) ![wordpress](https://s3.us-east-2.amazonaws.com/upload-icon/uploads/icons/png/9970351441553750355-128.png)

This are config files for installing three containers with Wordpress on port 80 and installing MySQL container on port 3306 balansed by HAProxy

Command for running haproxy Docker in this case

```
docker run -d -p 80:80 -p 3306:3306 -v $(pwd)/haproxy.cfg:/usr/local/etc/haproxy/haproxy.cfg haproxy

```
![Задание](https://github.com/anatoliykv/Installing-HAProxy/blob/master/Image%20from%20iOS%20(1).jpg)
