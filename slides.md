<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->

# Genetic Improvement
<!-- .element: class="no-toc-progress" --> <!-- slide not in toc progress bar -->

### Revolutionising programming or just fixing bugs?

By [Fraser Garrow](https://github.com/frsrgrrw) | 18-11-2020

----  ----

## 1. What is GI?

----

## What is GI?

<div class="fragment" />

* <!-- .element: class="fragment" -->  Genetic Programming
 

* <!-- .element: class="fragment" --> Search Based Software Engineering

<!-- .element: class="fragment" --> With GI the idea is to improve **EXISTING PROGRAMS** by genetic programming

----  ----

## 2. What are we improving?

----

## What are we improving?

<div class="fragment" />

<!-- .element: class="fragment" -->code functionality

<!-- .element: class="fragment" -->i.e. maintaining correct output (bug-fixing)
* <!-- .element: class="fragment" --> new functionality or feature
* <!-- .element: class="fragment" --> time or space efficiency
* <!-- .element: class="fragment" --> power consumption

----  ----

## 3. Why is this useful?

----

## Why is this useful?

<div class="fragment" />

<!-- .element: class="fragment" -->code maintenance is an expensive process. Industry is already using GI for maintenance REF.

<!-- .element: class="fragment" -->there is lots of computer programs already written, we don't need to start from scratch.

<!-- .element: class="fragment" -->computers are good at optimising for criteria that humans are not so good at.

----  ----

## 4. How does it work?


----

<!-- .slide: data-transition="none" --> 
## How does it work?

<img src="img/1.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" --> 
## How does it work?

<img src="img/2.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" --> 
## How does it work?

<img src="img/3.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/4.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/5.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/6.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/7.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/8.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/9.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/10.PNG" width="826" height="574">

----  

<!-- .slide: data-transition="none" --> 
## How does it work?

<img src="img/11.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" --> 
## How does it work?

<img src="img/12.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" --> 
## How does it work?

<img src="img/13.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/14.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/15.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/16.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/17.PNG" width="826" height="574">

----

<!-- .slide: data-transition="none" -->
## How does it work?

<img src="img/18.PNG" width="826" height="574">

----  ----

## 5. Representation

----

## Representation

<div class="fragment" />

* <!-- .element: class="fragment" --> Grammar based encoding
* <!-- .element: class="fragment" --> Syntax trees

<!-- .element: class="fragment" --> These can help ensure evolved programs are *correct*, but programs are less fragile than we think REF
* <!-- .element: class="fragment" -->Source code - simple and conveinnient

----  ----

## 6. Code Patches

----

## Code Patches

Code patches are just a list of edits that we apply to the existing program to create a new program

<div class="fragment" />

<!-- .element: class="fragment" --> So, what is an edit?

* <!-- .element: class="fragment" --> `Insert(location, code)`
* <!-- .element: class="fragment" --> `Remove(location)`
* <!-- .element: class="fragment" --> `Replace(location, code)`

----  ----

## 7. Genetic Material

----

## Genetic Material

<div class="fragment" />

* <!-- .element: class="fragment" --> Code transplants from the existing program (we repeat code lots) 
* <!-- .element: class="fragment" --> Derived from the grammar or allowable list of operators
* <!-- .element: class="fragment" --> Code transplants from outside sources – GitHub, StackOverflow, SourceForge, GitLab, BitBucket etc. (there is an abundance of code available)


----  ----

## 8. Improvement Criteria (again)

----

## Improvement Criteria

<div class="fragment" />

1. <!-- .element: class="fragment" --> Functional Properties
  * <!-- .element: class="fragment" --> Functionality and correct output, the features and normal usage
2. <!-- .element: class="fragment" --> Non-Functional Properties
  * <!-- .element: class="fragment" --> memory usage, execution time, power-usage, etc.. Things we might consider difficult for a human to optimise

----

## Improvement Criteria

The non-functional properties of programs are becoming increasingly more important as move away from the era of desktop computing.

<div class="fragment" />

<!-- .element: class="fragment" --> With GI we can create programs that explore trade-offs between properties.

----

## Improvement Criteria

When might me want to be less ‘correct’ but more efficient?

<div class="fragment" />

<!-- .element: class="fragment" --> When we cosnider things liek mobile computing or robots we can easily think of scenarios where it might be preferable to do a ob with reduced funcitonality if it means increased battery life.

<!-- .element: class="fragment" --> In mobile computing all of the functionality depends on the ability to sustain battery power, if this runs out there is no functionality.

----  ----

## 9. Case Studies

----

## Case Studies - Bug Fixing

----

## Case Studies - Energy Consumption

----

## Case Studies - Execution Time

----

## Case Studies - SLAM

----  ----

## 10. The Future of GI

----

## The Future of GI

* Self-adaptive systems
* Programs that can be tuned for specific purposes, maybe one day it has to be faster than it is accurate and vice versa

----  ----

## Try it yourself

* PyGGI
* GIN

----  ----

## References

