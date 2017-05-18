# docker-proxy
a proxy listening on port (default 2375) which forwards all requests to Unix socks (default /var/run/docker.sock directly)

## usage
go run proxy.go -l 2375 -d /var/run/docker.sock -D

