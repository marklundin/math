A collection of commonly used math functions

###mix
Lineary interpolates between a->b, using n as a weight
```mix( 0.5, 0, 16 ) // 8.0```

###map
Linearly maps n from the range a->b to x->y
```map( 10, 0, 20, 0, 200 ) // 100.0```

###normalize
Linearly maps n from a->b to 0-1
```normalize( 10, 0, 20 ) // 0.5```

###clamp
Clamps n within the range a-b
```clamp( 1.2, 0, 1 ) // 1.0```

###random
Returns a pseudo-random number within the range a->b, if b is not supplied it returns within the range 0-a
```10 <= random( 10, 20 ) <= 20.0```
