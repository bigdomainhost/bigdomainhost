## Bigdomainhost

We're a small Indian hosting company, run by Parth Sharma since September 2026. We sell KVM VPS, cPanel hosting, reseller plans and dedicated servers out of two Tier III data centres inside India: Mumbai (BOM-1) and Delhi NCR (DEL-1). Users in the south are served from Mumbai, which sits at 28–40 ms from Bangalore. We don't have regions outside India, so if most of your visitors are abroad we're probably not the right host for you.

Website: **[bigdomainhost.com](https://bigdomainhost.com/)**

This GitHub is where we put small tools and scripts we write for our own servers and think other people could use. Start with [vps-first-boot](https://github.com/bigdomainhost/vps-first-boot), a script we wrote to harden a fresh Ubuntu or Debian VPS on day one.

For quick reference, [linux-server-cheatsheets](https://github.com/bigdomainhost/linux-server-cheatsheets) has one-page cheat sheets for SSH, ports, SFTP, npm, HTTP and Chrome errors, and the first boot of a new VPS.

### What we run

| Product | |
|---|---|
| Web & cPanel hosting | [cpanel-hosting](https://bigdomainhost.com/cpanel-hosting.html) |
| WordPress hosting | [wordpress-hosting](https://bigdomainhost.com/wordpress-hosting.html) |
| Reseller hosting (WHM) | [reseller-hosting](https://bigdomainhost.com/reseller-hosting.html) |
| KVM VPS, Mumbai and Delhi NCR | [vps-hosting](https://bigdomainhost.com/vps-hosting.html) |
| VDS (dedicated vCPU cores) | [vds-hosting](https://bigdomainhost.com/vds-hosting.html) |
| Dedicated servers | [dedicated-servers](https://bigdomainhost.com/dedicated-servers.html) |
| GPU servers | [gpu-server-hosting](https://bigdomainhost.com/gpu-server-hosting.html) |

Also Tally on Cloud, Minecraft servers and fixed-quote web development. Current prices for every plan are on the [pricing page](https://bigdomainhost.com/pricing.html); hosting renews at the rate you signed up on. Orders and the client area are at [cloud.bigdomainhost.com](https://cloud.bigdomainhost.com). Setup guides live in the [docs](https://bigdomainhost.com/docs.html).

### Guides we've written

**Getting started**
- [How to host a website in India, step by step](https://bigdomainhost.com/guide-how-to-host-a-website.html)
- [Domain vs hosting: how they work together](https://bigdomainhost.com/guide-domain-vs-hosting.html)
- [VPS full form: what a virtual private server is](https://bigdomainhost.com/guide-what-is-vps.html)
- [VPS vs shared hosting: which one do you actually need?](https://bigdomainhost.com/guide-vps-vs-shared-hosting.html)
- [What is cPanel, and do you need it?](https://bigdomainhost.com/guide-what-is-cpanel.html) · [What is WHM?](https://bigdomainhost.com/guide-what-is-whm.html)
- [What a web server does: Apache, Nginx and LiteSpeed](https://bigdomainhost.com/guide-what-is-web-server.html)
- [How the SSL/TLS handshake works](https://bigdomainhost.com/guide-ssl-tls-handshake.html)
- [वेब होस्टिंग क्या है? (Hindi)](https://bigdomainhost.com/guide-web-hosting-kya-hai.html)

<details>
<summary><b>Running a Linux VPS</b></summary>

- [Set up and secure a new Ubuntu 24.04 VPS](https://bigdomainhost.com/guide-ubuntu-vps-initial-setup.html)
- [How to SSH into a server](https://bigdomainhost.com/guide-how-to-ssh-into-server.html) · [SSH keys](https://bigdomainhost.com/guide-ssh-keys.html) · [SSH tunnels](https://bigdomainhost.com/guide-ssh-tunnel.html) · [SFTP and SCP](https://bigdomainhost.com/guide-sftp-scp.html)
- [SSH "connection refused" on port 22](https://bigdomainhost.com/guide-ssh-connection-refused.html)
- [Point your domain at a VPS](https://bigdomainhost.com/guide-point-domain-to-vps.html)
- [How much RAM does a VPS need?](https://bigdomainhost.com/guide-how-much-ram-does-a-vps-need.html)
- [Cron jobs and why yours isn't running](https://bigdomainhost.com/guide-cron-jobs.html)
- [Deploy a Flask, Django or FastAPI app](https://bigdomainhost.com/guide-deploy-python-app-vps.html)
- [Install cPanel and WHM on a VPS](https://bigdomainhost.com/guide-install-cpanel-on-vps.html)
- [Find and fix slow MySQL queries](https://bigdomainhost.com/guide-fix-slow-mysql-queries.html)
- [Which Ubuntu version am I running?](https://bigdomainhost.com/guide-check-ubuntu-version.html)
</details>

<details>
<summary><b>Fixing website errors</b></summary>

- [403 Forbidden](https://bigdomainhost.com/guide-403-forbidden.html) · [500 Internal Server Error](https://bigdomainhost.com/guide-500-internal-server-error.html) · [502 Bad Gateway](https://bigdomainhost.com/guide-502-bad-gateway.html) · [504 Gateway Timeout](https://bigdomainhost.com/guide-504-gateway-timeout.html)
- [ERR_CONNECTION_REFUSED](https://bigdomainhost.com/guide-err-connection-refused.html) · [ERR_CONNECTION_RESET](https://bigdomainhost.com/guide-connection-reset.html) · [ERR_TOO_MANY_REDIRECTS](https://bigdomainhost.com/guide-err-too-many-redirects.html)
- [ERR_SSL_PROTOCOL_ERROR](https://bigdomainhost.com/guide-err-ssl-protocol-error.html) · [NET::ERR_CERT_DATE_INVALID](https://bigdomainhost.com/guide-net-err-cert-date-invalid.html) · [DNS_PROBE_FINISHED_NXDOMAIN](https://bigdomainhost.com/guide-dns-probe-finished-nxdomain.html)
- WordPress: [install it](https://bigdomainhost.com/guide-install-wordpress.html) · [database connection error](https://bigdomainhost.com/guide-error-establishing-database-connection.html) · [white screen of death](https://bigdomainhost.com/guide-wordpress-white-screen-of-death.html) · [plugin not working](https://bigdomainhost.com/guide-wordpress-plugin-not-working.html) · [speed for Indian visitors](https://bigdomainhost.com/guide-wordpress-speed-optimization-india.html)
</details>

<details>
<summary><b>Choosing and moving hosts</b></summary>

- [Comparing VPS hosting providers in India](https://bigdomainhost.com/guide-best-vps-hosting-india.html)
- [Best web hosting in India: cPanel, WordPress and reseller compared](https://bigdomainhost.com/guide-best-web-hosting-india.html)
- [Best dedicated servers in India](https://bigdomainhost.com/guide-best-dedicated-server-india.html)
- [What a server costs in India, in rupees](https://bigdomainhost.com/guide-server-cost-india.html)
- [Switch web hosts with zero downtime](https://bigdomainhost.com/guide-migrate-website-to-new-host.html)
- [Who hosts a website? Find out with dig, whois and RDAP](https://bigdomainhost.com/guide-who-hosts-a-website.html)
</details>

<details>
<summary><b>Tally and Minecraft</b></summary>

- [Tally remote access](https://bigdomainhost.com/guide-tally-remote-access.html) · [Tally on mobile](https://bigdomainhost.com/guide-tally-on-mobile.html) · [TallyPrime backup and restore](https://bigdomainhost.com/guide-tally-backup.html) · [Tally multi-user](https://bigdomainhost.com/guide-tally-multi-user.html)
- [How much RAM a Minecraft server needs](https://bigdomainhost.com/guide-minecraft-server-ram.html) · [Make a Minecraft Java server on a VPS](https://bigdomainhost.com/guide-make-minecraft-server.html)
</details>

### Support

Phone **+91 75994 50220** during IST working hours, or WhatsApp any time, or email support@bigdomainhost.com. Hindi or English, answered by the engineers, not a call centre.

For bugs in anything on this GitHub, open an issue on the repo instead. It's easier for everyone to follow there.
