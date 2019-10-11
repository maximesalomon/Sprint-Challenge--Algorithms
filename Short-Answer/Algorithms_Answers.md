#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n) - no loop, n doesn't changes

b) 0(n^2) - one loop to go over n

c) 0(n) - recursive algorithm

## Exercise II

def safeFloor(n)
    dropped = 1
    broken = false

    while (broken == false AND dropped <= n):
        drop egg from dropped
        if egg breaks:
            broken = true
        else:
            dropped =+ 1

    if dropped == 1
        return 0
    elif dropped > n:
        return "Egg didn't brake"
    else:
        return dropped


