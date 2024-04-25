---
layout: post
# If your post title is longer or more complicated
# than can be represented in the filename, uncomment the following line
# and specify a custom title
# title:  "Dark Reader - Karl Choi"

# Uncomment only one of the below categories
categories: 
- Bug Fix
#- Contribution


# Enter your name below
author: Karl Choi
---

# What the project is

Dark Reader is a chrome extension that automatically applies a dark theme to sites that the user visits.
The github community works together mainly to fix specific site issues, add new color themes, and add new features.

# Why I picked it

1. Since I don't really have experience with contributing to an open source project, I wanted to pick a project I thought I would be actually be able to contribute to

2. I have previously used Dark Reader before, and I wanted to pick a project that had some personal relevance

3. The project seemed to have good onboarding

# Comm Arch Analysis

- The last commit was 3 days ago, so the project is pretty active.
- There are over 1200 contributors
- The contribution doc was pretty detailed and explained step by step how to contribute.
- The project has a license, readme, and code of conduct
- There are 1,000+ open issues, so there are many things that can be fixed or contributed to  
![Last commit](https://imgur.com/a/jRW2b58)  
![Contributors](https://cdn.discordapp.com/attachments/593856325641830489/1226861977620582450/image.png?ex=66264f41&is=6613da41&hm=df4493e986d2f4eed960e928ce7fd0401106df138f986232294fa4d3a8b75b82&)  
![Important docs](https://cdn.discordapp.com/attachments/593856325641830489/1226854241537359962/image.png?ex=6626480d&is=6613d30d&hm=df2e5a3c00a4971078e754586ad7452677cb07a125b2dade5d26fdd12997f0cb&)  
![Issues](https://cdn.discordapp.com/attachments/593856325641830489/1226861411767029760/image.png?ex=66264eba&is=6613d9ba&hm=e82fe185558faa8cb56ca6b1993feef3b1d4f8aa0f7c2ab551dbd412d03c536b&)

# The issue I picked

Contributions to the Dark Reader Github are mainly specific site fixes, so the issue I picked was a site for a transit system I used while I was in Seattle, Washington: myorca.com. The issue was that several instances of text and icons were not visible in the dark mode applied by the Dark Reader extension.
![Orca logo](https://cdn.discordapp.com/attachments/593856325641830489/1226857674583572500/image.png?ex=66264b3f&is=6613d63f&hm=e761a5e1fa1ca223aa8ed04c3879f7cd86d892e31d962e5766698b7f85132ba5&)

# How I went about pursuing it

I read the contributing doc on the Github for step by step instructions on how to fix specific issues on websites. I was then able to make the texts/icons visible through the extension's dev tools. One issue I had was trying to work with the extension's specific code formatting. In addition, most of the project is coded in TypeScript, which I don't really have experience in. However, I was eventually able to figure it out. I submitted a pull request, so I'm currently waiting for that to go through. There are only 5 open pull requests (including mine) and 7,000+ closed pull requests, so pull requests seem to be reviewed pretty frequently.
![Dev Tools](https://cdn.discordapp.com/attachments/593856325641830489/1226861599743148052/image.png?ex=66264ee7&is=6613d9e7&hm=c74825d1939074004ecc962ef24016912cc5ba958bad133069827a3fa8a6a74e&)
![Languages](https://cdn.discordapp.com/attachments/593856325641830489/1226861836498898964/image.png?ex=66264f1f&is=6613da1f&hm=cc20507f2e82323edbb22a507e3de9b2f79ec6c6a5ea6577fbbff0b5a5d9435e&)
![Pull Requests](https://cdn.discordapp.com/attachments/593856325641830489/1226862174408802305/image.png?ex=66264f70&is=6613da70&hm=ddfb186c3cf7bcff15157a00141ad96f50713dca41ff697ac538839687331ad9&)

# Before my fix
![Before1](https://images-ext-1.discordapp.net/external/t85oJlXFFEgCYKneQUw1g8LiIOjdGPGDvImLXt0638Y/https/github.com/darkreader/darkreader/assets/157659446/df2f34fa-3791-4add-88ab-9610fe948cd6?format=webp&width=1439&height=532)
![Before2](https://images-ext-1.discordapp.net/external/g91xc5hAHI85vduayH-maSjVPsp8b_WRiAN1VnyQtms/https/github.com/darkreader/darkreader/assets/157659446/5957a5db-2303-418b-967e-aae71600cd47?format=webp&width=1196&height=701)

# After my fix
![After1](https://images-ext-1.discordapp.net/external/VWgnhGYCxt76yYy1SB1F4M-JD1zPOk5SejePO3Yx-3I/https/github.com/darkreader/darkreader/assets/157659446/e19fcda7-8d2a-403f-82ce-b6ff12f3eb7f?format=webp&width=1439&height=539)
![After2](https://images-ext-1.discordapp.net/external/hCfF0kHbNXKteBJBSfmAepzHH-umt5AoD8pGI-dOo60/https/github.com/darkreader/darkreader/assets/157659446/5bf87c2f-679a-420f-a4cb-8ee5c5864cdc?format=webp&width=1215&height=701)