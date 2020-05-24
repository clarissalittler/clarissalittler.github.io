---
layout: post
title:  "Machine learning and a perspective on science"
date:   2020-05-23 20:30:00
categories:
---


Yesterday, I saw an [infuriating](https://twitter.com/Abebab/status/1263806588734840833) bit of "machine learning" pseudo-science that, well, made me get a [little](https://twitter.com/ClarissaAdjoint/status/1263856811670564864) [angry](https://twitter.com/ClarissaAdjoint/status/1263860582635036674) on the internet. I'd be planning to write a post like this already but now seemed as good a time as any to write this argument. Namely, I want to explain what I mean when I claim that if you don't *understand* what a trained system is doing or what features it's making decisions on, if you don't have an underlying way of drawing conclusions from what it's doing, then *you aren't doing anything that could be called science*.

Now my argument is more philosophic than exactly mathematical, but I want to start with Chaitin's thoughts on scientific theories from an information theoretic perspective. I'm combining thoughts of his from *Meta Math*, *Goedel's Way*, and *Proving Darwin*. All books I **mostly** recommend modulo the caveats that he tends to be self-aggrandizing and have oddly inappropriate digressions in places.

The idea is that you can think of a scientific theory, roughly, as a *compression* of the observations it is attempting to explain. This seems like an odd perspective to take but it makes a kind of perverse sense: Kepler's laws can be inverted to be seen as a generator for stable orbits. You could then see Newtonian gravitation as a further compression, reducing even still the information needed to generate the same orbits. In this way, you can see measure the usefulness of scientific theories based on *how* much of a compression they are of the observations they're encoding. 

Now, if you see where I'm going with this you might say "yes! that's exactly what machine learning is doing!" and I agree if and only if we're able to understand what the calculated function is doing, extracting the principles that have been discovered&#x2014;if they exist, of course, I say pointedly in the direction of the *Iris* program I linked to above. Until we've done that, I think from the semi-informal information theoretic perspective above you are not just carrying the weights and geometry of the neural net but also *all the observations you've trained it on*. My argument for this is that without independent principles derived and understood from the results of the training, you cannot "debug" the predictions without having all of this data at hand. In this way, you've done anti-science: you've expanded the information burden of the predictions to beyond the initial observations.

And who wants to be *anti-science*?

