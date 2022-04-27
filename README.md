The Caddy Website
=================

This is a fork of the source of the Caddy website, [caddyserver.com](https://caddyserver.com).


## Requirements

- Caddy 2 (installed in your PATH as `caddy`)


## Quick start

1. `git clone git@github.com:thinkingerrol/caddyserver-website.git`
2. `cd website`
3. `docker volume create --name=caddy_data`
4. `docker-compose up`

You can then load [https://localhost](https://localhost) (or whatever address you configured) in your browser.


