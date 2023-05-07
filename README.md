# AM6020 Assignments (Continuous Assessment).
The .ipynb files in this repo were completed as part of University College Cork's AM6020: "Open Source Infrastructure for Modelling and Big Data" module. This was one of my first in depth experiences with python and this the code produced was that of a beginner.



## AM6020 Assignment 1.
### Part 1: Vigenère cipher.
Given a text which has been encrypted with a Vigenère cipher print the decrypted message and the keyword. The encrypted message is known to be a recipe for gingerbread and the key used is 4 letters in length. A brute force approach is used to generate every possible key of length 4. Then the functions "keygen" and "decipher" are made and applied to elongate a given key to the length of the input text and then decipher the text accordingley. The latter function only prints an output if the word "gingerbread" is found within the decrypted text along with the key used to do so.

### Part 2: Oscillations in gene regulation.
The aim of this section is to use Euler's method to produce your own cellular oscillations in the concentrations of proteins (x), mRNA (y) and sncRNA (z) given the association rate of the small-noncoding RNA and protein (A). The x0, y0 and z0 parameters are used to represent the starting concentrations of their respective biomolecules in our hypothetical cell.
the rates of change of each are given in the image contained within the notebook and have been transcribed in markdown for the sake of clarity.

## AM6020 Assignment 2.
### Part 1:  Plotting Data.
Given the data file energy_data.csv contains a breakdown of energy sources being used in Ireland from 1990-2018. Read this data into a numpy array and plot the year usage of each fuel type, all on the same axes and create a figure legend. Then plot the total fuel usage; that is, usage of all the fuel types together for each year. Finally a stackplot is created to plot the usage of each fuel type.

### Part 2: Dictionaries.
This section focuses on the use of python dictionaries. Given a dictionary that summarises the stock at a certain supermarket our first task is to make a function to return the total cost if you were to purchase everything in the supermarket. Finally, given a number of shoppers and their purchases in the form of dictionaries create a function that will return a total cost for each supermarket customer.

### Part 3: Blurring images.
Write your own code to apply a *mean blur* to an image by kernel convolution (ie do NOT use OpenCV). The mean blur is applied to *cactus.jpg*. Initially  a $3\times 3$ kernel is used and the results are plotted next to the original image. Then the code is adapted for a $n\times n$ kernel.