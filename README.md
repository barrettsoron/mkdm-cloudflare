# mkdm-cloudflare
MkDocs-Material – Using Docker with Cloudflare Tunnels

### Using Docker
1. Clone or fork this repo.
2. Create a new directory called 'docs' in the repo directory using `mkdir docs`.
3. Run `docker compose up -d` to start the docker container in detached mode.
4. Use `docker ps` to see whether the container has started yet. Run `docker console log` to see error logs.  
5. Visit (IP Address):8050 or whatever the full address is. Check that the ports are set up correctly.

### Using Cloudflare Tunnels
Configure a public hostname in Cloudflare Tunnels paired to a Cloudflare-managed domain address. Cloudflare will auto-config the DNS, but remember to map the ports properly. 
