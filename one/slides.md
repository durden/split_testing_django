<!SLIDE small>

(Simple) Django Split Testing
========================

<!SLIDE bullets>

Luke Lee
========
- Python developer
- Django enthusiast

<!SLIDE small>

Overview
========
- What is A/B Split Testing
- Why
- Simple implementation
- Pitfalls
- More formal/published attempts
- Django?

<!SLIDE small incremental>

A/B Split Testing
==================
- Not developer testing
- Designed by marketing, created by developers
- Define variations and goal
- Test site copy, UI layout, form length
- Track conversion rates

<!SLIDE small incremental>

Why
==================
- Improve overall success of site
- Improve focus on variables that matter
- Easy
- Cheap

<!SLIDE small incremental>

Simple Implementation
==================
- Needs:
    - Ability to run test for limited time
    - Turn on/off immediately
    - Track visitors/conversion
    - Hide from user

<!SLIDE small incremental>

A/B Testing Playground
==================
- Goal: Get users to register
- Variations:
    - Site copy
    - Button text
    - More data entry
- [Playground](http://split-testing.herokuapp.com/)

<!SLIDE small incremental>

Pitfalls
==================
- Template tied to database entry directly
- New test involves developer, designer, and marketing

<!SLIDE small incremental>

Improvements
==================
- Decorator
- Create template based on choice ID
    - Caching?

<!SLIDE smaller>

Formal/full-featured projects
==================
- [django-ab](https://github.com/johnboxall/django-ab)
- [django-lean](https://bitbucket.org/akoha/django-lean/wiki/Home)

<!SLIDE smaller>

Django?
==================
- [Google](www.google.com/websiteoptimizer)
- [Visual Website Optimizer](http://visualwebsiteoptimizer.com/)

<!SLIDE smaller>

Links
=====
- Code
    - [sample app](https://github.com/durden/split_testing_playground)
    - [presentation code](https://github.com/durden/split_testing_django)
    - [references](http://www.pinboard.in/u:durden/t:split_testing/)
    - [showoff](https://github.com/schacon/showoff)

- Me
    - [@durden20](http://twitter.com/#!/durden20)
    - [github](http://github.com/durden)
    - [lukelee.net](http://lukelee.net)
    - [codrspace](http://codrspace.com/durden)
    - [tumblr](http://durden.tumblr.com)
