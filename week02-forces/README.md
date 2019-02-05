# Vector and Forces

It's probably not realistic for you to consume everything that is below. Pick and choose what is most helpful and useful to you. Feel free to send me feedback as what doesn't work well or you feel is missing!

## Notes

- Adding forces!
- magic book plug ==> https://github.com/magicbookproject/magicbook
- programming design systems, rune madsen: https://programmingdesignsystems.com/
    + Rune will be in March 8th, Friday ==> talk
    + designsystems.international
- workflow:
    + quick look at git and github workflow ==> `git config` etc etc
    + how to configure VS Code
    + live-server: https://www.npmjs.com/package/live-server // for autoreload
    + p5-manager: https://github.com/chiunhau/p5-manager
- Quick code review:
    + `floor()`
    + `ceil()`
    + `round()`
- Assignment Reviews:
    + Billy noise example
    + Rui ==> random walk in 3D
    + see Ayal's plate break
- Perlin Noise and random:
    + set seed 
    + these are deterministic
    + gene kogan post: http://genekogan.com/code/p5js-perlin-noise/
    + e.g. perlin noise chaser ==> by offsetting the starting x and y of the noise() you can get an effect of chasing a feature.
    + perlin noise wood example
    + see perlin2D
    + see vector flow fields
        * the "arrows" tell a particle where to go
    + morgan, architect, mississippi river 
    + `noiseSeed()` sets the type of noise generation you get.
    + leaves-random-walk.herokuapp.com
        * using t-SNE to sort by similarity and using perlin noise in 2d space to select the image
- Random walks + higher dimensional spaces ==> what are productive or creative uses of random walks to move through latent space or hyperdimensional spaces often used in ML.
    + golan levin - circle morphing ==> https://github.com/CodingTrain/website/blob/master/_GuestTutorials/7-golan-levin-circle-morphing.md // https://www.youtube.com/watch?v=mvgcNOX8JGQ
- Diffusion limited aggregation (DLA) // https://www.youtube.com/watch?v=uBy3Uouy76Q
- RDP algorithm
- Discussing es6 classes vis-a-vis p5 vectors:
    + vectors have and angle and magnitude
    + conceptuall a postion is a vector from 0,0 which is why p5.vector has an x and y
- Euler integration:
    + velocity affects the position
    + acceleration affects the velocity
    ```
    velocity.add(acceleration)
    position.add(velocity)
    ```
- `p5.Vector.random2D()`
    + creates a unit vector with random vals b/w 0 and 1 for x and y
- `p5.Vector.fromAngle( radians(angle degrees) )` ==> get a vector from an angle! wow!
- the essence of calculus - youtube
    + looking at rate of change  (e.g. ▵x / ▵t)
- Other types of integration:
    + e.g. Verlet integration 
- Force = Mass * Acceleration
    + in early examples, we might consider that we have a world where mass == 1


## Nature of Code Chapter 1: vectors
* [Kadenze videos: p5.js](https://www.kadenze.com/courses/the-nature-of-code/info) -- Session 1
* [Chapter 1 text: Processing](http://natureofcode.com/book/chapter-1-vectors/)
* [Chapter 1 videos: Processing](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZwSmtE13iJBcoI-r4y7iEc)
* [Processing examples](https://github.com/nature-of-code/noc-examples-processing/tree/master/chp01_vectors)
* [p5.js examples](https://github.com/nature-of-code/noc-examples-p5.js/tree/master/chp01_vectors)

## Nature of Code Chapter 2: Forces
* [Kadenze videos: p5.js](https://www.kadenze.com/courses/the-nature-of-code/info) -- Session 2
* [Nature of Code Chapter 2 text: Processing](http://natureofcode.com/book/chapter-2-forces/)
* [Nature of Code Chapter 2 videos: Processing](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZRrqLcQ5BkBKmBLiGD8n4O)
* [Processing examples](https://github.com/nature-of-code/noc-examples-processing/tree/master/chp02_forces)
* [p5.js examples](https://github.com/nature-of-code/noc-examples-p5.js/tree/master/chp02_forces)
* [Attraction and repulsion coding challenge video: p5.js](https://thecodingtrain.com/CodingChallenges/056-attraction-repulsion.html), [code](https://editor.p5js.org/full/6WL2O4vq0)

## In-class Code
* TBA

## Assignment
* [Assignment](https://github.com/nature-of-code/noc-syllabus-S19/wiki/Assignment-2)

## Supplemental Reading
* [Newtonian Physics, An Online Textbook](http://www.lightandmatter.com/area1book1.html) (This is long, you may find Chapter 4 to be particularly relevant to this week's discussion.)
* [The Physics Classroom -- Newton's Laws](http://www.physicsclassroom.com/Class/newtlaws/newtltoc.html)
* [Mathematics and Physics for Programmers](http://www.amazon.com/gp/product/1584503300/), Chapters 12 and 14

## Web Editor Example Links

### Chapter 1: Vectors
* [1.1: Bouncing ball with no vectors](http://editor.p5js.org/natureofcode/sketches/Sk4d-UUPx)
* [1.2: Bouncing ball with vectors](http://editor.p5js.org/natureofcode/sketches/rkIaZUIvx)
* [1.2: Bouncing ball with vectors and objects](http://editor.p5js.org/natureofcode/sketches/B1HXjDzdl)
* [1.3: Vector subtraction](http://editor.p5js.org/natureofcode/sketches/H14-fI8Px)
* [1.4: Multiplying a vector](http://editor.p5js.org/natureofcode/sketches/HkoNf8Uve)
* [1.5: Vector magnitude](http://editor.p5js.org/natureofcode/sketches/SyeuMLLvg)
* [1.6: Normalizing a vector](http://editor.p5js.org/natureofcode/sketches/SJ2hzULPg)
* [1.7: Motion 101 (velocity)](http://editor.p5js.org/natureofcode/sketches/Bkg4XUIwe)
* [1.8: Motion 101 (velocity and constant acceleration)](http://editor.p5js.org/natureofcode/sketches/Sy3k4ILDg)
* [1.9: Motion 101 (velocity and random acceleration)](http://editor.p5js.org/natureofcode/sketches/ByT9EIUDl)
* [1.10: Accelerating towards the mouse](http://editor.p5js.org/natureofcode/sketches/ryAIHLIPe)
* [1.11: Array of movers accelerating towards the mouse](http://editor.p5js.org/natureofcode/sketches/Sy5lLI8ve)

### Chapter 2: Forces
* [2.1: Forces](http://editor.p5js.org/natureofcode/sketches/B13QnJZul)
* [2.2: Forces acting on many objects](http://editor.p5js.org/natureofcode/sketches/SJC2hk-dl)
* [2.3: Gravity scaled by mass](http://editor.p5js.org/natureofcode/sketches/HyQea1W_l)
* [2.4: Including friction](http://editor.p5js.org/natureofcode/sketches/B1isyebug)
* [2.5: Fluid Resistance](http://editor.p5js.org/natureofcode/sketches/H1DmxeW_g)
* [2.6: Attraction](http://editor.p5js.org/natureofcode/sketches/HyWqel-de)
* [2.7: Attraction with many Movers](http://editor.p5js.org/natureofcode/sketches/rJ9l-x-Ox)
* [2.8: Mutual attraction](http://editor.p5js.org/natureofcode/sketches/SkYSWlb_x)
