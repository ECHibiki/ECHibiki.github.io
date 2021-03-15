
<table>
<tr>
  <td><a href="/">Home</a></td>
  <td><a href="/react">ReactJS</a></td>
  <td>laravel</td>
  <td><a href="/backend">Backend</a></td>
  <td><a href="/tools">Tools</a></td>
</tr>
</table>

## Community Banners
<img src="/banners.png" style="border:1px solid grey"/>
A React web application for rotating user submitted artwork. This functions as a parody of websites with banner advertisements where instead of showing off a product, it's user submitted artwork and URLs. Users sign up for the application with a username and email. Moderators make sure that content is following the rules and the software prevents duplicates and spamming. A master list of all submitted content is available with filters.
### Technology
Uses the Laravel, React and NGINX. Laravel manages JWT authentication to allow for users to connect as long as they have a web token. Art data is submitted into a MySQL database table through a React user interface that focuses around simplicity. It is a partially single-page-application not using any extra dependencies.
Blockhash, a library for perceptual/fuzzy hashing, prevents duplicates from being posted eliminating most possible spam vectors. A cooldown for logging into accounts prevents bruteforce attacks. Through the UI moderators may ban or delete artwork. They may also shadowban(ban without letting them known) by leaving their images in the rotation only for them, not letting anyone else see their artwork, a useful tool against abusers with many proxies.
### Site
<a href="https://banners.kissu.moe">banners.kissu.moe</a>

<table>
<tr>
  <td><a href="/">Home</a></td>
  <td><a href="/react">ReactJS</a></td>
  <td>laravel</td>
  <td><a href="/backend">Backend</a></td>
  <td><a href="/tools">Tools</a></td>
</tr>
</table>
