# A symbolic computational approach to the generalized gambler's ruin problem in one and two dimensions
* Based on [this paper](#) by [Lucy Martinez](https://marti310.github.io/ "Lucy")
  
## Usage    
* Example using GGR1d.txt. Save this file as  GGR1d.txt to use it and stay in the same directory. Get into Mape and type:

``` read `GGR1d.txt:` ```

* The following will be prompted

```
        First Written: March 2024: tested for Maple 20 
              This is GGR1d.txt, a Maple package 
            accompanying Lucy Martinez's  article: 
A symbolic computational approach to the generalized gambler's ruin problem in one and two dimensions

                -------------------------------

                -------------------------------

       The most current version is available at the url: https://

  Please report all bugs to: lm1154@scarletmail.rutgers.edu  .

                -------------------------------

      For general help, and a list of the MAIN functions,

 type "Help();". For specific help type "Help(procedure_name);" 

                -------------------------------

   For a list of the simulation (classical game or general) functions type:  HelpSimu();

   For a list of the slow (classical game or general) functions type:  HelpSlow();

      For help with a specific procedure, type "Help(procedure_name);"

```

* Inputing `GR1dP(5)`, outputs a list L of length N-1 such that L[x] is the probability that a particle starting at x will eventually reach a position x=N

```
GR1dP(5);
```

* Inputing `GR1dL(5)`, outputs a list L of length N-1 such that L[x] is the the expected number of steps that a particle starting at $x$ will eventually take to reach a position x=0 or x=N
```
GR1dL(5);
```
