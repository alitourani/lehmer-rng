# Lehmer Random Number Generator (Lehmer-RNG)
This program calculates the value of Lehmer parameter with a given *Lambda* even in very high rates. This is also known as **"Lehmer Random Number Generator"** which is a type of **Linear Congruential Generator (LCG)** that operates in multiplicative group of integers modulo *n*. This function is defined as a recurrence relation similar to the *LCG* with c=0, as below:
```markdown
X(i+1) = a.X(i) | m
```

Unlike the *LCG*, the parameters *a* and *m* for multiplicative congruential generators are more restricted and the initial seed *X0* must be relatively prime to the modulus *m* (the greatest common divisor between X0 and m is 0). The current parameters in common use are m=2^31−1=2,147,483,647 and a=7^5=16,807.

### References:
1. Anne Gille-Genest (March 1, 2012). Implementation of the Pseudo-Random Number Generators and the Low Discrepancy Sequences.
2. Lehmer RNGs - See this [link](https://rstudio-pubs-static.s3.amazonaws.com/300542_7c3b39404d2e4d20a80eceb05ad8d513.html "link") for more information.
