# Loadbalancing with Nginx

## Node app

[Node app repository](https://github.com/subhrapaladhi/Docker-Node-App)

# Layer 7 Loadbalancing

## [nginx.conf](./Layer_7_Loadbalancing/nginx.conf)

## Instructions
1. create the docker image for the node app and start the required number of containers.
2. put nginx.conf file in ```/etc/ngnix```
3. assign the routes and ports appropriately.
4. run ```sudo nginx -s reload```


