# information-theory-tool
This toolbox contains Matlab source code for basic computations in information theory, including entropy, conditional entropy,  mutual information, capacity and rate distortion.

Individual functions and several examples are provided, as well as their experiment results shown in PDFs.


-----------------------------------------------------------------------------------------------------------------------------------
The documentation is not completed, but here is part of it. 

Entropy H(X) is the amount of uncertainty about a random variable X.
H(X) = -sum_x  pX(x)log pX(x), where we take: 0 log 0 = 0. Unless otherwise noted, the logarithm is base 2, which corresponds to measuring entropy in bits. If the base is e, the measure is not bits, but a unit called “nats”.

Properties:
-   Entropy is a lower bound on lossless compression: H(X) ≤ minimum number of bits to represent X, on average.
-   Uniform distribution maximizes entropy. The uniform distributionis pX(x)= 1/|X| for x∈X, 
    and so H(X) = sum (1/|X| )( log|X| ) = log|X|.
-   The entropy of a constant is 0. Since a constant is not random, it has no uncertainty and the entropy is 0.
-   Entropy is non-negative. The lower bound H(X) ≥ 0 can be shown by noting that pX(x)≤1means log 1/pX(x) ≥0.

Binary entropy function: h(p) = −p log p − (1 − p) log(1 − p)
An important random variable is the binary random variable. Let X with X = {0, 1} have distribution: 
pX(x) = p if x=0 and pX(x) = 1-p if x=1. Then H(X) = −p log p−(1−p)log(1−p).

                                                                                                                                        to be continued...
