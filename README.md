# docker-squid

Minimal Docker image for **Squid** based on **Alpine Linux**.

To run it : `docker run --name squid -d --restart=always -p 3128:3128 -v /var/log/squid:/var/log/squid -v /etc/squid/squid.conf:/etc/squid/squid.conf -v /etc/squid/cache:/var/cache/squid fallais/docker-squid`