# Programming-DA
## Geetha Karthikesan-DA 2019-20 
  
####  1.Purpose of Numpy.random package

       To generate an array of random numbers  we need to use numpy. numpy has the numpy.random package which has multiple 
    functions to generate the random n-dimensional array for various distributions.To generate “true” random numbers, random
    number generators gather random data from the physical world around them. For random numbers that are cannot
    be random, we may just use an algorithm and a seed value.Generating truly random numbers in software is indeed 
    impossible, however it is possible with hardware to build a device which can generate truly random numbers.This package 
    approximate random numbers, but are 100% determined by the input and the pseudo-random number algorithm.
    
    
#### 2.Use of "Simple random data" and "Permutations" functions    
   ######## numpy.random.rand(d0, d1, ..., dn)
Random values in a given shape.
Create an array of the given shape and populate it with random samples from a uniform distribution over [0, 1).

Parameters:
d0, d1, ..., dn : int, optional
The dimensions of the returned array, should all be positive. If no argument is given a single Python float is returned.
Returns:
out : ndarray, shape (d0, d1, ..., dn)
Random values.

########numpy.random.bytes(length)
Return random bytes.
Parameters:	
        length : int
Number of random bytes.
Returns:	
out : str
String of length length.

####### Permutation
numpy.random.permutation(x)
Randomly permute a sequence, or return a permuted range.

If x is a multi-dimensional array, it is only shuffled along its first index.
Parameters:	
x : int or array_like
If x is an integer, randomly permute np.arange(x). If x is an array, make a copy and shuffle the elements randomly.
Returns:	
out : ndarray
Permuted sequence or array range.

#### Distribution function
 
## References 
https://machinelearningmastery.com/how-to-generate-random-numbers-in-python/

https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/

http://ftp.heanet.ie/pub/ctan.org/tex/info/symbols/comprehensive/symbols-a4.pdf
https://numpy.org/doc/1.17/user/basics.types.html
https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.random.normal.html#numpy.random.normal
https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Typesetting%20Equations.html#Other-Syntax


## Requirements
Python version -3.7.4
Jupyter Notebook
[link]https://git-scm.com/  
Cmder | Console Emulator
http://cmder.net/
   Windows only: if you are using Windows I recommend you use cmder as your terminal. If you are on Mac or Linux I recommend you use the default Terminal to open the project.
