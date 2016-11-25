# Nginx Compiled with ``ngx_cache_purge`` Module

This image is based on the official ``nginx:mainline`` ([see on Dockehub]
(https://hub.docker.com/_/nginx/)) and recompiled with the same configure options from vanilla nginx
sources with addition of ``--add-module=ngx-cache-purge``.

[The fork](https://github.com/nginx-modules/ngx_cache_purge) of the [original FRiCLE's module]
(http://labs.frickle.com/nginx_ngx_cache_purge/) is used, which...

* is compatible with modern nginx
* supports purging by partial keys (``*`` at the end) (see [release notes](https://github.com/nginx-modules/ngx_cache_purge/releases))
