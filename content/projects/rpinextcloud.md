---
title: "Raspberry Pi Nextcloud server"
description: "Self-hosted cloud storage server on a Raspberry Pi"
date: 2022-04-07T16:15:00Z
tags: 
    - projects
    - server
categories:
    - Projects
draft: false
---
![A Raspberry Pi single-board computer](/images/rpicloud/IMG_20220408_080338.jpg)

# What is it?
This is a [Raspberry Pi](https://www.raspberrypi.org) running the software [Nextcloud](https://nextcloud.com). The Raspberry is a low-cost single-board computer. It can be used for a wide variety of cases, like robotics or controlling electrical devices. Nextcloud is an open-source program that allows you to store your files on a server of your choice or even your own.

# Why not Google Drive/OneDrive/Dropbox?
The moment you upload a file to one of these sites you've pretty much lost control of it. Cloud storage at the end of the day is little more than uploading your files to someone else's computer. But where is that computer? What do they do with my data? Will Sundar Pichai look at my files for his own pleasure? Those are questions we can't really answer due to the closed-source nature of these services along with their shady reputations when it comes to privacy.

In this day and age, we seem to be taking data privacy and security more seriously than before. I myself have come to realise that big tech has too much power on the internet and that privacy-respecting alternatives are the right way to go.

# How does it work?
Basically, it involves installing PHP and Apache on your server then installing Nextcloud. After that you have to configure where the files are stored, the trusted domains and link the server's public IP to your domain through its DNS settings. Sound complicated? It is, I had to follow a tutorial [(this one)](https://pimylifeup.com/raspberry-pi-nextcloud-server/). The fact I even managed to follow that tutorial I already consider an achievement.

# What can you do?
![The Nextcloud dashboard in a Vivaldi browser window. The top text says "good afternoon" and below is a list of files](/images/rpicloud/dashboard.jpg "The Nextcloud dashboard")
The basic functionality is that you can upload files to it and store it there to access it on any device with an internet connection, just like any other cloud storage service. With a domain name you can access these files outside your home network. Extra functionality can be added through addons called "apps".

# Conclusion
It feels great having full control of my own files again, after years of trusting Google and Microsoft. If it all works I plan to stop uploading my phone's photos to Google Photos and move over to this server. I still need to figure out how to setup redundancy though.