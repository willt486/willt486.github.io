---
layout: post
title: Development of cards for "Persuasion"
categories: [persuasion,games]
comments: true
---

Having tried the basic game out a few times now the next move seemed to be to develop some new cards. There were two main reasons for wanting to do this. Firstly, existing cards look somewhat "rough" - or to be less polite, they were amateurish. Secondly, the existing cards are not really robust enough to permit lots of playtesting; this is going to be critical in developing the game further.

The geeky side of my personality means I spent quite a bit of time looking for a tool to help with the process. In the end, I settled for "Squib" a tool which runs on Ruby that offers the benefit of separating out content and design.

Content is handled using a csv file - I chose to write this using a text editor but I guess a spreadsheet programme would work equally well. Design of the cards uses Ruby - which is why I was able to spend a happy Saturday morning playing about with learning something new. The result was a very workable second version of the cards that will enable further playtesting and looks slightly better. Having set up the cards, I am able to revise and amend them easily using the csv file for the content or the Ruby files for design elements.

The aim is to revise the game so that it is in a state whereby I am sufficiently confident that the game is useful in classes and other sessions, offering learning opportunities from year 12 through to undergraduate levels. In time, it might be possible to create resources to support earlier age groups using the game.

Here's a preview of how the v2 cards look:

[![Showcase of v2 cards](/img/showcase.png){:width="50%"}](/img/showcase.png)
