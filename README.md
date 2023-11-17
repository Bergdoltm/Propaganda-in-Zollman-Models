# Propaganda-in-Zollman-Models
The base of this code comes from Rosenstock et al. 2017, who publicly released code for the traditional Zollman model (without propagandists).  This can be found here: https://www.dropbox.com/sh/lyk7sd6h8459obp/AADxMzMcEDy--K1Odq9rlM97a?dl=0

I developed this work by expanding her code, and, as such, this code reflects the same structure and includes some of the same basic methods as hers.  I try to call these out with in-line comments.

The code was initially adapted to reproduce the results of Weatherall, O'Connor, and Bruner 2018.  The code for the reproduced results is not in this repository, but I am happy to send it if you contact me at: mhbergdolt@gmail.com

# Currently, this code has the following capabilities:
1. Propaganda similar to the Weatherall et. al model, but using a beta approximation rather than discrete Bayesian inference:
       This includes both the selective sharing and biased production strategies.
       Propagandists in this code have adjustable beliefs and can promote true or false positions.
2. Competitive propaganda:
     Technically, this code has the ability to establish 2 propagandists that promote any position between 0 and 1, but this is most interesting when they compete and promote positions at either extreme relative to the truth.
3. Confirmation bias as a strategy to defeat propaganda:
       In working with this code, I found the unique strategy for scientists to defeat propagandists: they only publish results that confirm their biases.
       Confirmation bias in this model is established using prior credible intervals.
   
As of 11/15/23, this code still requires some "clean up" for readability.  Contact me via email if you stumble across this page and need clarification about some function or method.
