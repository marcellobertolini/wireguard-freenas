# wireguard-freenas

## Server setup
- Insert the entries of [rc.conf](https://github.com/marcellobertolini/wireguard-freenas/blob/master/rc.conf) by creating some custom Tunables

- Launch [postinit](https://github.com/marcellobertolini/wireguard-freenas/blob/master/postinit) by creating a post-init scripts  (Task -> Init/Shutdown Script -> Add)

Create these files
1. [pf.conf](https://github.com/marcellobertolini/wireguard-freenas/blob/master/pf.conf) --> /root/pf.conf
2. [wg0.conf](https://github.com/marcellobertolini/wireguard-freenas/blob/master/wg0.conf) --> /root/wg0.conf

Restart the Freenas server

## Client
Use [client.conf](https://github.com/marcellobertolini/wireguard-freenas/blob/master/client.conf) as the wireguard configuration file


## References
- Enabling wireguard on Freenas [Freenas](https://www.ixsystems.com/blog/wireguard-on-freenas-11-3/)
- Pf configuration files [apearson](https://gist.github.com/apearson/168b244b4735cceff9809ef3d07f4df5)
