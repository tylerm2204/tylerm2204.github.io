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

