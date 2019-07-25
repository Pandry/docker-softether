# docker-softether

Quick run:  
```
docker run -d --cap-add NET_ADMIN --name softether-vpn-server -p 443:443/tcp -p 992:992/tcp -p 1194:1194/udp -p 1701/udp -p 500/udp -p 4500/udp -p 5555:5555/tcp -v $(pwd)/softether/config:/etc/softether:Z -v $(pwd)/softether/logs:/var/log/softether:Z pandry/softether
```

