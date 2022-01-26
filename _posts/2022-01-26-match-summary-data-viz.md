---
layout: post
title: "Adding context to match summary statistics"
date: 2022-01-26
---

A popular use of football statistics online is presenting a player's match totals for various metrics present in a list. 

E.g. Jamie Vardy vs Liverpool: 3 shots, 5 dribbles, 8 tackles etc

When I see this sort of thing, I can't help thinking "so what?" Five dribbles sounds like a lot, but is it? What does that player normally do? How does that compare to his teammates and the rest of the league? In other words, more context is needed. The below piece of data viz is an effort to give context to these lists of statistics. 

The aim is to give a good amount of context without overloading the screen with numbers. 

<div style="text-align: center"><img src="https://raw.githubusercontent.com/georgeball95/georgeball95.github.io/main/assets/match_summary_Patson%20Daka_2022-01-23.png" width="600" height="900" align="center">

Some thoughts on the data viz design process:

* <b>Splitting the distribution of each statistic into quintiles</b> - the idea behind this is, at a glance, you only really need to know if it was very low, low, average, high or very high - anything more is overkill. This is the main idea behind the graphic, giving the much needed context.

* <b>Adjusting the brightness to show the match value</b> - easy to spot at a glance - straight out of the pre attentive attributes playbook! 

* <b>Marking the player's season average with a border</b> - this doesn't immediately stand out but once you have looked at the graphic for a second or two you'll notice it - it's not the main part of the graphic but it's not supposed to be - it adds value and doesn't overwhelm the viewer. 

* <b>The legend</b> - it takes up quite a lot of space on the graphic but I think this is space well used. I adjusted the brightness down on this slightly and added the dotted line separator to make it immediately obvious it's not part of the main graphic.

* <b>Gold star</b> - I think it's cool to have an addition to the graphic to demonstrate the extreme end of the distribution, otherwise the 80th and 99th percentiles show up the same! This graphic is a bit like a scorecard/report card, so a gold star is a nod to that!

Just to note, clearly counts of metrics are not a tool for serious analysis, but I see lists of stats posted often enough so why not try and improve on them.


