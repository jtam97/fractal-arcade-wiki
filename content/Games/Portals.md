---
title: Portals - The Past and the Present
---

Portal - a critically acclaimed puzzle game from Valve in 2007 and a must-play for any puzzle game fan.

## Gameplay

Portal is a first-person puzzle game where the player must navigate through a series of rooms using a portal gun. The core of the gameplay is the portals - with the portal gun, you can shoot two portals, an orange and a blue one which "link" to each other. When you walk through one portal, you come out of the other.

The mindbending part of these puzzles is two-fold:

1. The ability to look through the portals and see what's on the other side. As seen below, you can see this in action. What's really interesting though is that you can see through the portals recursively.

![[static/assets/portal-look-recursive.jpg]]

2. The portals conserve momentum. If you throw a ball through one portal, it comes out the other side with the same speed it entered. This leads to some mindboggling mechanics, like the infamous "infinite loop":

![Infinite Fall](https://www.youtube.com/watch?v=rVJHQ7SkgwI)

Again, this is another example of a recursive look through the portal.


## Algorithm

So how do you render something like this graphically?

