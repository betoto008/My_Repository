How to use the template:

Note: Have a look at ./lib/random.cpp. There are two functions that lie in random.cpp: 

double randX(min,max): a random number between min and max
int randIX(min,max): an integer random number between min and max 

They are random number generators (integer and real value respectively). The file includes the randomc library for random number generator with Mersenne algorithm written by Agner Fog, published under GNU General Public License (please have a look at the relevant documents in randomc).

1)
Fill in the missing parts in the template source file (mc.cpp).
They are clearly indicated by the comment //FOR YOU TO FILL IN
Warning: The file will not compile before you fill in the gaps. There are uncommented lines "…" in these places that through an error.

2)

Compile mc.cpp, using a standard compiler, like

"g++ mc.cpp -o mc.x"

and run it.

Then use a program of your choice to plot the data in the file
"output.txt" generated by the mc program. In the template you can find
one possible way to post-process the results of your simulations, with
a notebook written in Mathematica.

Note that the programs takes some 30-45 minutes to run, slightly depending on how you optimise your commands.

3)
Regrading the critical exponents, a simple estimation by “pencil and ruler” is enough, no need for any complicated computer fitting function.
