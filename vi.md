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


## Hazuki+Vichan+NPFChan

A backend software for handling posts to kissu.moe. It is a combination of modifications to an open source software known as Vichan along with a Golang API server which handles files for the React UI. This combined gives the website a feature deep, highly contributed open source software ; personal modifications allow for features such as polling, post voting, donation tokens and captcha ; and the Golang API server to add machine learning to abuse reports, automatic proxy bans, similar post features and a detailed API required for React page generation ; merges on NPFChan give basic archive functionality and improve on mod tools.  

### Technology
Vichan comes with Twig template engine and PHP code that has been modified since the early 2010s. My modifications to Vichan do not add extra libraries but add on top of what already exists, fixing problems as they appear, whether through PHP updates, outdated security standards or functional bugs. A merge of another fork of Vichan, NPFChan, adds archive functionality among other tools. In Golang, the Hazuki API engine reads from Vichan's MySQL database on http requests from Vichan. Primitive but effective Naïve Bayes spam filtering is ready to set up should there come a time when abuse reports are abused. The engine also handles an automatic backup system where upon a thread being deleted it automatically restores from archive.

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
