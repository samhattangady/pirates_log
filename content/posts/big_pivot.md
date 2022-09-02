---
title: "Changing Directions"
subtitle: "Pivoting what the game is all about"
date: 2022-06-06T09:38:07+05:30
---

First, let me share one of the latest builds that I have.

<video width=100% controls autoplay>
    <source src="/posts/big_pivot/latest_build.mp4" type="video/mp4">
</video>

This is what I have been working on a lot. Trying to get the game into a place where
it feels like a real toy. Where the buttons will make clack-clack sounds. Something
about it feels very playful. And that's what has got me thinking.

I got into puzzle game development largely because of the [thinky-puzzle-games discord](https://discord.gg/jbQrge7pkk).
It's a great place, with a lot of fascinating and inspiring people doing exciting work.
Due to the nature of the discord, it attracts a lot of people who really enjoy 
difficult puzzles, and there is a sort of ethos built around that.

Subconsciously, I guess I started to think of that as my gold standard as well, and never
really questioned whether it is the right direction for the game that I am working on.
Now however, is the time to question all of that, and see what we can learn that might
benefit us.

A bit about puzzle game design philosophy.

## Portal

![Portal Poster](https://cdn.akamai.steamstatic.com/steam/apps/400/header.jpg?t=1608593358)

[Portal](https://store.steampowered.com/app/400/Portal/) is probably one of the most well-known
"thinky-puzzle" games out there. It represents one philosophy of puzzle game development.
It is built to be a very streamlined experience. The learning curve is pristine. It is playtested to perfection,
such that no single level will be so hard, that a player is compelled to put it down and quit.
This is something that the discord made me think about, and to some extent, it does make sense.

What that means for the game overall, is that it sometimes has to sacrifice interesting ideas if
those ideas might present a sharp roadbump for the player. A very interesting but difficult puzzle
will get cut in order to keep the learning curve as smooth as possible.
You will not find a [Great Tower](https://www.reddit.com/r/Stephenssausageroll/comments/692kzx/intimidated_by_the_great_tower/)
in Portal.

This approach means there is something gained, and something lost. You gain a large audience, and
you allow all of them to finish and enjoy the game. That certainly has a lot of value. 
<br>But you also lose something, and it's probably what makes Stephen Sausage Roll special.


## Stephen Sausage Roll

![Stephen Sausage Roll Poster](https://cdn.akamai.steamstatic.com/steam/apps/353540/header.jpg?t=1589230122)

[Stephen Sausage Roll](https://store.steampowered.com/app/353540/Stephens_Sausage_Roll/) is
in my opinion, one of the finest games ever made. The puzzles are really designed to highlight
every single interesting emergent phenomenon, and overall the levels can be brutally hard.
There is no real tutorial, and you just have to figure out how everything works. Even moving
around is fairly complex and takes some time getting used to. There is no real story, and the
world building is largely environmental and cryptic.

Finishing SSR is a truly fulfilling experience, and you really feel like you have mastered
the systems that were placed in front of you. There is also the ego boost that comes with having
accomplished something that is considered to be so difficult.

Originally that was my mental goal post. Make a game that emulates SSR in those respects. Focus
on emergence in puzzles, forgo narrative, embrace difficulty etc etc.

However, now when I think back to SSR, I realise that the thing that stuck with me most is
the final world. Those final set of levels feel like they ignore a lot of what came before.
Suddenly the game is more linear, and there is a bit more narrative. The levels are not easy, but
also not really that hard anymore. Knowing how brutal some of the early game is, the end game is
quite tame. Instead, the focus shifts to having novelty, excitement and joy as the crux of each level.
While the mechanics could have increased the difficulty, instead, they focus on something else.

Each level is built around _one_ overly complicated emergent mechanic. And it is built just to focus on
that. Sometimes this makes the level hard, sometimes not, but it feels like the focus is no
longer on the difficulty. Just the exploration, and playing with that mechanic. 

Thinking back, it feels
like all of the earlier levels and worlds just exist so that they can train you. So that when
you reach this stage, you are able to truly enjoy each level. You have drilled the
basics enough, and you can now enjoy the fruits of your labor with stunning novel ideas. You are
comfortable with the mechanics and can appreciate the magic in front of you.

---

## Applying those learnings

The main thing I had to figure out is what it is about SSR that we are chasing. I had initially naively
assumed that it was a sense of difficulty and satisfaction of conquering that challenge. But the more
that I think back, the primary emotion I associate with completing the game is not pride. It's something
closer to joy and delight.

It seems to me that the difficulty in SSR is incidental. It is required so that you can understand
and enjoy the levels that were really designed to be enjoyed. The game aims to spark joy, and had to
travel a path of difficulty to get there.

The design of KCPS ([__this__](/) game...)
makes it really easy to make difficult levels. Just add a bunch of specifically forced interactions,
maybe confine the space to prevent trivial solutions, and _Lo!_.

It is fairly simple to make interesting levels as well. The system has so many interactions, and so many
emergent phenomena that if you can't design a level around one, you have a pick of hundreds of others to
choose from. Just a couple of pieces on the board, fairly small solution space, and _Behold!_.

The difficult thing to make; __interesting levels that are difficult.__

It's just how the system is. Most other puzzle type games allow the player to make inputs
throughout the level. So it is possible to string together multiple different _sections_ in the same puzzle,
and you won't know if you've solved the first one correctly until you solve all the _sections_.

An example of this would be that you have to get to a certain part of the map. Once you get there, you realise
that you have to carry a box with you, and so on. This allows for levels to seem simple at the offset,
but become a little more difficult because of the interactions between sections.

In KCPS, on the other hand, you set up all the commands on the board at the beginning, and then you let it rip.
You can't make any changes partway through the simulation. If you need to make a change, you start over,
and change the positions of the commands.

So the same approach of multiple sections does not
work out, as adding additional commands tends to make the puzzle noisy and allows for
trivial level breaks.

## The New Direction

I think I was trying to build a game that I envisioned, instead of allowing the game to build itself.
The system that the game explores has the luxury of _not_ requiring the same level of difficulty just
to showcase the most interesting parts. That is something that I am now leaning into.

The levels are now a lot easier. The harder levels are much more optional. There is still value in those
levels, but the basics of the game can be enjoyed without needing to master, or even be aware of them.

Somehow, without meaning to, I think I have found a sweet spot in between Portal and SSR. Most of it is
because of having a lot of optional levels. But that's just how the game is. 

While the most interesting parts definitely have that combinatorial explosion that all the 
mechanics can provide together, the mechanics introduced later on in the game have some beautiful
emergent properties on their own, and I would love for players to have a chance to explore them.

## In Conclusion

I finally understood what the game was telling me all along. It is meant to be a simple experience,
with mostly simple levels, and just the occasional mind-melter thrown in there for good measure. I
no longer have to fight against the game to generate levels. They just waltz by, and I have to pay
attention and ask for their permission to catch them. This all makes the work much more enjoyable
and will hopefully result in a much more sincere product.
