# ResistAR
Project for TartanHacks at CMU

##Prize Categories
###Won
Grand Prize
Facebook Company Prize
###Attempted
Duolingo’s Social Impact Prize (Educational) and
GoDaddy’s Social Impact Prize (“Best app that improves STEM education”)

## Inspiration
Long hours spent on ECE problem sets and frustration visualizing convoluted circuits caused these four CMU undergrads to create a circuit visualization system that would also help them solve circuits.
A member of the team is currently in the intro ECE course: "Well it's not _bad_, I guess." - Team Member

## What it does
ResistAR is an Augmented Reality Circuit Visualizer and Solver. A user can place down circuit elements in parallel and series configurations and ResistAR will solve the current through and voltage across each element of the circuit. It gives the user an easy way to _see_ (sharp) the circuit.

## How we built it
We first began with 3D printed chassis for the [VuMark] (https://library.vuforia.com/articles/Training/VuMark) targets. These targets are identified and parsed by the program and cross checked against our cloud database on [Vuforia] (https://www.vuforia.com/). 
We then created 3D, textured, models in [Blender] (https://www.blender.org/) that will hover over the VuMark targets.
We then wrote the code in [Unity] (unity3d.com) that will calculate voltage and current values using concepts from vector calculus and matrix algebra.

## Challenges we ran into
The math was very difficult and attempting to rush a 3D printed design was also difficult but there was a rush because 3D printing would be a very time consuming process. 
Thus we also had to create a lot of our latter designs around the already 3D printed parts.
VuMarks were also difficult to create. VuMarks must be very easily distinguishable from each other and non-symmetric along any axis, and therefore took a while to get finely tuned and calibrated.
Finally the math was a very difficult thing to visualize. We had to go from 3D space to 2D space and there were some difficulties with projections. The coders did end up writing relatively bug-free code, but not before a long, arduous thinking process.

## Accomplishments that we're proud of
The two logic/algorithm gods that we had on our team solved an extremely complex math problem very quickly. 
Also our 3D printed parts are actually fire though. Just saying.

## What we learned
Two 5 hour energies in 72 hours is actually not as bad an idea as some might think.
Math is hard.

## What's next for ResistAR
Norton and Thevenin Equivalents. Yikes.
