---
description: >-
  After getting a subscription, you should learn how to manage your connection
  slots, also known as configurations.
icon: graduation-cap
---

# Basics

## **What is a VPN Configuration?** <a href="#definition" id="definition"></a>

A VPN configuration is a set of details required to establish a connection between your device and our VPN server. This includes the protocol you choose (e.g., WireGuard or VMess/VLESS), the server location, and authentication keys.

## How to access my configuration list <a href="#access" id="access"></a>

Simply go to the "💻 VPN Configurations" menu in the Services section. You will be able to see a list of slots.

<div align="left">

<figure><picture><source srcset="../.gitbook/assets/image (18).png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/image (17).png" alt="" width="551"></picture><figcaption></figcaption></figure>

</div>

## **Components of a VPN Configuration** <a href="#components" id="components"></a>

<div align="left">

<figure><picture><source srcset="../.gitbook/assets/Screenshot From 2024-09-27 17-06-26.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Screenshot From 2024-09-27 17-06-21.png" alt="" width="553"></picture><figcaption><p>An example of configuration menu</p></figcaption></figure>

</div>

Each configuration in our service contains:

* **Protocol**: The method of connecting to the VPN (e.g., WireGuard, VMess, or VLESS).
* **Server**: The specific VPN server location that you will connect to. You can choose from different countries or cities to suit your needs (e.g., France, Paris #1).
* **Authentication Data**: Depending on the protocol, this could be a configuration file (for WireGuard) or a URL (for VMess/VLESS) that contains all necessary information to connect.

{% hint style="info" %}
⚠️ **Never share authentication data from your configuration file or URL!**&#x20;

This data is essential for your configuration slot to connect to our VPN service. Sharing it can allow unauthorized users to access your specific configuration, potentially leading to data misuse, security breaches, or violations of your privacy. Keeping this information confidential ensures your connection remains secure and protects your online activities.
{% endhint %}

## **How VPN Configurations Work**

* When you select a server and protocol, our system will generate a configuration file or URL for you.
* For **WireGuard**, this will be a `.conf` file, which you’ll import into the WireGuard app.
* For **VMess/VLESS**, it will be a connection URL to use with the Xray or V2Ray client.

{% hint style="info" %}
You can change the VPN server without regenerating the configuration. Simply choose a different server from the settings, and your connection will update accordingly.
{% endhint %}

## **Management Options** <a href="#manage" id="manage"></a>

* **Change Configuration Name**: You can rename your configuration at any time. This change is only for visual purposes and does not affect the functionality of the VPN connection. It’s useful to help you organize and identify different configurations.
* **Revoke Configuration**: If your configuration is compromised or you no longer trust it (e.g., it was leaked), you can revoke it. This will drop the old configuration and generate a new connection URL or file. This is useful for ensuring your connection remains secure.
