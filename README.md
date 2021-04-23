# ProtonVPN-Configs

I've pre-compiled all ProtonVPN P2P servers into configuration files. As I prefer Canada and New York servers, they are the only ones here for now. This list currently has both PAID and UNPAID servers. If you do not have a paid account you will not be able to connect and it may cause you connection issues.

I've selected all the un-loaded servers at the time I was compiling the mega-config. These loads may have changed. I also selected all P2P servers, as I myself would like to use P2P at some point with the VPN.

One thing I've noticed is in OpenWRT specifically when using the mega-config it refuses to start the TUN interface until I cut out half or more of the "remote" lines. I also notice the TCP connections don't work for some reason.

Should you experience issues connecting, please check:

- You have a paid account with ProtonVPN
- Remove half or more of the servers from the configuration
- Try UDP as I never got a successful connection over TCP for some reason

The single servers are listed for reference, they are the same ones you can get from ProtonVPN download page. You probably want to grab their configs from them to verify the VPN servers are indeed ProtonVPN.

Quick link to Mega Config for NewYork: https://github.com/BlockChasers/ProtonVPN-Configs/blob/main/P2P/New-York_United-States/UDP/NEW-YORK-USA-P2P-UDP.ovpn
