---
layout: post
title: "Visual Odometry - The Reading List"
modified: 2014-07-29 11:08:43 +0530
category: vision
tags: robotics, vision
summary: "Some resources for getting started with Visual Odometry"
image:
  feature: 
  credit: 
  creditlink: 
comments: true
share: 
---

I am thinking of taking up a project on 'Visual Odometry' as UGP-1 (Undergraduate Project) here in my fifth semester at IIT-Kanpur.
This post is primarily a list of some useful links which will get one acquainted with the basics of Visual Odometry.


The first thing that anyone should read is this wonderful two-part review by Davide Scaramuzza and Friedrich Fraundorfer:

* [Visual Odometry Tutorial Part 1](http://www.roboticsschool.ethz.ch/airobots/programme/presentations/VO_part_I.pdf)
* [Visual Odometry Tutorial Part 2](http://rpg.ifi.uzh.ch/docs/VO_Part_II_Scaramuzza.pdf)


One thing that I did not understand from the above tutorials was the '5-point algorithm' by Nister in 2003. The original paper is [here](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=1288525). But, this paper also seemed quite complicated for me to implement without any background, so I moved onto a simpler algorithm, called the '8-point algorithm', which was published a long time ago by Longuet-Higgins. You can find it [here](http://www2.ece.ohio-state.edu/~aleix/Longuet-Higgins.pdf). There are some lecture slides which explain this in a simple manner, and you can find them [here](http://www.cse.psu.edu/~rcollins/CSE486/lecture20_6pp.pdf).


Note, there are more papers that one should read regarding this, most notably:

* [In Defense of the 8-point Algorithmm](http://www.cse.unr.edu/~bebis/CS485/Handouts/hartley.pdf)
* [5-point Motion Estimation Made Easy](http://users.cecs.anu.edu.au/~hongdong/new5pt_cameraREady_ver_1.pdf)

In my next post, I will hopefully start working on my implementation.