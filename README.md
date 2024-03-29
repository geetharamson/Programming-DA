# Programming in DATA ANALYTICS
## Geetha Karthikesan 
### Higher Diploma in DATA ANALYTICS 2019-2020 

## How to clone this repository
A repository on GitHub exists as a remote repository. You can clone this repository to create a local copy on your computer by following these instructions:

On GitHub, navigate to the main page of the repository GitHub

Under the repository name, click Clone or download.

Choose "Clone with HTTPS".Click the Code button which is colored green.

Open a terminal on your machine. Change the current working directory to the location where you want the cloned directory to be made.

Type git clone, and then paste the URL you copied in 2 above.

   https://github.com/geetharamson/Programming-DA.git/
6.Press enter to clone the repository to your machine.
  
####  1.Purpose of Numpy.random package
   To generate an array of random numbers  we need to use numpy. numpy has the numpy.random package which has multiple 
   functions to generate the random n-dimensional array for various distributions.To generate “true” random numbers, random
   number generators gather random data from the physical world around them. For random numbers that are cannot
   be random, we may just use an algorithm and a seed value.Generating truly random numbers in software is indeed 
   impossible, however it is possible with hardware to build a device which can generate truly random numbers.This package 
   approximate random numbers, but are 100% determined by the input and the pseudo-random number algorithm.
    
#### 2.Use of "Simple random data" and "Permutations" functions    
   ###### numpy.random.rand(d0, d1, ..., dn)
Random values in a given shape.
Create an array of the given shape and populate it with random samples from a uniform distribution over [0, 1).

Parameters:
d0, d1, ..., dn : int, optional
The dimensions of the returned array, should all be positive. If no argument is given a single Python float is returned.
Returns:
out : ndarray, shape (d0, d1, ..., dn)
Random values.

###### numpy.random.bytes(length)
Return random bytes.
Parameters:	
        length : int
Number of random bytes.
Returns:	
out : str
String of length length.

### Permutation
###### numpy.random.permutation(x)

Randomly permute a sequence, or return a permuted range.
If x is a multi-dimensional array, it is only shuffled along its first index.
Parameters:	
       x : int or array_like
If x is an integer, randomly permute np.arange(x). If x is an array, make a copy and shuffle the elements randomly.
Returns:	
        out : ndarray
Permuted sequence or array range

#### 3. Distribution function
###### numpy.random.chisquare
###### numpy.random.chisquare(df, size=None)

When df independent random variables, each with standard normal distributions (mean 0, variance 1), are squared and summed, the resulting distribution is chi-square (see Notes). This distribution is often used in hypothesis testing.
Parameters:	
    
    df : float or array_like of floats
    Number of degrees of freedom, should be > 0.
    size : int or tuple of ints, optional
    Output shape. If the given shape is, e.g., (m, n, k), then m * n * k samples are drawn. If size is None (default), a single value is returned ie. df is a scalar. Otherwise np.array(df).size samples are drawn.

Returns:	
out : ndarray or scalar

###### Gaussian distribution:
Gaussian distribution (also known as normal distribution) is a bell-shaped curve, and it is assumed that during any measurement values will follow a normal distribution with an equal number of measurements above and below the mean value.

###### Exponential Distribution
 The exponential distribution is a continuous analogue of the geometric distribution. It describes many common situations, such as the size of raindrops measured over many rainstorms.
 
######  Poisson Distribution
 Poisson Distribution is a discrete probability distribution that expresses the probability of a given number of events occurring in a fixed interval of time or space if these events occur with a known constant rate and independently of the time since the last event. The Poisson distribution can also be used for the number of events in other specified intervals such as distance, area or volume.
 
 ###### numpy.random.power
numpy.random.power(a, size=None) Draws samples in [0, 1] from a power distribution with positive exponent a - 1. Also
known as the power function distribution.
 
#### Seeds in generating pseudorandom numbers

A random seed is a starting point in generating random numbers. A random seed specifies the start point when a
computer generates a random number sequence. A random seed (or seed state, or just seed) is a number used to 
initialize a pseudorandom number generator. For a seed to be used in a pseudorandom number generator, it does not
need to be random.
     Pseudo Random Number Generator(PRNG) refers to an algorithm that uses mathematical formulas to produce sequences 
of random numbers. PRNGs generate a sequence of numbers approximating the properties of random numbers.For a seed to be
used in a pseudorandom number generator, it does not need to be random. A pseudorandom number generator's number sequence 
is completely determined by the seed: thus, if a pseudorandom number generator is reinitialized with the same seed, it 
will produce the same sequence of numbers.
     Seed function is used to save the state of random function, so that it can generate some random numbers on multiple 
execution of the code on the same machine or on different machines (for a specific seed value). Seed value is the previous
value number generated by the generator.If we use same seed every time, it will yield same sequence of random numbers.
The reason for using a seed of some value is when we want to debug the program using such deterministic behavior.
    
    numpy.random.seed
    numpy.random.seed(seed=None)
  This method is called when RandomState is initialized. It can be called again to re-seed the generator.
             
  #### uses of random.seed()
   1.This is used in generation of pseudo-random encryption key. Encryption keys are important part of computer security.
   These are the kind of secret keys which used to protect data from unauthorized access over internet.
   2.It makes optimization of codes easy where random numbers are used for testing. The output of the code sometime depends 
   on input. So the use of random numbers for testing algorithm can be complex. Also seed function is used to generate same 
   random numbers again and again and simplifies algorithm testing process.
 
## References 

[Machinelearning](https://machinelearningmastery.com/how-to-generate-random-numbers-in-python/)

[Geek](https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)

[ftp](http://ftp.heanet.ie/pub/ctan.org/tex/info/symbols/comprehensive/symbols-a4.pdf)

[numpy](https://numpy.org/doc/1.17/user/basics.types.html)

[scipy](https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.random.normal.html#numpy.random.normal)

[jupyter](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Typesetting%20Equations.html#Other-Syntax)

[stanford](https://stanford.edu/~shervine/teaching/cs-229/refresher-probabilities-statistics)

[programcreek](https://www.programcreek.com/python/example/50979/numpy.random.poisson)

# Requirements

#### Python version - 3.7.4

####  [git](https://git-scm.com/)

#### Cmder|Console Emulator [cmder](http://cmder.net/)

#### Jupyter Notebook

#### Windows : if you are using Windows I recommend you use cmder as your terminal. If you are on Mac or Linux I recommend you use the default Terminal to open the project.

#### [github](https://github.com/geetharamson/Programming-DA)
Else in 
#### [JupyterNotebook](https://github.com/geetharamson/Programming-DA/blob/master/programming%20DA.ipynb)

