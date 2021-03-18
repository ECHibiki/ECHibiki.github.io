<style>td{border:1px solid #d9d9d9;}</style>
<table>
<tr>
  <td><a href="/">Home</a></td>
  <td><a href="/kissufr">Kissu-Fr</a></td>
  <td><a href="/banners">Community-Banners</a></td>
  <td><a href="/vi">Hazuki+Vichan</a></td>
  <td><a href="/tools">Tools</a></td>
  <td><a href="/contact">Contact</a></td>
</tr>
</table>

## Community Banners
<img src="/banners.png" style="border:1px solid grey"/>
A React web application for rotating user submitted artwork. This functions as a parody of websites with banner advertisements. Instead of showing  a product the banners contain user submitted artwork or artwork with URLs to interesting content. Users sign up for the application with a username and email. Moderators make sure that content is following the rules while the software prevents duplicates and spamming. A master list of all submitted content is available with filters.
### Technology
Uses Laravel and React. Laravel manages JWT authentication and allow for users submit content. Art data is submitted into a MySQL database table through a React user interface. It is a partially single-page-application not using any extra dependencies.
Blockhash, a library for perceptual/fuzzy hashing, prevents duplicates from being posted eliminating most possible spam vectors. A cooldown for logging into accounts prevents bruteforce attacks. Through the UI moderators may ban users or delete artwork. They may also shadowban(ban without letting them known) by leaving their images in the rotation only for them, not letting anyone else see their artwork, a useful tool against abusers with many proxies.
### Site
<a href="https://banners.kissu.moe">banners.kissu.moe</a>

<table>
<tr>
  <td><a href="/">Home</a></td>
  <td><a href="/kissufr">Kissu-Fr</a></td>
  <td><a href="/banners">Community-Banners</a></td>
  <td><a href="/vi">Hazuki+Vichan</a></td>
  <td><a href="/tools">Tools</a></td>
  <td><a href="/contact">Contact</a></td>
</tr>
</table>
