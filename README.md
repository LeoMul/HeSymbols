# HeSymbols

The Hamiltonian for a He-like system is,

$$
\mathcal{H} = -\frac{1}{2} \left(\nabla^2_1 + \nabla^2_2 \right) - \frac{Z}{r_1}- \frac{Z}{r_2} + \frac{1}{r_{12}},
$$

in Hartree atomic units. 

We use symbolic methods (SymPy) (and some numerical optimization from SciPy) to calculate variational wave functions for the ground-state of this hamiltonian. 

This was orignally to check some results for my thesis (which didn't make the cut), but I was particularly surprised by the results in notebooks 1 and 2 where I could calculate six dimensional integrals completely analytically. 

In notebook 3 we introduce the Hylleraas coordinate system, and these reduce to three dimensional integrals. While complex - these integrals remain doable with horrible closed forms - but the numerical optimization at the end obtains the results of [Chandrasekhar (1944)](https://ui.adsabs.harvard.edu/abs/1944ApJ...100..176C/abstract) for the $Z=1$ case.

Notebook 1 is derived in many books and particularly in Griffiths' Quantum Mechanics. Notebook 2 is derived in Prob. 8.26 of this book also, in a different and probably more explicit closed form. I may update it to get this closed form.

The purpose of this repository is to demonstrate the power of combined Symbolic and numerical calculation in a computational setting, and I feel an exercise such as this will  become common place certainly in the post-graduate classroom, and I suspect the under-graduate classroom. This is actually where I first learned how to use symbolic calculators when acting as a teaching assitant for an UG classical mechanics course in my PhD. 