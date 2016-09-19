---
layout: post
title: Week of Sept. 19th
---

## What did you do this past week?

This past week in class We dug even deeper into the intricacies of the python language, learning more about types, and objects and the general object structure of the language. On top of this we also began to learn more about all of the different objects in python and how they interact with each other. Outside of class My partner and I began working on the second project, Netflix. I spent a couple hours this week just reading up on the netflix problem, and how suggesting ratings actually works. It is an extremely complex process, and a very interesting problem to tackle.

## What’s in your way?

What seems to be in my way this week would have to be a true understanding of the Netflix problem, and writing unit tests. My partner and I finished writing the algorithm for the Netflix problem, however, it uses some caches of some of my classmates, and it feels a bit strange to have finished using other people’s data caches. I am fairly sure I understand how they are working, but as they are not mine, and do not have good explanation’s I am not sure I am truly understanding the problem. As far as unit tests go, they are making development very strange for me. I am not used to writing testable code, and its making me think in a very different way

## What will you do next week?

Next week I will finish up the Second project. My partner and I have to finish up the unit tests and the acceptance tests, as well as making sure that the code will work with TravisCI. As of right now the code does all of it's file calls are local, calling the local machine. However, TravisCI will not work with those types of calls so we need to make a HTTP calls in our code to fix this problem. After that we simply need to gather all of the necessary files and we will have completed the second project.

## Personal Reactions to class

This week of class was pretty interesting. The Netflix problem is an extremely interesting one. However, I feel like this project did not give as in depth of a dive into it as I would have liked. I started reading up on the math behind the actual solution and quickly realized that it was a bit out of my realm, then I began to read farther and realized that an acceptable answer could be reached just by using a couple of quick tricks related to the average user rating. To be honest I feel like getting the RMSE to less than 1 was quite easy and I feel like 0.95 would have been a bit trickier. I also think this project would have been more appropriate without all of the unit tests. This project does not need all of that because the input is technically the same every time.

## Tip Of The Week

My tip of the week would be to really try and get to know the language that you are using. This week we had to get the execution time of our program below a minute, which at first our execution time was one and a half minutes. At first we could not figure it out, but then we realized that file opening and closing in python was a slow operation and so we tried to make our program do that as little as possible to alleviate a lot of the execution time and we cut nearly 80 seconds from our execution.
