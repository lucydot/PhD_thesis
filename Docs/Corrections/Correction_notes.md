## Corrections - Defects and Distortions in hybrid halide perovskites (Lucy Whalley)

Note: page numbers outside of bracket refer to pages in the original manuscript. page numbers inside of bracket refer to pages in the corrected manuscript.

### Front matter  

*Ambiguity over who prepared Fig.2.3*

- p.8 (p.9): Clarified: Young-Kwang Jung prepared this figure rather than Aron Walsh

*If need to give values should use higher precision*

- p.17 (p.18): The values have been removed

### Ch1

*Refs needed for equations 1.5-1.9*

- p.27 (p.28): References have been added

*A more careful description of mobility should be given including discussion of the Drude model*

- p.30 (p.31): The description of mobility has been extended, including reference to the Drude model

### Ch3

*Section 3.2 on DFT lacks sufficient detail on most of the methods and theoretical concepts that underpin this work in this thesis and needs to be substantially rewritten after the candidate and properly refreshed her understanding. This includes description of the many electron schrodinger equation, Hartree-Fock and exchange, the Kohn-Sham equations, GGA, the HSE functional including range dependence, discussion of Bloch functions and reciprocal space and the PAW method.*

- Section 3.2 (Sections 3.2-3.4): Section 3.2 has been substantially rewritten. It has been expanded and split into three sections; quantum chemistry (The Schrodinger eqn / Hartree approximation / Hartree Fock approximation and exchange), density functional theory: basic concepts (The Hohenberg-Kohn theorems and Kohn-Sham formalism incl. KS equations), and DFT in practice (Exchange correlation functionals at LDA/GGA and hybrid level of theory (including range-dependent hybrids), Bloch functions, basis sets, pseudopotential construction (including an additional figure) and the PAW method).

*Eq. 3.2 should show that the many-body wavefunction is a function of the coordinates of all N electrons not just of them.*

- p.49 (p.50): Curly-bracket notation is used to show that the many-body wavefunction is a function of all N electron coordinates

*The right equation in Fig. 3.1 uses total energy E rather than single particle energy e_i*

- p.50 (p.52): The equation has been corrected to show the single particle energy on the RHS

*The discussion of Meta-GGA is too brief to be useful but may be omitted entirely since it is not used.*

- p.53 (p.58): Discussions of Meta-GGA and RPA omitted

*Misleading statement on growth conditions*

- p.61 (p.68): The statement on growth conditions has been removed

### Ch4

*Fig. 4.1 central panel is confusing. The dashed curves appear to have nothing to do with the second derivative.*

- p.71 (p.77): The central panel has been adjusted so that the curvature of the parabola more clearly decreases as the energy difference from band edge increases (where the curvature of the parabola is used to represent the second derivative)

*Eq. 4.11 is dimensionally inconsistent and does not specify at which point the second derivative is evaluated. Assume it is point i I believe the equation has errors in both the numerator and denominator. This equation was not derived (taken from literature) but there is no citation. It should be confirmed this equation is not used in the code.*

- p.74 (p.80): The numerator is correct and a reference to the derivation is provided in the main text of the thesis. The squared sign in the denominator was missing in the manuscript, but I can confirm it is present and correct in the `effmass` code.

*Also need to give expression for evaluation of dE/dk*

- p.74 (p.81): The description of the calculation method used for the transport effective mass has been extended

*Size of symbols in Fig. 4.6 and 4.7 very large and scale makes it difficult to see trend*

- p.81 (p.87/p.88): The size of Figures 4.6 and 4.7 have been increased so that the symbols are smaller in proportion to the scale of each axis and the overall trends can be seen more clearly.

### Ch5

*Need to explain where Eq. 5.1 comes from.*

- p.89 (p.96): Equation 5.1 has been split into multiple expressions (one for each term of the Hamiltonian). A short description of each sub-system is included and the number operator is introduced. Additional textbook references have been included.

*Eq. 5.2 seems inconsistent as k does not appear.* 

- p.89 (p.97): The dependance on k is removed due to assumptions in the model. This point has been highlighted in the text and two relevant references have been provided.

*‘long carrier lengths’ – meaning unclear*

- p.90 (p.98): 'long carrier lengths' has been reworded to 'long charge carrier diffusion lengths' and upper estimates for diffusion length and mobility are given from the literature.

*Include ref for displacement step size selected.*

- p.99: The displacement step size selected was selected in line with the literature and a reference has been included.

*Issue with x-axis symbol format in Fig. 5.3 and 5.5*

- p.95 (p.102/p.105): The x-axis symbol format has been fixed in Figures 5.3 and 5.5

*More detailed discussion of the idea of an excited polaron*

- p.97 (p.106): A paragraph outlining the concept of a "hot polaron" model, in contrast to the two temperature model for hot carrier cooling, has been included.

*Define valence and conduction band deformation potential*

- p.98 (p.105): The definition of deformation potential used for values in Table 5.4 is now specified in the table caption.

### Ch6

*Explain why this particular supercell expansion*

- p.104 (p.113): A statement has been included relating to elastic effects and the need for isotropic supercell expansions

*Missing delta in Eq. 6.1*

- p.105 (p.114): The delta has been included

*Where does eq.6.2 come from?* 

- p.106 (p.114): The approximations made to reach Eq. 6.2 (now Eq. 6.3) are outlined and a reference is included.

*More details of dielectric embedding approach needed.*

- p.108 (p.115): Subsection 6.2.4 has been added to the methods section: "Calculation procedure for the optically excited states"

*Some statements about valence when actually mean conduction*

- p.117 (p.126): 'valence' has been corrected to 'conduction' in the appropriate places.

*Hole capture -> hole emission*

- p.119 (p.127): hole capture has been corrected to electron capture, and a reference has been included.

### References

*Several cases of inconsistent journal name abbreviation which should be corrected (note not all identified in annotated pdf).*

- Journal name abbreviation is now consistent.
