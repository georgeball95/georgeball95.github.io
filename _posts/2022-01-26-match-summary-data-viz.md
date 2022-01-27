---
layout: post
title: "Adding context to match summary statistics"
date: 2022-01-26
tags: ["data viz"]
---

A popular use of football statistics online is presenting a player's match totals for various metrics present in a list. E.g. Jamie Vardy vs Liverpool: 3 shots, 5 dribbles, 8 tackles etc

When I see this sort of thing, I can't help thinking "so what?" Is five dribbles a lot? What does that player normally do? How does that compare to his teammates and the rest of the league? In other words, more context is needed. The below piece of data viz is an effort to give context to these lists of statistics. 

<img src="https://raw.githubusercontent.com/georgeball95/georgeball95.github.io/main/assets/match_summary_Patson%20Daka_2022-01-23.png" width="600" height="900" align="center">

Some thoughts on the data viz design process:

* <b>Splitting the distribution of each statistic into quintiles</b> - at a glance, you only really need to know if a statistic is very low, low, average, high or very high (compared to players in the same position) - anything more is overkill. 

* <b>Adjusting the brightness to show the match value</b> - this makes it easy to spot the match value at a glance - straight out of the pre attentive attributes playbook! 

* <b>Marking the player's season average with a border</b> - this doesn't immediately stand out but once you have looked at the graphic for a second or two you'll notice it - it's not the main part of the graphic but it's not supposed to be - it adds more context and doesn't overwhelm/distract the viewer. 

* <b>The legend</b> - it takes up quite a lot of space on the graphic but I think this is space well used. The brightness is adjusted down on this slightly (grey not black text) and added the dotted line separator to make it immediately obvious it's not part of the main graphic. Having this reference point (with annotations) gives all the information the viewer needs to interpret the graphic. 

* <b>Gold star</b> - I think it's cool to have an addition to the graphic to demonstrate the extreme end of the distribution, otherwise the 80th and 99th percentiles show up the same! This graphic is a bit like a scorecard/report card, so a gold star is a nod to that!

Just to note, clearly counts of metrics are not a tool for serious analysis, but I see lists of stats posted often enough so why not try and improve on them. Not a game changer in the football analysis space but I might put a few more out as and when Leicester City players have good games!




