**Photoluminescence Quenching Simulator (`PLQ-Sim`)** is a user-friendly software to study the photoexcited state dynamics at the interface between two organic semiconductors forming a blend, an electron donor (D), and an electron acceptor (A). Its main function is to provide substantial information on the photophysical processes relevant to organic photovoltaic and photothermal devices, such as charge transfer state formation and subsequent free charge generation or exciton recombination.

The PL effect corresponds to the light emission from the radiative exciton recombination after photon absorption in the material. Depending on the material combination, PL can be quenched due to interfacial charge transfer processes.

If the excitation wavelength corresponds to donor’s main absorption band, the PL quenching efficiency of the donor excitonic luminescence ($PLQ_{D}$) is given by:

$$ PLQ_{D}(\\%) = 1 - \dfrac{PL\left[D/A\right]}{PL\left[D\right]} $$

If the excitation wavelength corresponds to acceptor’s main absorption band, the PL quenching efficiency of the acceptor excitonic luminescence ($PLQ_{A}$) is given by:

$$ PLQ_{A}(\\%) = 1 - \dfrac{PL\left[D/A\right]}{PL\left[A\right]} $$

The measurement of PL is a powerful tool to investigate photoluminescence quenching in D/A blends. However, the application of this experimental method does not allow to study the details of the processes that contribute to the quenching.  Deep knowledge of the excited state dynamics at D/A interfaces by kinetic modeling is fundamental to tailoring the properties of the blend aiming at different applications.

Our research group developed a theory to calculate $PLQ_{D}$ and $PLQ_{A}$ based on a kinetic model that considers all possibilities involved in exciton dissociation.⁠ 

[Kinetic model for photoluminescence quenching by selective excitation of D/A blends: implications for charge separation in fullerene and non-fullerene organic solar cells, J. Mater. Chem. C, 2020,8, 8755-8769.](https://doi.org/10.1039/D0TC01077D)

[Conditions for efficient charge generation preceded by energy transfer process in non-fullerene organic solar cells, J. Mater. Chem. A, 2021,9, 27568-27585.](https://doi.org/10.1039/D1TA06698F)

We believe that this model can be very helpful for research groups interested in the dynamics of charge generation or exciton recombination induced by light excitation of D/A blends. To popularize this model, we developed a free license software, Photoluminescence Quenching Simulator (PLQ-Sim), that is easy to handle and provides key features to characterize the system. To perform the simulation, basic information about the materials must be provided as input parameters (like the energy levels, dielectric constant, reorganization energy, and singlet exciton lifetime, for instance). If some information of the analyzed system is missing, default values for the class of material studied can be used. After running the simulation, the rates of the physical processes involved in the charge dynamics at the D/A interface (like the charge transfer or charge recombination rates, for instance) are provided as output. This information is crucial to characterize the photophysical process as a whole and propose solutions for system optimizations.
