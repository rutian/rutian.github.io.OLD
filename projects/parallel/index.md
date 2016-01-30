---
name: Digifab
layout: default
date: 2015-12-10

---


##Intro

Hello, my name is Rundong (Kevin) Tian. I'm a second year PhD student in computer science working with Eric Paulos. I'm interested in geometry/fabrication/interactive device design. Some of my projects can be found [here]({{site.url}}/projects).

Some applications of parallel computing I'm interested in are around simulation and form finding for mechanical designs.

From this class, I'd like to familiarize myself with the tools and techniques used in parallel computing.

---

##Autodesk Dreamcatcher

This is a computer aided design software that allows users to create physical geometries using high level design constraints (loading forces, load locations, final weight, material, manufacturing method, etc) rather than explicit declarations of the geometry (extrude, fillet, revolve, draw, etc).

For example, rather than design a bicycle by specifying the geometry and length/shape of the tubes, a bicycle frame can be "designed" by specifying the forces it must support and the other components it interfaces with.

![bicycle](https://autodeskresearch.com/img/dreamcatcher/bike-gif.gif)

_Successes:_ Rapid creation of geometries. High level exploration of the design space. 

_Weaknesses:_ Will the generated designs be valid (aesthetic qualities, manufacturability)? 

_Challenges:_ How can users still be involved in the design of these forms? How can human expertise be best combined with a design tool that can on its own generate many valid geometries.

---

## Details

Dreamcatcher is driven by Project Saturn, a computing framework for solving optimization functions (also developed by Autodesk). 

Project Saturns claims to be scalable from an individual computer to a "cloud", but not many technical details are described.

This is an interesting way of of thinking about the design of mechanical objects, where the designed constraints are directly specified to the software, and the software is responsible for finding the form that satisfy those constraints.

The body of a bow made using this design software:

![bow](http://autodeskresearch.typepad.com/.a/6a01630463a631970d01bb08918f61970d-pi)
source: [bow](http://autodeskresearch.typepad.com/blog/dreamcatcher/)

__Links:__
[Dreamcatcher](https://autodeskresearch.com/projects/dreamcatcher), 
[Saturn](https://autodeskresearch.com/projects/saturn)


