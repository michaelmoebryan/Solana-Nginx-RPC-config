# SOL RPC Node Nginx Reverse Proxy Config
This is an example config for a solana RPC node reverse proxy

This allows you to use nginx as a reverse proxy to proxy both http and websocket requests through the same port and IP.

Also shows how to include http -> https TLS redirect as certbot wont touch the custom config
