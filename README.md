# docker-traefik-config
example traefik docker configuration (used with cloudflare)

## prerequisites  

VM with `docker` and `docker-compose` installed  
a DNS entry for the domain you want to use (I use proxy.`<domain>` hosted at Cloudflare)  

## configure   
fill in your details in the `sample.env` file   
rename `sample.env` to `.env`

## run with docker (normal mode)
`docker-compose up -d`

**OR**

## run with docker (swarm mode)
`docker stack deploy -c docker-compose.swarm.yml traefik`


## see official docs

https://docs.traefik.io/
