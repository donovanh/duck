SASSY DUCK
==========

Sassy Duck is a duck rendered in HAML/SASS. Browser performance may vary.

Why
---

http://i.imgur.com/FKRqc.gif

Demo
----

A demo is available at: http://donovanh.github.com/duck

Structure
------------

The HAML is straightforward. Items stack from the back to front, so for example the head of the duck is mentioned later than the body so that it sits in front.

    .duck
      .body
        .wing
          .wing-part1
            .wing-part1a
          .wing-part2
            .wing-part2a
          .wing-part3
            .wing-part3a

      .head
        .beak
          .beak-part1
          .beak-part2
        .eye
          .eye-dark
            .eye-shine
            
I've approached the wings by using two DIVs for each feather in the wings. In retrospect it might be better to use a radial gradient for the light / dark sections. I might revisit this.

The SASS / CSS is based on EMs for proportions. This means that the font size can be adjusted to scale it. When building it I started with pixel dimensions and converted them to EMs later.

Inspiration
-----------

The design was inspired by WebDesign.org's great article on how to design a cartoon duck:

http://www.webdesign.org/vector-graphics/adobe-illustrator/how-to-draw-a-cartoon-duck.18049.html

Usage
-----

Feel free to copy, hack, and share. I hope it's helpful and would love any feedback or pull requests.

Thanks
------

* SASS: http://sass-lang.com
* HAML: http://haml.info/

Thanks also to Steve (@stevebiscuit) for the kind words.

