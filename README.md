<h2>Securing Wireless Networks</h2>

<b>Wireless networking has become present everywhere and is synonymous with being online. Most places with an internet connection have a wireless modem or router serving a multitude of devices, from desktops to phones and internet of things (IoT) devices such as TVs, light bulbs, and refrigerators. Without the use of wireless technology, life today would be less convenient. However, with the increase of wireless technology, we've been forced to give up some of our online security. </b>

<b>As wireless technologies evolve, the effective distance of our wireless network improves, so much that we're seeing larger networks that overflow from what used to be local area networks (LANs) inside our premises, all the way to our neighbors. This is amazing when it comes to connectivity, however for security, this is disastrous.  </b>

---
<b>In this project I will reduce my attack surface by disabling IPv6 and limiting the number of devices allowed on a wireless network. This project also dives into MAC address filtering, which allows only known devices onto the internal network; disabling features when they're not in use; using secure authentication methods; and grouping devices or users based on their necessary privilage level within the network.</b>

---

<h2>Disabling IPv6</h2>

<b>IPv6, the newer version of the Internet Protocol, was designed to combat the fact that we'll eventually run out of IPv4 space. However, if we don't use IPv6 in our network but leave it enabled, we're allowing bad actors one more potential intrusion vector. As a general rule, we should disable or uninstall all protocols and applications that are not in active use to prevent attackers from using those tools against us.</b>
<b>Disabling unused protocols reduces the attack surface of our environment, which should be as small as possible. </b>

<h3>Windows</h3>

* <b>Open Network and Internet Settings.</b>
* <b>Click Change adapter options.</b>
* <b>For each adapter in the resulting window, double-click the adapter and then click Properties.</b>
* <b>Find the Internet Protocol Version 6 (TCP/IPv6) checkbox and uncheck it.</b>
* <b>Click OK and close the remaining windows.<b>

<h3>macOS</h3>

* <b>Open System Preferences.</b>
* <b>Click Network.</b>
* <b>For each adapter in the list, click Advanced.</b>
* <b>Open the (TCP/IP) tab.</b>
* <b>Ensure Configure IPv6 is set to Off.<b>

<h3>Linux</h3>

* <b>Open Settings.</b>
* <b>Click Network from the list on the left.</b>
* <b>For each adapter, click the configuration Cog.</b>
* <b>In the IPv6 tab, click the Disable radio button and then click Apply.</b>

