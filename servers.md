<style>td{border:1px solid #d9d9d9;}</style>
<table>
<tr>
  <td><a href="/">Home</a></td>
  <td><a href="/react">ReactJS</a></td>
  <td><a href="/laravel">Laravel</a></td>
  <td>Servers</td>
  <td><a href="/tools">Tools</a></td>
  <td><a href="/contact">Contact</a></td>
</tr>
</table>

This page highlights some accomplishments in working with servers over the past few years such as CloudFlare configuration, SSL certs, NGINX and customizing open source software.
<ol>
  <li><a href="#servers">Servers</a></li>
  <li><a href="#cloudflare">CloudFlare</a></li>
  <li><a href="#nginx">NGINX</a></li>
  <li><a href="#ssl">SSL</a></li>
  <li><a href="#software">Server Software</a></li>
  <li><a href="#security">Security</a></li>
  <li><a href="#wordpress">Wordpress</a></li>
</ol>

## Servers
Originally using HostGator's shared hosting, as my experience grew I expanded into home servers using XAMPP. Currently I use Linux VPS servers in Ubuntu.
## CloudFlare
CloudFlare was originally my choice of sites for SSL Certificates, but I have since grown to appreciate it as a metric for gauging user counts and geography, saving bandwidth, managing DNS and provide simple DoS security.
## NGINX
Of the choice between Apache and NGINX I will chose NGINX due to both familiarity and an easier experience building complicated location blocks. On my servers I have made them alternate between one UI or the other depending on if a cookie is present, configured subdomains, handled file retrievals with no extensions, used it for proxying. While this is all possible on Apache, NGINX comes across as easier. Rate limiting in NGINX is a simple task with lots of depth.
## SSL
Typically servers will run end-to-end encryption using both cloudflare and a LetsEncrypt Certificate. While I have used both individually redundancy in security scenarios is better than optimization and assures privacy of data to anyone in-between.
## Software
My servers run Ubuntu on them since it is my work environment of choice. It's simple GUI and standard Linux terminal allow for seamless updates between development and production servers. It's file system allows for easy transfers between server and work environments. Nothing could be a more simple OS for working with servers. MySQL is often used due to familiarity.
I have also used a Squid Server to mask the IP of a website hidden behind CloudFlare which makes requests to websites at client's requests.
## Security
My servers make use of long passwords and restrictive permissions. When required I use a custom captcha and run scripts to remove abusive IPs from services as they appear in spam databases and proxy websites. While CloudFlare is a good tool for DoS  prevention, good NGINX rate limiting is important as well. CloudFlare's CSAM scanner helps to handle the issues of illegal material being posted to websites.
## Wordpress
In my time some servers have run wordpress for blogs. I don't proclaim to be an expert with it, but I have used it.

<table>
<tr>
  <td><a href="/">Home</a></td>
  <td><a href="/react">ReactJS</a></td>
  <td><a href="/laravel">Laravel</a></td>
  <td>Servers</td>
  <td><a href="/tools">Tools</a></td>
  <td><a href="/contact">Contact</a></td>
</tr>
</table>
