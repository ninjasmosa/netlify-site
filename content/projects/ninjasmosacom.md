---
title: "ninjasmosa.com"
date: 2022-02-23T15:56:00Z
tags: 
    - projects
    - website
categories:
    - Projects
draft: false
---
# About the website
{{< figure src="/images/websitedata/ninjasmosa.com.jpg" align="center" caption="Screenshot of my new website" border="white" >}}
This website was built using Hugo, a static website builder coded in Go, and hosted on Cloudflare Pages (previously Netlify). The source code can be seen [on GitHub](https://github.com/ninjasmosa/ninjasmosa.com).

Written in a mix of markdown, HTML and CSS, I made this to replace my old website which was built on Google Sites, after finding it restrictive and being unable to get the custom domain to properly work. Not only that it was also quite bloated, being slow to load on slow internet and was also tied to a big tech company. While the old website will continue to remain available [here](https://sites.google.com/view/ninjasmosa), this new one is what I will be updating long-term.

# A bit of history
## The origins
In late 2021 I had the idea to create a website. I decided to use [Google Sites](https://sites.google.com/new) because of its ease of use and how good a website can look with it. ~~The old website is currently still available on [https://sites.google.com/view/ninjasmosa](https://sites.google.com/view/ninjasmosa).~~ **UPDATE: The old website is no longer online.**

In the end I was quite proud with how everything turned out.
{{< figure src="https://pbs.twimg.com/media/FMStW6bWUAAl4LM?format=jpg&name=large" align="center" caption="Screenshot of my old website" border="black" >}}

## However I wanted more
After a few weeks I realized that Google Sites was as bare-bones as website builders got. There wasn't a lot of features and there wasn't a lot of customisability on offer. Also Google is a big tech company known for constantly closing down old products and selling your data to the highest bidder. That was when I decided to consider other options.

### WordPress woes
Initially I decided to move over to WordPress. It was simple yet powerful. However there were problems I had that made me scrap these plans.

#### Hosting provider horrors
After some research it turns out that the only good free web hosting provider out there was 000webhost. Even then they were still nothing but problems. Not only were the bandwidth and storage limits severly restrictive, but that getting WordPress to work under this was nothing but problems. Sometimes trying to remove an extension would completely nuke my whole setup and trying to do some things wouldn't work at all. I did briefly decide on hosting it on my Raspberry Pi but I didn't proceed with this in the end.

#### Hackers ahoy
Because WordPress is like the biggest CMS out there (43% of websites run off WordPress), it was also a prime target for hackers to find backdoors and hack everyone's websites. It was then that I realized that maybe this WordPress thing isn't the way to go and reflected on the problems I had along the way.

### Hugo comes to the rescue
Just before I had lost all sense of hope I found out about [Hugo](https://gohugo.io), a fast and open-source website framework. After looking into it, this seemed perfect for what I wanted to do. Initially the idea of having to mess with markdown and config files initially seemed daunting to me but I got the hang of it quickly.

# Conclusion
This project has made me realise that there is a lot more than just the mainstream providers in the market. As a believer in the potential of free and open-source software It's great seeing that there need not be tech giants to hold monopolies or be in control of everything.