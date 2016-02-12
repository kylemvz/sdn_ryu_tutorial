# Dockerized SDN Tutorial w/ Ryu Controller

- - -

## Set Up

This tutorial was written using: 
- Docker version 1.10.0, build 590d5108
- docker-compose version 1.6.0, build d99cad6

I think that most Docker/docker-compose should work -- just ensure that your Docker/docker-compose version supports
setting networks for containers.

Clone this repository and cd inside using:
```
git clone https://github.com/kylemvz/sdn_ryu_tutorial.git
cd sdn_ryu_tutorial
```

Start up the mininet and ryu containers using:
```
docker-compose up -d
```

This starts the containers in the background. You will want to connect to the containers using 
```
docker attach sdnryututorial_ryu
```
```
docker attach sdnryututorial_mininet
```

Use Ctrl+p + Ctrl+q in order to detach from the containers.

- - -