# 100 Go Mistakes

## Overview

This is a very interesting book, especially this being my first technical reading.
I think I am learning a lot, but also it is slightly daunting as a casual read.
Some concepts take a long time to understand, and it is not the best night time reading
material, being already miserable and wanting to sleep.

Regardless I think there are some points that is so niche, but good to have in your
tool belt, as eventually you will come across some of these niche problems.

## Interesting Points

1 very interesting thing I learned so far is the behaviour of the `slice` implementation
in golang. Golang implements list by using a set size array, and would double it's backing
array's capacity everytime it fills up. When thinking/ debuging memory problems when allocating
a large slice of structs, it could cause memory bottle neck that you wouldn't think about
otherwise, but now that I know, it allows me to be more aware of application behaviour,
and I think it is always important to know the intricate behaviour to be able to utilise a system
well.

## Negatives

This book is quite daunting, but it is also not very general. If you read this, it could only
apply to this version of golang, and the language could evolve. It acts as a good starting point
for your understanding of this technology, but require more effort to maintain, so the time spent
reading might eventually become redundant.

It is also not very magically revealing of problems, and most of the problems are niche points.
So it is likely that by using a more simple programming style, you avoid most of these mistakes
entirely.
