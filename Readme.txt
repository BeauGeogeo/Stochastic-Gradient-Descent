************************************************ Stochastic Gradient Descent Project ************************************************


						*** Context of the project ***


This is the researched project my comrade and I had to do during the second semestre of our first year of master degree. The master
is a research master in applied mathematics, called Mathématiques, Données, Apprentissage (MMA), at Paris Cité University. We had
to read and understand research papers about a subject of our choice, as long as it was related with the topics studied this year.
We then chose a subject linked to optimization and machine learning.


						*** Topic of the project : Stochastic Gradient Descent ***


The aim of the project was to study the proof of the convergence of the stochastic gradient descent, and compare the speed of this
convergence to the speed of the batch gradient descent. Stochastic gradient descent is often used when big calculations are involved.
Since one and only one example is considered at each iteration, there is no problem to store this example in the computer memory, and
updating the parameters after each example rather than having a long calculation of the gradient based on all examples can speed the
convergence to the minimum. 
But because of the noise due to the random choice of an example from the dataset, the convergence is not deterministic but stochastic
and requires some specific tools to be proven. 
We then compare the speed of convergence of the batch gradient descent and the stochastic gradient descent. In terms of optimization,
stochastic gradient is a poor algorithm in the sense that it converges much slower than the batch version, i.e it requires much more
iterations. Nevertheless, in terms of generalization, which is equivalent to the learning ability of our algorithm, stochastic
gradient descent is much better than the batch version. For the same number of examples given to the algorithm, the stochastic
one converges faster to a better minimum than the batch gradient descent.

The theory and the experimentations are explained in the pdf file. It is based on several research papers, mentionned in the 
bibliography, especially those of Leon Bottou.


						*** Research papers for the project ***


Most of the research papers used for the project were written by Leon Bottou and can be found on his Website : 

https://leon.bottou.org/


						*** Implementations *** 


Implementations were an important part of the project. We had to program some of the algorithms mentionned in Leon Bottou's papers
to underline different theoretical results. 

My fellow comrade make the part about K-Means algorithm while I coded the perceptron algorithm to perform classification and 
regression tasks.

The jupyter notebooks are to be found in the Implementations directory and contain detailed explanations about our experimentations 
and the theoretical results they illustrate.