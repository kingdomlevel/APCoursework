# AP Coursework 2017
### University Project
Coursework submission for the class *Advanced Programming*, undertaken as part of my masters degree *MSc Software Developmet* from [University of Glasgow](http://www.gla.ac.uk/postgraduate/taught/softwaredevelopment/) in Feb 2017.

The task was to design and implement a 2 dimensional [cellular automata](https://en.wikipedia.org/wiki/Cellular_automaton) system in the form of a 'grid world' populated by two species of 'creature'.

![Program screenshot](https://68.media.tumblr.com/519e8d9baf46593508d29e9378ff596c/tumblr_owhcvrPubq1uoduy3o3_540.png)

---

### Specification
The assignment had the following requirements:
* Must be implemented in Java;
* Must run from command line;
* Each species has its own maximum lifespan and fitness score;
* Each creature must run on its own thread;
* At the end of a creature's life, it must re-produce then die according to various rules
* The system must handle two *edge cases*:
    * Edges of grid are edges of the world;
    * World 'wraps around' grid.

---

### Implementation
I implemented the program using emojis (in a battle-of-the-sea kinda theme) and very basic user interaction. I got an ⭐️**A1**⭐️ for this project.

Run this program by compiling all the classes and then running the `TestWorld` class:

```
javac *.java
java TestWorld
```
When it launches, you'll be prompted to choose the edge case:

![User prompt at program launch](https://68.media.tumblr.com/14b34b68b1a2c651208eea9fb01e9629/tumblr_owhcvrPubq1uoduy3o2_1280.png)

---

##### Program design:
![AP UML](https://68.media.tumblr.com/a6fe70f5cf1512454be7a05d4a22b703/tumblr_owhcvrPubq1uoduy3o1_1280.png)
