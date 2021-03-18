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

This page showcases some tools that I have built to achieve certain tasks on platforms such as bots, extensions or database fixers. They are simple descriptions of items built, some which no longer exist.

## 4Taba Archiver

  This Golang application takes a thread on 4taba.net and stores it as a json file with thumbnails and images stored in a tar.gz file available for download. It was done as a prototype for Kissu's API engine. Archive files are not stored on the server, but generated for each user individually.

## IRC YouTube Bot

  Typescript and NodeJS server reads an IRC channel and displays links for YouTube videos that get posted. Was later expanded to handle any URL reading the title field of HTML documents.

## Database Citation Fixer

  Simple Ruby script to scan Vichan's database and create a new citation table. From a posts table it reads the body of a post and determines if anyone is responding to it. If so it will add this data into the citation table. Was required to fix errors in Kissu's API engine.

## Tweet queue

  One of my earliest projects in PHP allowed for myself to add tweets to submit over a longer duration. I would fill up a queue of tweets in the morning and when I was out at classes it would release a tweet every hour making the account seem active 24/7. This made use of Twitter's API and Cron to release posts over a set period of time. Queue data was stored in a MySQL database.

## Automatic Github Backups

  Was a component of a program that logged data on a website. Said PHP server would store data as JSON and MySQL data. This bot would read the entire directory, omitting sensitive information, and store it on a Github account through it's API and a backup repository. The PHP script ran whenever Cron called it.

## Website Content Aggregator

  This Python bot scanned a list of websites using an open source software and stored their JSON data in a database for others to fetch.

## Proxy Tester

  This Python script would take a list of proxies and run requests on a site I owned. If it got back a response before timing out then the proxy was active, if it did not the proxy was dead. By doing this I populated a list of working proxies for testing sites in different geolocations.

## Userscripts for websites

  Userscripts were how I got into web programming in the first place. Whiles some were extensions that enhanced the experience of browsing, some were userscripts that enhanced other userscripts.

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
