# investigation-of-the-non-Gaussianity-in-the-simulated-CMB-using-convolutional-neural-networks

Non-Gaussianity:
-----------------
Several models of the inflation predict a roughly perfect Gaussian primordial fluctutations which are generated by a single scalar quantum field in ground state. This is while there are alternative approaches to decribe the inflationary period which lead to the non-Gaussianity of the CMB.

From this point of view, detecting non-Gaussian patterns in the CMB radiation plays a crucial role in confining cosmological models.

Research goal:
---------------------
My primary aim in this research is to design a network which is able to indentify these patterns. 

Data source:
-------------
I used simulated data that are available here:
http://dc.zah.uni-heidelberg.de/elsnersim/q/s/fixed

A succinct description of research results:
---------------------------------------------
According to the mathematical background (which is provided in a pdf file in the repository), I assigned three different values to f_NL (0,500,-500) and applied Resnet18 as my convolutional neural network.

With the using of cross-validation technique, the network reached a maximum of about 99% in validation accuracy.  
