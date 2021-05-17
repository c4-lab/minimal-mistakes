---

title: Modeling Socio-technical Systems
layout: single
header:
  image: /assets/images/murmuration.jpg
  caption: "Photo credit: [Tom Lee](https://www.flickr.com/photos/68942208@N02/) / Flickr Creative Commons"
permalink: /social-simulation/
author_profile: true
---
One of the most beautiful and evocative presentations of emergent social behavior can be found in the flocking behavior of birds. In some species, hundreds or thousands of birds can come together to create huge swirling clouds called [mumurations](https://en.wikipedia.org/wiki/Swarm_behaviour). These mumurations can seem to take on a life of their own, moving with something like intentionality.

Of course the flock is not an intentional being, and the behavior of a murmuration can be reasonably approximated when individuals follow three basic rules:

* Move in the same direction as their neighbours
* Remain close to their neighbours
* Avoid collisions with their neighbours

This model was demonstrated in the original [boids](https://en.wikipedia.org/wiki/Boids) computer program by Craig Reynolds [1], and the code running on the lab's [home page](/) was adapted from a version written by [Noah Vetman](https://bl.ocks.org/veltman/995d3a677418100ac43877f3ed1cc728). In our version, we've divided the population of boids into two distinct groups and added a few parameters inspired by human social systems. *Homophily* governs how much individuals seek their own kind, *heterophily* governs how much individuals seek out those of other kinds, and *individualism* governs how much individuals go their own way. You can manipulate these parameters by clicking the "show controls" link in the lower left of simulation.

The simulation captures the spirit of research in the C4 lab. We develop and explore simple models to identify critical factors that influence the collective behavior of human socio-technical systems. We pursue this research in order to become better informed about how to design technology that benefits society.

We also do it because it's lots of fun!

-----------

[1] Reynolds, C.W. 1987. Flocks, herds and schools: A distributed behavioral model. ACM SIGGRAPH Computer Graphics. 21, 4 (Aug. 1987), 25–34. DOI:[https://doi.org/10.1145/37402.37406](https://doi.org/10.1145/37402.37406).
