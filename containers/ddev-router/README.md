## Information

This project is based on the [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy) project and contains overrides to the nginx config template specific to [DDEV](https://github.com/drud/ddev). If you are looking for a generalized Docker router solution, we recommend you look there.

Previously this project was also named `drud/nginx-proxy`, but has been renamed to `drud/docker.ddev-router`.

## Usage

This container is used to allow all [DDEV](https://github.com/drud/ddev) sites to exist side by side on a shared port (typically 80). It serves as a proxy to those sites, and forwards traffic to the appropriate site depending on the hostname.
