---
title: '300-Levels, Part 1: Foundational Courses'
layout: home
nav_order: 40
---
# 300-Levels, Part 1: Foundational Core Courses
These are the 300-level courses that are required for everyone in computer science. They cover extremely foundational material, important for many of the 400-level courses. Almost everything you study in the 400-levels will demand a strong foundation in the 300-levels, so it's important to make sure you really get the basics down well. 

The courses are largely very disjoint from each other and each is very unique, so they often pair well together to construct quarterly schedules where you have a nice variety of different kinds of courses (more on why I think this is a good idea on the section about [Building Schedules](/150%20-%20building%20schedules.md)).

I consider them separate from the non-mandatory 300-level courses, which I consider [Intermediate Courses](45%20-%20intermediate.html) owing to the fact that most of the non-mandatory 300-level courses actually have at least one of the foundational courses on this page as a pre-requisite. Those intermediate courses can therefore serve more as the middle ground to ease into some of the 400-levels.


## CSE 311 - Foundations of Computing I
The name is not particularly descriptive of the material covered in the course. In some regard, this class should really be considered a "Fundamentals of Theoretical Computer Science" course, owing to the fact that the course is entirely theoretical, focusing on such topics as [logic](https://en.wikipedia.org/wiki/Logic), [formal proofs](https://en.wikipedia.org/wiki/Mathematical_proof), a rigorous look at mathematical constructs (such as very basic [number theory](https://en.wikipedia.org/wiki/Number_theory), [set theory](https://en.wikipedia.org/wiki/Set_theory), and [graph theory](https://en.wikipedia.org/wiki/Graph_theory)), models of computation such as [automata](https://en.wikipedia.org/wiki/Automata_theory) and their corresponding [formal languages](https://en.wikipedia.org/wiki/Formal_language), before wrapping up with some of the most important results in computer science, such as the [continuum hypothesis](https://en.wikipedia.org/wiki/Continuum_hypothesis) and the [halting problem](https://en.wikipedia.org/wiki/Halting_problem).

This course, being primarily focused on theory, can often feel disconnected from the rest of computers. After all, how can this class that feels more like math than computing have anything to do with computers?

The truth of the matter is that, as the name suggests, it's really only here to set up a foundation. All of the things you learn here will come in handy later, even in programming classes! Here, even though you're only learning "theory", you will get a good appreciation that will help you answer such questions as:

- What is a computer, anyways?
- Are there problems computers can't solve?
- Are there tools that can help us in writing and reasoning about complicated conditional statements?

All of which are practical even if you want nothing to do with theoretical computer science ever again.

The class can be quite difficult if you've never had exposure to more abstract mathematics. For most people entering this class, their prior experience with math has primarily been regarding calculation such as solving equations. This class will expose you to a very different kind of math - specifically reasoning about abstract objects (and indeed, you'll find out that a "computer" is actually just one of those abstract kinds of objects). This course frequently feels foreign to many people, for these reasons. If you have prior exposure to most of these topics, however, the course might even feel very slow (it is not unheard of for students to come in knowing virtually all of the course content, and then more as well).

Overall, I very much enjoyed the course. I came in with enough experience to not feel always lost, but not enough to know everything, and so the course frequently had its mind-blowing "a-ha" moments when a clever result was presented or a cool proof idea was highlighted.


## CSE 312 - Foundations of Computing II
Like its predecessor, the name is not particularly descriptive of the material covered in the course. This class is probably best described as a "Probability for Computer Science" course. The course builds up probability from first principles ([counting and enumeration](https://en.wikipedia.org/wiki/Counting)) all the way to various [probability distributions](https://en.wikipedia.org/wiki/Probability_distribution). About one-third of the class is focused on applications of probability and randomness in computing, which can vary based on the quarter but will almost always include some or all of the following topics:

- Applications to artificial intelligence (with methods such as [Bayesian inference](https://en.wikipedia.org/wiki/Bayesian_inference)) and machine learning (with methods such as [MLE](https://en.wikipedia.org/wiki/Maximum_likelihood_estimation))
- Powerful probabilistic data structures, such as the [Bloom filter](https://en.wikipedia.org/wiki/Bloom_filter)
- Inequalities and bounds useful in the analysis of algorithms, such as [Chernoff bounds](https://en.wikipedia.org/wiki/Chernoff_bound)
- Randomized algorithms, such as those falling under the [Monte Carlo algorithmic paradigm](https://en.wikipedia.org/wiki/Monte_Carlo_algorithm)
- Distributions such as the [Poisson distribution](https://en.wikipedia.org/wiki/Poisson_distribution) that are very useful in performance engineering of large-scale software systems, particularly via [queueing theory](https://en.wikipedia.org/wiki/Queueing_theory).

The practicality of which should be self-evident.

Following in the footsteps of CSE 311, this class is basically entirely theoretical in nature, but unlike CSE 311, it actually has a very minimal amount of programming (dependent on instructor), primarily geared towards the applications side of things. You get to implement some cool algorithms!

It's essentially just a math course that happens to teach probability with a specific computer-scientific perspective rather than a pure math one. If you are mathematically inclined, you will find the class fairly simple to navigate. The results generally feel no more dense than the ones from CSE 311, but can be very unintuitive at times (probability is indeed not so intuitive, in my opinion). My experience is that the difficulty of the course is fairly comparable to CSE 311, though a small amount of other people I know found it much easier, and a still smaller amount of others found it much harder. The best conclusion I can draw, therefore, is that it probably depends on your prior experience with this particular kind of math.

This was a course I definitely enjoyed. I found the applications very convincing and the theory very interesting. Even though I did not necessarily internalize all the ideas when I was taking the course, over time I've come to develop a deep appreciation for the material and have found it coming up over and over again. It certainly deserves to be considered a "foundations" course.


## CSE 331 - Software Design and Implementation



## CSE 332 - Data Structures and Parallelism



## CSE 351 - The Hardware-Software Interface


