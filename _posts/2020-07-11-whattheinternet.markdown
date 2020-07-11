---
layout: post
title:  "What the internet could be"
date:   2020-07-11 15:00:00
categories:
---

I've been fairly disillusioned yet hopeful about the internet, lately. What I mean is that I've been fairly depressed over how bad everything seems to be, about how awful social media is at contributing to the decay of democracy and the spread of conspiracy theories, about how it seems to worm itself into our brain, about the lack of privacy.

[An article on the recent "Wayfair is trafficking children" conspiracy](https://www.newsweek.com/wayfair-child-trafficking-conspiracy-theory-cabinets-scandal-1517013)

[Musing by analogy about the problems with privacy we have on the commercial web](https://inconsistentuniverse.wordpress.com/2019/06/18/flecks-of-data-and-the-digital-self/)

[The insidiousness of social media from a phenomenologic perspective](https://inconsistentuniverse.wordpress.com/2020/03/16/incomplete-thoughts-spider-webs-the-extended-body-and-social-media/)

[My ranting on the slow centralization of the internet and the accumulation of computational capital](https://inconsistentuniverse.wordpress.com/2019/06/27/brief-thoughts-on-computational-capital/)

[An essay on the environmental problems of the modern www](https://alistapart.com/article/webwaste/)

At the same time, I've also been inspired by how many people want to fix it. I'm not a lone voice in the wilderness afterall! So I'm going to give an overview of the small swath of the non-commercial internet landscape.

So I want to summarize some of the infodump of links above on why I don't think the commercial web is a good thing, not anymore.

* It's become incredibly centralized, with a small number of companies controlling most of the infrastructure
* It's anti-convivial, with none of us having any real say in how the sites run by the big few operate
* It's wasteful, a massive waste of storage and energy that both accelerates the obsolescence of computational devices and is environmentally irresponsible
* It's invasive, with companies opaquely tracking us, building profiles of our identities, and potentially sharing those with government agencies

So what in God's name do we do given that much of what we're dealing with is a kind of consensus problem? The problem where everyone settles on the same platform because everyone else has settled for it Much like why almost everyone uses qwerty rather than dvorak layout on english keyboards. You use what everyone else uses because the cost feels too high otherwise.

Well there seem to be two separate (although contingently so, not necessarily) tracks happening:

* The distributed internet, as represented by things like Mastodon or the Beaker browser/platform
* The small internet of pubnixes, gopher, gemini &c.

For the distributed internet, there's the big conglomeration of servers people call the "Fediverse", including the social network Mastodon. I don't actually have a lot to say on this front because this isn't an area that's ever interested me. Plenty of other people have written about it, including how to run your own servers

[Darius Kazemi's small guide to running your own Mastodon derived social networks](https://runyourown.social/)

I think the most interesting thing in the distributed web space, currently, is the Beaker browser

[Beaker browser homepage](https://beakerbrowser.com/)

Beaker runs over the hyper:// protocol (formally using dat://) and serves web pages across a peer-to-peer version of the web. Beaker acts not only as peer-to-peer distribution node, and a web browser that can move seamlessly between the p2p and "normal" web but is also capable of functioning as a perfectly capable HTML and CSS editor. If I sound gushing that's because I think it's a really, really cool bit of technology and the Beaker team has done great so far. I love everything connected to dat://, hyper://, and attempts to build p2p technologies.

[The dat protocol page](https://dat.foundation/) 
[The hyper protocol page](https://hypercore-protocol.org/)

But! While I have nothing but heart eyes for this project

[copy of Heart Eyes vine (contains swears)](https://www.youtube.com/watch?v=leeP6LgM8H0)

That's not actually what I've been most excited about lately. No, that's more what I've seen people call the "small internet" (smol internet in tumblresque terminology), the world of pubnixes, tilde communities, and more.

Here I've been finding a world of, dare I say, intentional communities of people who are rejecting the commercial internet and trying to make something better. Unsurprisingly, in the little bit I've been exploring, it seems my anarchist leanings are overrepresented among the denizens of these spaces. These are places where people still use gopher rather than the web, where free shared space on linux servers is how communities are built. Most, but not all of it, asks you to be familiar with command line tools but I've also been finding these communities incredibly friendly towards people who want to learn more. Obviously, nothing is a monolith and your mileage may very, but I can at least say that my experiences have been really positive so far.

One thing I want to highlight in particular is Project Gemini

[The Project Gemini homepage ](https://gemini.circumlunar.space/)

The Gemini protocol gets, uhh, divisive comments on spaces like Hacker News

[An example thread](https://news.ycombinator.com/item?id=23042424)

but I'm rather fond of it so far. It's not a replacement for the web, it's meant as a small, stripped down, simple system that's easy to implement and low on resource usage relative to a web server. I agree with the people who characterize Gemini as a more powerful gopher than a minimal http. It's not supposed to be able to do everything, and the point is that you don't need most of the complexity of the web.

I've been simulblogging both on my github pages and my geminispace 
[My github pages blog](https://clarissalittler.github.io) 
[My geminispace](gemini://gemini.circumlunar.space/users/left_adjoint/)

and, in fact, I wrote the gemini version of this post first and converted to github's markdown standard afterwards.

You can get a small amount of server space on gemini.circumlunar.space by request for gemini hosting and I've really been pleased with the infrastructure that's being quickly built around the young protocol.

Now, you don't only have to interact with gemini by running your own server or connecting to someone else's with ssh & sftp (although those are the most flexibile methods). I personally love the site gemlog.blue, which is for blogging in gemini, and they have a very simple web interface for creating accounts or adding entries---as I said, gemini isn't trying to be a replacement for http.

[The web interface to the blogging site](https://gemlog.blue) 
[The gemini interface](gemini://gemlog.blue)

I have a more personal blog on this space that I've been updating regularly.

Finally, I want to say a few words about rawtext.club

[website for rawtext.club](https://rawtext.club) 
[gemini site for rawtext.club](gemini://rawtext.club)

This is an example of the kind of very small intentional community that I find kind of exciting. It's very minimalistic but it has all sorts of cool command line tools that have been built into it: things for journaling, writing internal "shell log" (shlog) posts, an internal asynchronous chat system, the room to host public web sites, gopher holes, and gemini spaces, and a lot more in terms of tools to write and make. Rawtext bills itself as "slow" internet, which I think is a fantastic perspective. I want slow. I want deliberate. I want to avoid. 

What are other spaces? There are a number of "tilde" communities such as
[tilde.town](http://tilde.town/) 
[tilde.pink (via web proxy)](https://proxy.tilde.pink/cgi-bin/proxy.cgi?q=tilde.pink)
[tilde.pink gemini site](gemini://tilde.pink)

and many more available via listing on the tildeverse
[The tildeverse](https://tildeverse.org/) 

So what's my conclusion? Am I claiming these technologies or communities are perfect? Absolutely not. What I want to stress is that I want even more of these and I am very clearly far from alone in that desire. People are actively inventing and creating in the small internet space and it seems to be changing very quickly. The gemini protocol is only roughly a year old and its community is growing by the day.

Part of my interest in this space is that I want to encourage gen z and younger to build these spaces for themselves. I'm excited by things like rawtext.club because they run with such minimal requirements that I can totally see running similar communities off of cheap single board computers like the rpi0, the exact kind of hardware I'm trying to put in the hands of teens who don't have access to any other true computer.

I think we're doing a horrible disserve to a lot of youth right now with these horrible, dysfunctional, online spaces. I don't like the way I'm seeing kids right now just accept a total lack of privacy or community online, or be kept in the dark on how to actually use computers unless they come from families that can afford something better than a smartphone or a chromebook. I think I want to try showing them how to make their own small internet spaces, ones that they can control and use to make and think and learn together. 
