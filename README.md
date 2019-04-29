# GT VPN
Create a own VPN Server with the help of ALgo API and Digital ocean which is most user friendly cloud. 

## Features

* Supports only IKEv2 with strong crypto (AES-GCM, SHA2, and P-256) and [WireGuard](https://www.wireguard.com/)
* Generates Apple profiles to auto-configure iOS and macOS devices
* Includes a helper script to add and remove users
* Blocks ads with a local DNS resolver (optional)
* Sets up limited SSH users for tunneling traffic (optional)
* Based on current versions of Ubuntu and strongSwan
* Installs to DigitalOcean, Amazon Lightsail, Amazon EC2, Vultr, Microsoft Azure, Google Compute Engine, Scaleway, OpenStack, or your own Ubuntu 18.04 LTS server

## Not Supported

* Does not support legacy cipher suites or protocols like L2TP, IKEv1, or RSA
* Does not install Tor, OpenVPN, or other risky servers
* Does not depend on the security of [TLS](https://tools.ietf.org/html/rfc7457)
* Does not require client software on most platforms
* Does not claim to provide anonymity or censorship avoidance
* Does not claim to protect you from the [FSB](https://en.wikipedia.org/wiki/Federal_Security_Service)

