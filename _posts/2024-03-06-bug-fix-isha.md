---
layout: post
# If your post title is longer or more complicated
# than can be represented in the filename, uncomment the following line
# and specify a custom title
# title:  "Wincuts Bug Fix"

# Uncomment only one of the below categories
categories: 
- Bug Fix
#- Contribution


# Enter your name below
author: Isha Errande
---

## Introduction to the Community 

The community I chose came from the recommended list of communities that I found through a link in the CHAOSS presentation
slides. I am relatively new to contributing to FOSS communities, so I wanted to find something that would get me familiar 
with contributing for the first time as my bug fix. 

The community I chose was [Wincuts](https://github.com/LyubomirT/wincuts)  It is a relatively very new FOSS project that
is looking for more contributers. The software is in charge of setting up and managing custom keyboard shortcuts. The
primary languages that the software is coded in are python,HTML, and CSS. The main contributer of this community is 
LyubomirT. He was very welcoming when I asked to be assigned and stressed that I was new to contributing. This made
me even more willing to contribute to this community. 

From the Comm Arch presentations good communities have good documentation, contributing guidelines, and a welcoming 
community. I chose this community because the languages were semi familiar to me, as my specialty is low level languages
with some experience in python. 

It was challenging to find a community because of how intimidating some of the content was for me to at least partially
understand. A lot of my time was spent finding this community.

## The Issue

So I reached out and was assigned the issue relating to moving icons to a directory and relinking them. This was issue #4.
![image](https://github.com/ise8933/hfoss2024-blogs/assets/90360951/c34cbb76-e652-412c-81ff-faf8c91848cd)

At first I was a bit intimidated to contribute as I was getting some issues with github. I usually would create a branch 
and merge. I was not familiar with forking. After resolving that I simply moved the two icons into a seperate directory, and created a pull request. 
![image](https://github.com/ise8933/hfoss2024-blogs/assets/90360951/9393433b-1a18-404b-8a7f-71c946da3e27)

Unfortunately, I did not completely fix the issue. The icons are supposed to be relinked. I am planning on making this apart
of my bigger contribution assignment, however i did get to a start on where the changes may need to be made. 
```
self.setWindowIcon(QIcon("logo.png"))
self.tray_icon = QSystemTrayIcon(self)
self.tray_icon.setIcon(QIcon("logo.png"))  # Set your own icon
```
I was unfamiliar with the self.tray_icon.setIcon() method. I looked at python documentation, however I still got stuck. 
Due to time constraints, I have settled with my current contribution for a bug fix, as I contacted the contributor very 
last minute. In the future, I will make sure to clarify my questions early on in the main contribution. 





