# homelab stacks 
> my personal home lab stacks and services. 🦉

## Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [running services](#running_services)
- [TODO](#todo)

## About <a name = "about"></a>
This is a collection of services I run on my home lab. I use a Raspberry Pi 3 B+ as my main server, and a VPS as a reverse tunnel server. I use the reverse tunnel to access my Raspberry Pi from anywhere in the world. I use a domain name to access my Raspberry Pi, and I use Cloudflare to manage DNS. I use Nginx as a reverse proxy, and I use Docker to manage my containers.

## Getting Started <a name = "getting_started"></a>
### prerequisites
- Raspberry Pi 3 B+
- VPS
- Domain name
- Cloudflare account


## Running Services <a name = "running_services"></a>
- [sshm](services/sshm/readme.md)
- [encrypted-dns](docker/pi-hole/readme.md)
- [pi-hole](docker/pi-hole/readme.md)

this is what my home lab looks like:<br>
<img src="assets/homelab.jpg" width="300" height="300">

## TODO <a name = "todo"></a>
- [ ] add more services
- [ ] add more documentation

