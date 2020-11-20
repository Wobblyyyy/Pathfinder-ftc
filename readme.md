![Pathfinder Logo](https://raw.githubusercontent.com/Wobblyyyy/Pathfinder/master/logo.png)
Odometry-dependent library for robotics-based competitions and challenges.
Click right [here](https://wobblyyyy.github.io/Pathfinder/) to get to the online documentation!
Or, go right to the JavaDocs with the following links.
1. [Pathfinder JavaDoc](http://wobblyyyy.github.io/Pathfinder/javaDocs/pathfinder/index.html)
2. [OdometryCore JavaDoc](http://wobblyyyy.github.io/Pathfinder/javaDocs/odometryCore/index.html)
3. [ftc2 JavaDoc](http://wobblyyyy.github.io/Pathfinder/javaDocs/ftc2/index.html) (not complete!)

## Features 
- Virtualized simple Euclidean geometry in combination with a field-mapping system to allow programmers to
quickly and easily set up a pathfinding system that automatically avoids collisions.
- Lightweight code specifically and originally designed for use within the First Tech Challenge.
- Near plug-and-play usability - add the library, get familiar with the library's APIs (maybe check out the
quick-start guide) and get to pathfinding.
- Open-source and easily configurable.
- Fully documented and well-documented code, designed specifically to make implementation a breeze.

# Getting Started
It would be a great idea for you to check out the JavaDocs, and the tutorials (both text and video) included
here. If you don't do both of those, I'm probably not going to be all that willing to provide you with tons
of help.

## Requirements
This library is based around odometric positional tracking math, all of which has been originally developed
by Tejas Mehta. As a result, his OdometryCore library is required for this library to... well, function
properly, or even at all. Additionally, Gradle is required - I know it's crazy to think that a Gradle library
requires Gradle to work, but I'm sure you've seen crazier things.

## Warnings
As with any newly-created piece of code, this library is in a very early alpha stage. I can't guarantee that
the pathfinding system will always find the quickest possible path. I can't guarantee that it'll work 100% of
the time. If you notice major issues with the code, it would be a great idea to report those on this repo -
maybe check out the issue tracking system GitHub was so kind as to provide to all of us?
