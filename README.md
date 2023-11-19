# IP_EA_deltaSCF
Ionization potential, electron affinity, and delta SCF for small organic molecules selected from the ANI-1 data set. Properties are calculated with 24 different density functional approximations as well as CCSD(T).

Contents of this repository include:

* ad3165-23dfa.csv - predictions of electron affinity, ionization potential, and delta scf for 3165 small organic molecules; predictions are provided for 24 different functional approximations as well as CCSD(T)

* geo_AD-3165 - folder of 3165 .xyz files detailing the molecular configurations corresponding to the predictions of quantum chemical properties; the names of these files correspond to the first column of ad3165-23dfa.csv

* organic_ip_data.csv - a subselection of the data in ad3165-23dfa.csv; this table contains ionization potential predictions by five levels of theory: CCSD(T), PBE0_DH, PBE0, PBE, and BLYP; all molecular configurations for which all of these computations converged are included

* organic_molecules.xyz - extended .xyz file with molecular configurations corresponding to organic_ip_data.csv; the index column of organic_ip_data.csv indicates which molecular configuration the predictions of ip correspond to


# References

For a description of the density functional approximations used to generate the data along with related computational details, see:

C. Duan, S. Chen, M. G. Taylor, F. Liu, and H. J. Kulik, “Machine learning to tame divergent density functional approximations: a new path to consensus materials design principles,” Chem. Sci. 12, 13021–13036 (2021). [http://dx.doi.org/10.1039/D1SC03701C](http://dx.doi.org/10.1039/D1SC03701C)

For more information on the ANI-1 dataset, see:

J. Smith, O. Isayev, and A. Roitberg, “A data set of 20 million calculated off-equilibrium conformations for organic molecules,” Scientific Data 4 (2017). [http://dx.doi.org/10.1038/sdata.2017.193] (http://dx.doi.org/10.1038/sdata.2017.193)

For a description of how molecular configurations were subselected from the ANI-1 dataset, see:

C. Duan, F. Liu, A. Nandy, and H. J. Kulik, “Data-driven approaches can overcome the cost–accuracy trade-off in multireference diagnostics,” Journal of Chemical Theory and Computation 16, 4373–4387 (2020). [http://dx.doi.org/10.1021/acs.jctc.0c00358] (http://dx.doi.org/10.1021/acs.jctc.0c00358)
