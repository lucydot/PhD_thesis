Five Carrier Capture Questions

Ordered from "most pressing" to "least pressing"

1. Does the potential energy surface include an energy shift dependent on the fermi level - for example, if the fermi energy of the system is at 0.7eV above the VBM would I shift the negative PES down by 0.7eV (and leave the neutral PES unchanged)?

2. The volume I calculate for a 197 atom MAPI supercell is 4E-27 m^3 (17*17*13 Angstrom). The volume in the DX-centre example online is 4.72E-21 m^3 - it does not make sense to me how they could be orders of magnitude different.

3. The values for the capture coefficient in the plot (captcoeff.pdf) and in the csv file (capt_coeff.csv), both generated using GetRate.jl, are many orders of magnitude different (~10^-15 and ~10^-31 respectively) - are they in different units / different definitions?

4. In the Alkauskas paper there is C and C tilda (the "actual" capture coefficient) - does the code calculate C? If it calculates C, how is the scaling factor calculated? (I cannot see mention of it in the anharmonicity paper)

5. I have given the neutral and negative defects a degeneracy of 1 as only these two atoms are involved with bonding (there are not other equivalent iodines to consider) - however there might be an electronic degeneracy which I should include? 