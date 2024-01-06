## TimeComplexity:

How many times it taks to run the program for a given input.
It not time take complete the program execution because it consist of hardware processing time
Space Complexity:
The memory space taken by a program.

A good program has to consist of time and space complexity while coding…


### Note:

No. of input increases = time complexity increases
No. of input decreases = time complexity decreases


## Asymptotic Notation
It used to show the performance of an algorithm.





### Type of Asymptotic Notation:

1) Big oh (O) notation
2) Big omega (Ω)
3) Big Theta (θ)

#### Big oh (O) notation
- Highest possible output
- Upper bound

```
f(n) <= cg(n)
```

**Ex**:

```
f(n) = 2n+3
```

```
2n+3 <= 10n         =>             O(n)
2n+3 <= 10n^2       =>              O(n^2)
```

#### Omega (Ω) notation:

- Lower bound

```
f(n) >= cg(n)
```

```
2n+3 >= 1n       =>                   Ω(n)
2n+3 >= llogn    =>                Ω(logn)
```

#### Theta:

- Average bound


```
c1*g(n) <= f(n) <= c2*g(n)
```

```
1n <= 2n+3 <= 5n     => θ(n)
```


# Best, Worst and Average case

**Ex**

In linear search:

## Best case:

The search element present in 1st index

## Worst case:
The search element present in at last

## Average case:

All the possible / No. of case 

```
1+2+3…+n/n
n(n+1)/2/n
(n+1)/2

```

```
b(n) = O(1) = Ω(1) = θ(1)

w(n) = O(n) = Ω(n) = θ(n)
```

So, best, worst and average cases is not depend on bound it depend on the input and output


