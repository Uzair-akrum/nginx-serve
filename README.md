# Node.js Server behind a reverse proxy (Nginx) in a contanarized environment
This repository contains three instances of a node js server and nginx being used as load balancer to divide load across servers in a dockerized environment
 
## Why use a reverse proxy 
- Web Server 🤖:It can act as a web server to load static content (Html,CSS)
- Reverse Proxy ⏩:It act as a server and hide our backend application from the internet adding 
  an extra layer of security , isolation and caching
- Load Balancer ⚖️:The reverse proxy can also act as  a load balancer divding load across multiple servers 
- SSL Encryption 🔐: encrypting and decrypting SSL communications is expensive, and would make web servers slow. The reverse proxy can be configured to decrypt incoming requests from the client and encrypt outgoing responses from the server

## My Learnings
- How a reverse proxy like nginx works and compares to other reverse proxies like apache
- When or when not to use a reverse proxy
- How Docker networking works
- How Dns Resolution works
- How SSl Encryption works
- How gzip compression works
- Layer 4 vs layer 7 proxy
