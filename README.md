# Cloudflare Tunnel -> Nginx Docker Compose

Example docker compose setup for exposing a self hosted application using cloudflare tunnels.

1. Create a tunnel within the cloudflare console.
2. Obtain the token from the "Install and run a connector section"
3. `cp .env.example .env` and enter your token.
4. Setup the public hostname to point to the url of your server on port 80.
5. `docker compose up -d`

Your hostname will now point to your nginx container!
