---
layout: post
title:  "Paper Review: Computer Science and Metaphysics"
date:   2020-07-01 13:00:00
categories:
---


So today we'll be talking about a small little paper that I think is actually pretty neat: [Computer Science & Metaphysics: a Cross-Fertilization](https://arxiv.org/abs/1905.00787).

This is a paper on applications of theorem provers to philosophy. We won't be getting too deep into the weeds on it, though, because I think the general ideas are more interesting than the specific problem they tackle in this paper&#x2014;and I think the authors intended it as such.

Specifically, they're using my favorite prover---[Isabelle](https://isabelle.in.tum.de/)&#x2014;to tackle Goedel's ontologic proof for the existence of God. "Okay, hold up," I can practically hear people saying. Bear with me, but this basically has nothing to do with religion per se. It's entirely about how we reason about *abstract objects*. 

Abstract objects&#x2013;to simplify a little&#x2014;are things that we talk about in terms of their *properties* rather than having an actual example. Part of the inspiration for this is that we're clearly capable of reasoning about things that might not necessarily exist *or even whose existence is contradictory*. 

My type theorist friends are probably very familiar with the dangers of an empty type, which is capable of poisoning every conclusion because the empty type/logical false implies **everything**. However, we're obviously capable of reasoning about things like "a round square" that are contradictory by definition without concluding **literally anything** by holding these ideas in our head. 

Abstract objects are also important for dealing with *fictional* objects: which are weirder the more you think about them. As a side note, part of the weirdness of fictional objects is that we're capable of judging *equality* on them even without them being "real" in any reasonable sense. I can read fanfic of a tv show and understand that they're *the same setting* despite the fact that this world doesn't exist. It's one of those situations that seems very "well, duh" until you try to formalize this in some kind of logic&#x2014;a problem I find is often true in analytic metaphysics.

Finally, abstract objects have applications to the metaphysics of mathematics. We can discuss mathematical ideas solely by their properties without any appeal to whether or not math "exists". 

With all of that preface I hope it's clear why arguments about the existence of God can be really interesting from a formal logic perspective. 

So why do they use Isabelle? Isabelle/HOL has a few really nice features here:

-   excellent, reliable, automation
-   the possibility of classical reasoning
-   good support for opaque definitions

You add all of this up and you get that it's easy to embed their abstract object theory into Isabelle through a possible-worlds semantics, keep all the definitions opaque, and then feel confident that further proofs isn't depending on their semantic choices. Neat-o.

The rest of the paper is a really fun case study, with them exploring how they can tackle ambiguities in prior attempts to formalize this problem by hand. This work is only a year old and I'm *really* hoping to see this approach catch on.

