---
layout: post
title:  "Will we be able to upload our minds?"
date:   2020-05-25 13:00:00
categories:
---


This is an expansion of an argument I made on [Twitter](https://twitter.com/ClarissaAdjoint/status/1262550425556774914) recently, fleshed out a little bit more solidly.

So a trope of post-humanist/futurist discourse is the idea that we will someday be able to upload human consciousness to computers. Very Serious People make predictions around this. It's talked about in some rationalist circles like it's an inevitability.

I personally think it's a little silly and let me explain why.

One thing that a lot of people seem to neglect in any discussions of future-tech is that *computation has limits*. I'm serious. It's something a lot of professional programmers I've met don't even believe: that there are things that are **inherently** not computable. One of the most famous of these is the halting problem, in part because that was the problem Turing showed wasn't solvable by a computer as a part of showing the very *existence* of incomputable problems. 

Just for completeness, let's give a rough sketch of what the halting problem's problem is: 

-   We want to know if there can exist a program that will, when handed the source code of another program, be able to predict with perfect accuracy whether the program will halt or enter an infinite loop
-   If such a program existed, let's call it `H`, then we should be able to write another program `P` that
    -   Reads the source code of another program
    -   Runs `H` on this source
    -   Then, if the program read in halts `P` should go into an infinite loop and if the program goes into an infinite loop then `P` should halt
-   What happens to `P` when it reads in its own source ?
    -   If it halts then it loops
    -   If it loops then it halts

So this is an example of a program that *can't* exist. You could write down a perfectly well-defined function in mathematics that would correspond to the halting problem, you just can't write down an algorithm that implements it. 

There's another argument that I think is illustrative for *why* there are limits on computation and it depends on simple cardinality. Let's hit this argument quick:

-   The number of functions from the natural numbers to the natural numbers is the same cardinality as the real numbers
-   The number of computable functions (in a Turing complete language) corresponds roughly to the number of programs you can write in the language
-   The number of programs you can write in a language is the same as the number of finite length pieces of text with a finite alphabet (no sneaking in an infinite number of unique symbols, since that just makes the program interpreter non-computable)
-   The number of finite texts can be written is the size of the natural numbres

So, in other words, there are way fewer possible programs than functions you'd want to compute. Yikes! Well, what about hhuman consciousness. Now, I want to be very clear that I'm not saying human consciousness is *not* computable, that this is something I know or have proven. My problem is that *no one else knows either*. 

In fact, I think the assumption that we'll be able to upload our consciousness is a kind of strangle hubris. When there are so many things that aren't computable, and strictly speaking there are so many more incomputable than computable functions that if you could choose a function completely at random you would have 0% chance of selecting a computable one, it seems odd that a naturally evolving process we so personally find important would just happen to be computable. 

I'm being sincere, here. I think the assumption here presumes a certain kind specialness to human existence that I don't find plausible. If what our brains do naturally translated to a computable process I'd practically consider that evidence we were living in a universe designed **for** us.

Now, am I saying **consciousness** is inherently not computable? No, actually. I think there might be some kind of computable consciousness&#x2014;I just think that it's going to inherently look differently than something developed through natural selection like ours was. 

My only point is that I want to see a little more humility and realism coming from people talking about the future of the tech sector. 

