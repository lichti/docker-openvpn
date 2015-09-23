# OpenVPN as Docker container
This container may be used to server and client.

#How to use
```bash
docker run --rm -it --privileged --net=host -v $PDW:/etc/openvpn lichti/openvpn openvpn --config myvpn.conf
```
