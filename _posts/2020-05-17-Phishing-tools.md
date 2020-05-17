---
layout: post
title: Phishing Tools for Training Employees
---
# Phishing Tools
These are some tools for email phishing or web phishing

##GoPhish
It's an email phishing tool. With graphics and stadistics.
Installacçtión with docker:

`docker pull gophish/gophish`
>This command works fine for me:
´docker run -d --name gophish -p 3333:3333 -p 80:80 gophish/gophish´

[https://localhost:3333/](https://localhost:3333/)
> you can login from outside with your LAN ip instead "localhost"
> User: admin , password: gophish

In this video you can lear how to copy any email
[https://www.youtube.com/watch?v=ujjWqKFClOI](https://www.youtube.com/watch?v=ujjWqKFClOI)

Here you have some **email templates**

More information in:

[https://hub.docker.com/r/gophish/gophish/](https://hub.docker.com/r/gophish/gophish/)
> This is the original command:

´docker run -d --name gophish -p 3333:3333 -p 8083:80 gophish/gophish´

##Zphisher
[https://github.com/htr-tech/zphisher](https://github.com/htr-tech/zphisher)

Installation:

`sudo apt install git curl php openssh -y`

`git clone git://github.com/htr-tech/zphisher.git`
Give executable permission to the bash script by using following command:

`cd zphisher`

`sudo chmod +x zphisher.sh`

`bash zphisher.sh`

##Nexphisher
[https://github.com/htr-tech/nexphisher](https://github.com/htr-tech/nexphisher)

`apt update`

`apt install git -y`

`git clone git://github.com/htr-tech/nexphisher.git`

`cd nexphisher`

Execute the *setup* with admin priviledges
`sudo su`
`bash setup`

Then we can use NexPhisher

`bash nexphisher`