#SQUAD Book chapter

This project exemplifies the implementation of the Standardized Qualitative Analysis of Dynamics (SQUAD) method as defined in Di Cara *et al*, 2007 and later modified in Martínez-Sosa *et al*, 2013.

*CartoonNetwork.R* file defines the regulatory network comprising three nodes *A*,*B* and *C* shown in Figure 1 from the book Chapter in BoolNet format.

*SQUADTransformation.ipynb* file exemplifies the simulation of the regulatory network model defined in the *CartoonNetwork.R* file, first as a boolean regulatory network model, and then as a continuous regulatory network using the SQUAD method. 

*SQUAD_implementation.ipynb* contains a tutorial for implementing node perturbations with the SQUAD methodology. It presents the code used to make the figure 5.

*animation.gif* shows an animation of the figure 3 that allows to see the direction of the flow of the states of the network at different rotation angles.


**References**

Di Cara, A., Garg, A., De Micheli, G., Xenarios, I., & Mendoza, L. (2007). Dynamic simulation of regulatory networks using SQUAD. BMC Bioinformatics, 8(1), 462. http://doi.org/10.1186/1471-2105-8-462

Martínez-Sosa, P., & Mendoza, L. (2013). The regulatory network that controls the differentiation of T lymphocytes. BioSystems, 113(2), 96–103. http://doi.org/10.1016/j.biosystems.2013.05.007

