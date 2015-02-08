NGINX with TCP proxy support
============================

- [Nginx](http://nginx.org/)
- [nginx_tcp_proxy_module](https://github.com/yaoweibin/nginx_tcp_proxy_module)

[![](http://dockeri.co/image/zack/nginx-tcp-proxy)](https://registry.hub.docker.com/u/zack/nginx-tcp-proxy/)

Quick Start
-----------

    $ docker run --name nginx-tcp-proxy -d --rm -p 80:80 -p 8000:8000 \
        -v `pwd`/nginx.conf:/usr/local/nginx/conf/nginx.conf \
        zack/nginx-tcp-proxy

License
-------
[MIT](http://yulun.mit-license.org/)
