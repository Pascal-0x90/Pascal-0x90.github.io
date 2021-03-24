---
layout: post
title: After Class
date: 2021-03-18 13:33:28 -0700
categories: Thoughts
---

# Hello Again

It has been a while. In fact, almost exactly a year since I last wrote a post to
this blog. I have managed to reformat the blog as well to something that was a
bit more smooth and not as "cool". I do plan to mix it up later with a bit more
design geared towards computers, cybersecurity, or in general, hacking.

# Current Events

Since my blog post, some things have taken place:

- COVID-19 (shocker, betcha you did not know that)
- I graduated university (Woo!)
- Moved back home to start my job search

Now while these are nothing to write back home to, I do find that generally
these have been some key points; COVID itself has been the top of the talk in
any social circle now a days due to how much it has changed our lives. The
latter half of University was hellish I feel for both students and teachers
both. The fortunate part was how well we recovered as a system of teachers and
students to make this unfortunate situation work. For this, I am reminded just
how amazing some of the people who attend/attended my university are. I am
fortunate to have made it through my academic career, and despite what I know
now of how I did not require a degree to go far in my field, I do find myself
contempt with the fact I still did the degree. It helped me meet some amazing
people who I can call friends, and mentors. Furthermore, it helped me understand
and develop a better set of fundamental skills that I would otherwise be
lacking, had I not jumped into taking a degree in computer systems with cyber
security. <br> I am still a participating member in the Shellphish Capture The
Flag (CTF) team as well as am a participating member of the DevilSec cyber
security clubs. These two clubs have been keeping me busy and my mind on some
projects to help further develop some skills in creating tools, exploitation,
reverse engineering, and overall security research while I continue the great
job hunt. On that note, I would also like to say a word of advice:

> If you have an internship prior to graduation, I would try to get hired under
> that job before you leave so you have a job when you graduate.

It is a simple word of advice but it was one of the biggest mistakes I have done
thus far in my career. Despite this, I feel things have been going well. I will
continue to contribute to open source projects, creating my own projects, and
helping give back to the community which helped me discover something I love.

# Projects I am Working On

## Sliver

For some time now, I have been going through trying to debug some code for a
prototype reverse socks5 proxy for the Sliver C2 framework by Bishop Fox. So
far, it has come along well and I feel it is almost ready for a PR however, I am
currently dealing with some funky concurrency issues in Golang. While an amazing
concept concurrency is, if it is not handled well, it can easily get out of
control fast and you will have race conditions for days. These can cause some
inconsistencies in how a program operates; logic can be skewed by race
conditions as well as crashes could occur. The thing to keep in mind too, golang
does not have any sense of try catch therefore, we need to make sure no wacky
race conditions happen and proper mutexes are set in place. I have been slowly
going through and fixing these little weird write after read (WAR) or read after
write (RAW) race conditions.

## LOBAS CommandLine Tool

LOLBAS or also known as Living Off The Land Binaries and Scripts, is a website
much like [GTFOBins](https://gtfobins.github.io/) however, it allows a person
who is on a windows system to "Live off the land". The idea is to use any of the
binaries or scripts available on a system (in this case Windows) to accomplish
various tasks such as downloading and uploading files, obtaining a shell, and
AMSI bypasses. Our goal in this project is to use the currently existing
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) repo, and convert it into a
python project which will allow digesting of all known key binaries on a Windows
operating system, then present you your capabilities in a static web page
created with flask. Currently the repository is private but I do see its public
showing should be some time soon.

## Write-ups

I want to work through some more write-ups on CTF challenges, Hack the box
challenges, and Try hack me challenges. I do not know how frequent they will be
however, in the coming weeks, I am planning on putting out at least two per
week. It will vary over these different categories and I will make sure to label
them as such. If you do prefer some different challenges or if I am doing too
many of one type please message me over on Twitter, GitHub or on Discord at my
handle ( Pascal-0x90#1337 )
