---
description: >-
  Our service provides three VPN protocols: WireGuard, VLESS, and VMess. This
  article will guide you on selecting the right protocol for your VPN
  configuration based on your needs.
icon: shield-keyhole
---

# Select a protocol

## How to switch protocol  <a href="#switch" id="switch"></a>

To switch protocol, navigate to the configuration menu and select the "📡 Change Protocol" button.&#x20;

<div align="left">

<figure><picture><source srcset="../.gitbook/assets/Screenshot From 2024-09-28 16-10-59.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Screenshot From 2024-09-28 16-10-55.png" alt="" width="368"></picture><figcaption></figcaption></figure>

</div>

You'll then be prompted to choose a protocol.

<div align="left">

<figure><picture><source srcset="../.gitbook/assets/Screenshot From 2024-09-29 16-40-35.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Screenshot From 2024-09-29 16-40-30.png" alt="" width="563"></picture><figcaption></figcaption></figure>

</div>

After changing the protocol, reconnect using the new configuration specific to that protocol. If you want to revert to the previous protocol, simply reconnect to the old one without importing the old configuration again. This process ensures a smooth transition between protocols while keeping your settings intact.

<div align="left">

<figure><picture><source srcset="../.gitbook/assets/Screenshot From 2024-09-29 17-02-05.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Screenshot From 2024-09-29 17-02-00.png" alt="" width="563"></picture><figcaption></figcaption></figure>

</div>

## Which protocol to choose? <a href="#choose" id="choose"></a>

All protocols are equipped with features to tackle specific needs like speed, bypassing censorship, or secure communication, allowing users to select the best protocol based on their requirements.

### **WireGuard:** <a href="#wireguard" id="wireguard"></a>

* **Overview**: A modern, fast, and secure VPN protocol.
* **Features**:
  * **Speed**: High-speed performance with minimal overhead.
  * **Security**: Uses state-of-the-art cryptography.
  * **Simplicity**: Easy to configure and ideal for most users.
* **Best for**: Users seeking a balance of speed and security on open networks.

***

### **VLESS (TCP/gRPC):** <a href="#vless" id="vless"></a>

* **Overview**: A lightweight protocol optimized for bypassing restrictions.
* **Features**:
  * **TCP/gRPC Support**: Provides reliable, multiplexed communication with efficient traffic handling over HTTP/2.
  * **No Built-in Encryption**: External encryption like TLS is used, allowing flexibility.
  * **Lightweight**: Ideal for resource-constrained environments.
* **Best for**: Users needing better stability and performance in restricted or high-latency environments.

***

### **VMess (TCP/WebSocket):** <a href="#vmess" id="vmess"></a>

* **Overview**: A full-featured circumvention protocol designed to bypass censorship.
* **Features**:
  * **TCP/WebSocket Support**: Ideal for disguising VPN traffic as regular HTTPS traffic.
  * **Encryption**: Built-in encryption using advanced algorithms (AES, RSA).
  * **Obfuscation**: Effective for bypassing firewalls in restricted regions.
* **Best for**: Users in heavily censored environments needing flexible, secure communication.

***

### **Summary**: <a href="#summary" id="summary"></a>

* **WireGuard**: Best for speed and security on open networks.
* **VLESS (TCP/gRPC)**: Optimal for stability and censorship evasion in restricted environments.
* **VMess (TCP/WebSocket)**: Ideal for users needing secure, obfuscated traffic to bypass deep packet inspection.
