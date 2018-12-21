---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _Malaysia_ by _Tyler Marx_

## Describe your program

The country I designed for was Malaysia. I is a pretty hard flag to make, but in the end it will look cool. I expect to hopefully get a professional grade because this flag was advanced and I worked hard on it a put every detail into it.

## Current output

* * *
![Flag](/images/FinalFlag.png)
* * *

## Describe your process.

The process was really hard to create the Malaysian flag. The first challenge I had was creating the star. The star has 14 points on it. However, I looked up how to do it, and I figures it out. You have to input 3 numbers for your star. The first number is the number of points. The second number is the radius of the middle. The last number is the size of the whole star. Another problem I had was creating the stripes for the flag. With help from Steven and Benjamin, I figured out how to do it by using definitions.


## Explain your code.


The arguments in the box are the most important in my whole code. The definitions leading up to the final flag are what really helped instead of rewriting the code over and over again. It does function independently because the definitions that were already made are what helps the code create the image.

* * *

```
(define BIG (rectangle WITH HIGHT "solid" "darkblue"))
(define JUICE (circle 40 "solid" "gold"))
(define BOB (circle 30 "solid" "darkblue"))
(define CRESCENT (put-image BOB 55 42 JUICE))
(define TOGETHER (put-image BIG 70 150 BOX))
(define YEET (put-image CRESCENT 46 150 TOGETHER))
(define YUSS (put-image STAR 105 150 YEET))
(define OK (put-image STRIPES 150 7 YUSS))
(define OMG (put-image STRIPES 150 35 OK))
(define OOF (put-image STRIPES 150 63 OMG))
(define GOOD (put-image STRIPES 150 91 OOF))
(define DOG (put-image STRIPE 225 119 GOOD))
(define CAT (put-image STRIPE 225 147 DOG))
(define HOORAY (put-image STRIPE 225 175 CAT))
HOORAY
```

* * *

 This code is what creates the final flag. Stripes are the stripes for the flag, Hooray is the final flag, and all the other random words are the steps it took to create it. For example, OOF would have only 3 white stripes and a red background with a blue patch and a crescent and a star. HOORAY would be the final image with all the stripes needed and the rest of the flag. This section fits into the whole because without it, the final image wouldn't be complete.



## Program code

```
(define STRIPES (rectangle 300 14 "solid" "white"))
(define STRIPE (rectangle 160 14 "solid" "white"))
(define STAR (scale 3/4 (star 14 22 50 "solid" "gold")))
(define WIDTH 300)
(define HEIGHT 200)
(define BOX (rectangle WIDTH HEIGHT "solid" "red"))
(define WITH 150)
(define HIGHT 105)
(define BIG (rectangle WITH HIGHT "solid" "darkblue"))
(define JUICE (circle 40 "solid" "gold"))
(define BOB (circle 30 "solid" "darkblue"))
(define CRESCENT (put-image BOB 55 42 JUICE))
(define TOGETHER (put-image BIG 70 150 BOX))
(define YEET (put-image CRESCENT 46 150 TOGETHER))
(define YUSS (put-image STAR 105 150 YEET))
(define OK (put-image STRIPES 150 7 YUSS))
(define OMG (put-image STRIPES 150 35 OK))
(define OOF (put-image STRIPES 150 63 OMG))
(define GOOD (put-image STRIPES 150 91 OOF))
(define DOG (put-image STRIPE 225 119 GOOD))
(define CAT (put-image STRIPE 225 147 DOG))
(define HOORAY (put-image STRIPE 225 175 CAT))
HOORAY

```
