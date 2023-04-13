---
title: "Best way to speed up a bulk of HTTP requests in Python"
description: "How to web scrape as fast as possible & not get banned using Asyncio?"
featured_image: 'images/Project-2/Skateboard.jpg'
date: 2023-04-12T15:53:00+02:00
draft: false
tags: ["Python", "Data Collection"]
---

# Description:
I had a programming project that needs to read a bulk amount of insider transactions (form 4s) from sec.gov daily and build a rank list of the most successfull insiders in the US. Therefore I need to build a Python script that could make millions URL-requests efficiently, remove unneccessary form 4s and evaluate the remaining datas as Pandas DataFrame. In this Medium article {{< rawhtml >}} 
  <a href="https://gunardi-dashboard.herokuapp.com" target="_blank"><img src="/images/siteimages/link_icon.png" style="width:20px;height:20px;"></a>
{{< /rawhtml >}}, I will only concentrate on the downloader programming part.
