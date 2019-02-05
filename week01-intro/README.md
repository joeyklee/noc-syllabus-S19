# Introduction

Notes: 
- This course is about the concepts of simulation natural systems implemented in code.
- This course is inspired by James Tu's course in 2003. See acknowledgements in Nature of Code Book. At 2003, it was run in macromedia director. James's course focused more on physics simulation.
- We want to in this course add "intellligence", emotional resonance of hte real world in our software.
- ref: Philip Galanter - Generative Art Systems
- the goals:
  - have more time to practice programming
  - put into your toolset, physics simulation and broadly AI concepts can be put into graphics
- this class was first run in 2008!

The class in 3 parts:
- Physics Engine/similation:
  - vectors ==> `createVector()`
    - in 2D space --> the difference betwnee 2 points in space that can be presented by an arrow between those two points.
    - velocity is a vector! ==> 
    - acceleration is a vector!
    - A path is a vector! ==> 
    - A SVG ==> scalable vector graphic! 
  - forces, and newton's law ==> `F = M * A`
    - gravity, repulsion, attraction
  - trigonometry, relation betwen angles and sides ==> `sin()` `cos()`, `tan()` etc.
- Complexity or complex systems:
  - "more than the sum of it's parts" - e.g.: an ant colony: individual ants have simple behaviors, but together as a whole, they can do big things
- Intelligence:
  - genetic algorithms
  - neuroevolution, neural network

Exmaple project: showing all the concepts learned in this course 
- filiplazovic.github.io/aijs2
- the partices have learned how to avoid the circles through evolution

Goal of class:
- try to post something each week

Books:
- Emergence: https://www.amazon.com/Emergence-Connected-Brains-Cities-Software/dp/0684868768
- Computational Beauty of Natre: https://www.amazon.com/Computational-Beauty-Nature-Explorations-Adaptation/dp/0262561271
- mathematics and physics for programmers: https://www.amazon.com/Mathematics-Physics-Programmers-Programming-Kodicek/dp/1584503300


Part 2 of session:
- Conditional Design, Conditional design manifesto, sol lewitt
- Interesting projects:  https://github.com/nature-of-code/noc-syllabus-S19/wiki/Related-and-Past-Projects
  - everest pipkin ==> everest-pipkin.com // https://twitter.com/mothgenerator?lang=en
    - moth generator, fictional moths, fixtional designs
    - > think about procedural design 
  - Robert hodgin: http://roberthodgin.com/
    - magnetosphere: https://vimeo.com/135858
  - Mark Stock: http://markjstock.com/
  - Mudtub: Tom gerhardt
    -  http://tomgerhardt.com/
 -  Zurkow and Shiffman:
    -  https://vimeo.com/37383446
-  Matterjs
   -  http://brm.io/matter-js/
   -  nice for quick physis needs!
   -  > in this course we will want ot build our own physics engines
- Workflows
- Randomness, probability, and random walk




## Class Intro / Overview
* [Related and Past Projects](https://github.com/nature-of-code/noc-syllabus-S19/wiki/Related-and-Past-Projects)

## Development Environments
* [Processing](http://www.processing.org)
* [p5.js](http://p5js.org)
   * [web editor](https://editor.p5js.org/)
   * [open processing](https://www.openprocessing.org/)
   * [codepen](https://codepen.io/)
* [Node + VSCode workflow videos](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zu_uqEA6NqhLzKLACwU74X)
* [Other Nature of Code Ports](https://github.com/nature-of-code/noc-examples-processing/blob/master/README.md)

## Week 1 Tutorials and Resources

It's probably not realistic for you to consume everything that is below. Pick and choose what is most helpful and useful to you. Feel free to send me feedback as what doesn't work well or you feel is missing!

* [Video: Publishing p5.js sketch with github pages](https://www.youtube.com/watch?v=8HPYsDTk17A) -- note that `gh-pages` is no longer required, you can host a github repository using the default master branch now.
* [Video + code: Walker p5.js](https://thecodingtrain.com/CodingChallenges/052-random-walk.html)
* [Video + code: Random Walker with Vectors p5.js: Levy Flight](https://thecodingtrain.com/CodingChallenges/053-random-walk-levy.html)
* [Perlin Noise Videos -- mostly p5.js](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bgPNQAdxQZpJuJCjeOr7VD)
* [Perlin Noise tutorial in p5.js](http://genekogan.com/code/p5js-perlin-noise/) by Gene Kogan
* [Nature of Code Introduction text: Processing](http://natureofcode.com/book/introduction/)
* [Nature of Code Introduction videos: Processing](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YVljJvFRCyRM6mmF5wMPeE)
* [Processing code examples](https://github.com/nature-of-code/The-Nature-of-Code-Examples/tree/master/introduction)
* [p5.js code examples](https://github.com/nature-of-code/The-Nature-of-Code-Examples-p5.js/tree/master/chp00_introduction)

## Supplemental Reading
* [Mathematics and Physics for Programmers](http://amzn.to/2Fhooq7) Chapter 5
* [Computational Beauty of Nature](http://amzn.to/2Gk3WpQ), Introduction
* [Probability Theory](http://www.probabilitytheory.info/)

## Assignment
* Accept invite to class mailing list (let me know if you prefer a different e-mail address.)
* [Assignment](https://github.com/nature-of-code/noc-syllabus-S19/wiki/Assignment-1).

## Web Editor Example Links

### Introduction
* [I.1: Traditional random walk](http://editor.p5js.org/natureofcode/sketches/Hk4LOoSvx)
* [I.2: Random number distribution](http://editor.p5js.org/natureofcode/sketches/BJHTAHUwe)
* [I.3: Walker that tends to move to the right](http://editor.p5js.org/natureofcode/sketches/SkPQJIUwx)
* [I.4: Gaussian distribution](http://editor.p5js.org/natureofcode/sketches/S120y8Uwx)
* [I.5: Perlin noise walker](http://editor.p5js.org/natureofcode/sketches/SkuNg88Dx)

## Week 2

To get a jump on next week, start to look at the material about vectors. I'll go over some of this in class as well as introduce concepts from Chapter 2: forces.

### Object Oriented Programming Review & Vectors
* [Kadenze videos: p5.js](https://www.kadenze.com/courses/the-nature-of-code/info) -- Sessions 1 and 2
* [Nature of Code Chapter 1 text: Processing](http://natureofcode.com/book/chapter-1-vectors/)
* [Nature of Code Chapter 1 videos: Processing](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZwSmtE13iJBcoI-r4y7iEc)
* [Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp1_vectors)
* [p5.js examples](https://github.com/shiffman/The-Nature-of-Code-Examples-p5.js/tree/master/chp01_vectors)
