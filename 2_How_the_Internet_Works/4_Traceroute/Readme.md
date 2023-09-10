# 🌐 Traceroute

---

## 🌐 Overview

Have you ever wondered how the internet works behind the scenes when you type "google.com" in your browser's address bar? When you perform a traceroute, it unveils a fascinating journey filled with IP addresses and hops. In this section, we'll take you on a virtual adventure through traceroute, exploring the IPs and hops, and show you how to access Google's website directly via its IP 🌍💻🕵️‍♂️

---

## 🚀 Traceroute: Introduction 

Traceroute is like a digital treasure map. 🗺️ When you execute it, it reveals a list of IP addresses, each representing a hop along the route from your device to the destination. These hops are like stepping stones that your data packets jump across to reach Google's servers.

🔍 Traceroute to google.com:

```shell
traceroute google.com
```
The output looks like below:
```
1  192.168.1.1 (Your Router)
2  10.0.0.1 (ISP's Gateway)
3  74.125.136.46 (Google's Server)
4  172.217.165.14 (Another Google Server)...
```

---

## 🌐 Browsing by IP: The Hidden Shortcut

Now, let's take a shortcut. Instead of using "google.com" in your browser, you can access Google directly by entering its IP address. Every website, like Google, has an IP address, and it's like the website's digital home address.

🌐 Google's IP address (as an example): `172.217.165.14`

Open your browser and enter this IP address in the address bar, and  You'll see Google's website appear. 

---

## 💬 Why So Many IPs and Hops?

You might wonder why there are so many IPs and hops when all you wanted was to visit Google. 🤔 Well, the internet is a vast network with many layers. Your request travels through various devices and networks before reaching its destination. Each hop represents a point where data is forwarded along this journey.

It's like sending a postcard to a friend in another city. It passes through local mailboxes, sorting centers, and post offices, each with its address.

---
