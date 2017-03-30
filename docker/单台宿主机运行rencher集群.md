###单台宿主机跑swarm/kubernet/rencher集群

###1.准备docker环境和docker-compose环境

```
curl -fsSL https://get.docker.com/ | sh 
systemctl start docker 
curl -L https://github.com/docker/compose/releases/download/1.11.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```
