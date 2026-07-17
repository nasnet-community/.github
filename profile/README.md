<h1 align="center">🛰️ NasNet Community</h1>

<p align="center"><b>Free internet, for everyone, everywhere — no matter who's trying to switch it off.</b></p>

<p align="center">
  <a href="https://x.com/joinNASNET"><img src="https://img.shields.io/badge/X-@joinNASNET-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="https://www.instagram.com/joinnasnet/"><img src="https://img.shields.io/badge/Instagram-joinnasnet-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://www.youtube.com/@JoinNASNET"><img src="https://img.shields.io/badge/YouTube-@JoinNASNET-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
</p>

<p align="center">
  <a href="https://t.me/joinNASNET"><img src="https://img.shields.io/badge/Telegram-Channel-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel"></a>
  <a href="https://t.me/joinNASNETGroup"><img src="https://img.shields.io/badge/Telegram-Group-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Group"></a>
</p>

<p align="center">
  <a href="https://starlink4iran.com/"><img src="https://img.shields.io/badge/Website-starlink4iran.com-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
</p>

<p align="center">
  <img src="starlink-vs-akhond.jpg" alt="Comic: the internet is switched off in Iran, but Starlink and NasNet Connect bring people back online" width="600">
</p>

**NasNet** builds tools for **safely using Starlink and similar satellite internet in repressive and censored environments**, such as Iran. When governments cut the cables, we look to the sky. 🚀

In countries with heavy censorship and frequent internet shutdowns, satellite internet is a lifeline — but using one can put you at risk. That's where we come in. Our mission: get people onto the free and open internet **safely** — hiding the fact that a satellite connection is in use, protecting the identity and location of operators and users, letting one dish be safely shared with many people over VPN, and making it all simple enough that you don't need to be a network engineer to stay safe.

## 🔥 What we're about

- 🛡️ **Safe Starlink usage in censored regions** — IP masking to hide the digital footprint of using a Starlink (or similar) connection when accessing domestic sites and apps
- ⚡ **Resilience against internet shutdowns** — connectivity that keeps working when the national network goes dark
- 🤝 **Community connection sharing over VPN** — one dish doesn't have to mean one household. Turn a single satellite connection into a lifeline for your neighbors, your street, your city — locally over WiFi, and remotely through encrypted VPN tunnels
- 🧭 **Radical accessibility** — automated, easy-to-follow setups so anyone can protect themselves, no expertise required

## 📡 One dish, many people: sharing Starlink over VPN

A Starlink dish is scarce and expensive in places like Iran — but a single dish can carry far more than one household. Our tools let a dish owner run a **VPN server on their own router**, so that trusted friends, family, and neighbors can tunnel through the satellite connection from wherever they are:

- 🏠 **Next door** — neighbors join over dedicated guest WiFi networks, each with their own username and password
- 🌆 **Across the city** — people still on the domestic network connect through an encrypted VPN tunnel (WireGuard, OpenVPN, or Outline keys) and come out on the free internet via your dish, even mid-shutdown
- 🕶️ **Safely** — the tunnel is encrypted end-to-end, the Starlink's digital footprint stays masked, and the dish owner keeps full control over who connects and how much bandwidth they use

Every project below is built around this idea: **NasNet Connect** turns a MikroTik router into a multi-client VPN server for the people you trust; **NeighborLink** and **CityLink** scale the same model up to whole neighborhoods and cities.

## 🚀 Our projects

### [NasNet Connect](https://github.com/nasnet-community/connect/tree/main)
The flagship. A free, open-source MikroTik router config generator built specifically for using Starlink safely in Iran. Answer a few questions, get a ready-to-apply configuration that protects your privacy and keeps your satellite connection hidden — no networking expertise required. Packed with features:

- 🕶️ **IP masking for Starlink** — hides the digital footprint of your satellite connection when accessing domestic sites and apps
- 🔀 **Split tunneling** — intelligently routes domestic and foreign traffic separately
- 🔐 **Built-in VPN server for sharing your connection** — runs WireGuard and OpenVPN servers with multi-client support, so friends and family beyond your WiFi can tunnel into your router and get online through your Starlink
- ⚙️ **Automated router setup** — no manual MikroTik configuration needed
- 🎮 **Game-specific port forwarding** with an integrated game database
- 📊 **Network monitoring** with performance visualization
- 🧰 **SSL/TLS certificate management**, **DDNS support**, **NTP synchronization**, and **scheduled automatic updates**
- 🌍 **Multi-language interface** — English and Farsi

### [NeighborLink & CityLink](https://github.com/nasnet-community/solutions/tree/main/neighbor-link#readme)
One dish, a whole neighborhood online. A custom OpenWRT firmware image that turns an affordable TP-Link router into a Starlink-sharing hub:

- 📶 **NeighborLink** broadcasts password-protected guest WiFi networks for the people around you, with per-neighbor usernames and passwords so the dish owner stays in control
- 🔑 **Remote sharing via VPN** — a WireGuard tunnel masks the Starlink's IP, and shareable Outline keys let people connect from beyond WiFi range
- 🌆 **CityLink** extends the reach city-wide: a domestic VPS relays VPN traffic to the dish, so anyone in the city can reach the free internet through it — no line of sight to your rooftop required

### More coming soon… 👀
We're cooking up new tools and solutions. Follow us on our socials above to be the first to know — you won't want to miss what's next.

## 💜 Get involved

All of our projects are **fully open-source** — built in the open, by the community, for the community. Whether you write code, test on real hardware, translate, design, document, or just have ideas, there's a place for you here. Jump into any of the repos above, open an issue or a pull request, or come chat with us on [Telegram](https://t.me/joinNASNETGroup). Every contribution helps keep someone connected. 🌐

---

⚠️ **A note on safety:** Using satellite internet in countries where it is restricted can carry serious legal and personal risks. Our tools aim to reduce those risks, but no tool can eliminate them entirely. Understand your local situation and threat model before deploying anything.
