# elk-tips

## ELK Docker
* One docker: https://elk-docker.readthedocs.io/ https://github.com/spujadas/elk-docker
* Three dockers: https://github.com/deviantony/docker-elk

## Forward port to access 
* `sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 8080 -j REDIRECT --to-port 5601`

