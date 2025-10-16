server: srv01

server: srv02

server: srv03

server: srv04

**inicia swarm:**

docker swarm init

**comando e token para inserir vm no cluster:**

docker swarm join --token SWMTKN-1-2zyqy1exnhg45vbmxneo47vtwceadyez59he8d1w9w6r0eebmn-9y7xov8jwrtupwh9c2g7dkx1b 192.168.1.17:2377

**lista clusters:**

docker node ls

![image.png](attachment:b7d33f49-81d0-4bfb-a97e-d582ec977f52:image.png)

![image.png](attachment:38a0b52d-3937-4409-b14d-c7e7328fd535:image.png)
