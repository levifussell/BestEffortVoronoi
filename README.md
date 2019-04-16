# Best Effort Voronoi #

A dynamic Voronoi diagram generator for David Ackley's [Movable Feast Machine](https://github.com/DaveAckley/MFM). Data points can be added and removed, and the Voronoi diagram will self-regulate. A tutorial on how the algorithm works and how the code is written can be found [here](http://www.howthefrondsfold.com/T2Voronnoi/).

## Download ##

Clone the repository to a directory on your computer:

```$ git clone https://github.com/levifussell/BestEffortVoronoi```

Download the Movable Feast Machine simulator [here](https://github.com/DaveAckley/MFM) and the ULAM language compiler [here](https://github.com/DaveAckley/ULAM). Further details in my [tutorial](http://www.howthefrondsfold.com/T2Voronnoi/).

## Run ##

Compile the source code:

```$ ULAM/bin/ulam -l Propagator.ulam Propagate.ulam Source.ulam```

Run the source compiled .dll file:

```$ MFM/bin/mfms -ep .gen/bin/libcue.so```

## Results ##

Video of results.

[![Watch the video](https://img.youtube.com/vi/GVNMdOOBeGo/maxresdefault.jpg)](https://youtu.be/GVNMdOOBeGo)

## Visualisation of Algorithm ##
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/GVNMdOOBeGo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

A single source propagates like water.

![Alt text](imgs/Source1.png?raw=true "Title")

Two sources compete via water pressure variables.

![Alt text](imgs/Source2_asynch.png?raw=true "Title")

A removed source will be consumed by its neighbouring source(s).

![Alt text](imgs/Source3_removal_correct.png?raw=true "Title")





