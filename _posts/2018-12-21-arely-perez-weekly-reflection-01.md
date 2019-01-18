---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

Flag of _insert your country_ by _insert your name_
My Flag Pakistan 

## Describe your program
So in my flag you would be able to see how the crescent is on one side its tilted and the star is rotated in an angle the rectangle is\all solid green.
i guess A grade I would expect out of this is a 3 since I did my program good.

## Current output

* * *
https://www.wescheme.org/view?publicId=eSVnixl1aZ
* * *

## Describe your process.

AT first in the beginning of doing this i really didnt know what to do first. Than I realized I needed to start with the first layer which would be the green solid rectangle. I had to figure out what the best color fit would be. Than I have come to a point where I was just layering all these shapes on top of each other to get the image that i wanted. Well the person who had helped me the most in this I would give credit to savannah because we had about the same flag and we had worked together to finish up this professional flag.

## Explain your code.
(define SIZE(* 2 50))
(define HEIGHT(* 5 30))
(define GRE (make-color 1 65 28))

(define GREEN (make-color 231 0 19))

(define WHITE(make-color 255 255 255))

(define REC(rectangle(* 3 150) (* 3 100) "solid" "green"))

(define CIR1(circle SIZE "solid" "white" ))

(define CIR2 (circle SIZE "solid" "green"))
 
(define STAR( rotate 100 (star (* 5 7 ) "solid" "white")))

well what was so significant about this part of my program would be the beginning since i would make my life so easier when doing th size of ones shape not onlt was that significant but also how I shortened these function names. 
* * *
``````
* * *
The first few lines of my code would basically make ones life easier by changing the functions name and replacing with a nickname or a "variable". After doing that instead of putting the size number you would instead plug in the "SIZE". Same goes for the color that you are using it would affect my code a lot in a positive way.

## Program code
```
(define SIZE(* 2 50))
(define HEIGHT(* 5 30))
(define GRE (make-color 1 65 28))

(define GREEN (make-color 231 0 19))

(define WHITE(make-color 255 255 255))

(define REC(rectangle(* 3 150) (* 3 100) "solid" "green"))

(define CIR1(circle SIZE "solid" "white" ))

(define CIR2 (circle SIZE "solid" "green"))
 
(define STAR( rotate 100 (star (* 5 7 ) "solid" "white")))

(define FLAG (rectangle(* 2 250)(* 2 150)"outline" "black"))

(put-image STAR 365 200 (put-image CIR2 340 175 (put-image CIR1 310 HEIGHT (put-image REC 350 HEIGHT FLAG))))
