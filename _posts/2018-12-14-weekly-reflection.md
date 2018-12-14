---
layout: post
title: "Flag Project v2 Progress Report"
date: 2018-12-14
---

This week in CS, we continued our flag project 2.0. Here is the code and image that I got so far:
```
(define STAR (scale 3/4 (star 14 22 50 "solid" "gold")))
(define WIDTH 300)
(define HEIGHT 200)
(define BOX (rectangle WIDTH HEIGHT "solid" "red"))
(define WITH 150)
(define HIGHT 100)
(define BIG (rectangle WITH HIGHT "solid" "blue"))
(define JUICE (circle 40 "solid" "gold"))
(define BOB (circle 30 "solid" "blue"))
(define CRESCENT (put-image BOB 55 40 JUICE))
(define TOGETHER (put-image BIG 70 150 BOX))
(define YEET (put-image CRESCENT 46 150 TOGETHER))
(define YUSS (put-image STAR 105 150 YEET))
YUSS
```
![MyFlag](/images/FlagV2.0.png)

If you haven't seen my last blog, I am doing the Malaysian flag for my project. A challenge I had making this flag was doing the star. The malaysian flag star has 14 points in it. I thought I would never be able to do it until I figured out that you can have 3 different numbers for a star. The first number, 14, is how many points it has, the second number, 22, is the size of the circle in the middle of the star, and the third number, 50, is the size of the whole star. I also had trouble finding the right sized circle to make a crescent, but I fixed that quickly. I am looking foward to finishing my flag project next week.
