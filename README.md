
**Photoluminescence Quenching Simulator (`PLQ-Sim`)** is a user-friendly software to study the photoexcited state dynamics at the interface between two organic semiconductors forming a blend, an electron donor (D), and an electron acceptor (A). Its main function is to provide substantial information on the photophysical processes relevant to organic photovoltaic and photothermal devices, such as charge transfer state formation and subsequent free charge generation or exciton recombination.

The PL effect corresponds to the light emission from the radiative exciton recombination after photon absorption in the material. Depending on the material combination, PL can be quenched due to interfacial charge transfer processes.

If the excitation wavelength corresponds to donor’s main absorption band, the PL quenching efficiency of the donor excitonic luminescence ($PLQ_{D}$) is given by:

$$ PLQ_{D}(\\%) = 1 - \dfrac{PL\left[D/A\right]}{PL\left[D\right]} $$

If the excitation wavelength corresponds to acceptor’s main absorption band, the PL quenching efficiency of the acceptor excitonic luminescence ($PLQ_{A}$) is given by:

$$ PLQ_{A}(\\%) = 1 - \dfrac{PL\left[D/A\right]}{PL\left[A\right]} $$

The figure below illustrates PL measurements using a fluorimeter after selective excitation of the donor or acceptor.

<p align="center">  
  <img width="500em" src="https://github.com/NanoCalc/PLQ-Sim/assets/129612477/2570f6a4-6107-4ac9-a93f-868508b31b41" />
</p>

The measurement of PL is a powerful tool to investigate photoluminescence quenching in D/A blends. However, the application of this experimental method does not allow to study the details of the processes that contribute to the quenching.  Deep knowledge of the excited state dynamics at D/A interfaces by kinetic modeling is fundamental to tailoring the properties of the blend aiming at different applications.

Our research group developed a theory to calculate $PLQ_{D}$ and $PLQ_{A}$ based on a kinetic model that considers all possibilities involved in exciton dynamics.⁠ To popularize this model, we developed a free license software, PLQ-Sim, that is easy to handle and provides key features to characterize the system.

Detailed instructions for using PLQ-Sim can be consulted in our published article:

**PLQ−Sim: A Computational Tool for Simulating Photoluminescence Quenching Dynamics in Organic Donor/Acceptor Blends** [article page](https://doi.org/10.1016/j.cpc.2023.109015)

This article is open access: you can get the preprint [here](https://github.com/NanoCalc/PLQ-Sim/blob/main/PLQ-Sim.pdf).

Earlier articles that form the basis for the current theory used in the program:

**Kinetic model for photoluminescence quenching by selective excitation of D/A blends: implications for charge separation in fullerene and non-fullerene organic solar cells, J. Mater. Chem. C, 2020, 8, 8755-8769.** [article page](https://doi.org/10.1039/D0TC01077D)

**Conditions for efficient charge generation preceded by energy transfer process in non-fullerene organic solar cells, J. Mater. Chem. A, 2021, 9, 27568-27585.** [article page](https://doi.org/10.1039/D1TA06698F)

To perform the simulation, basic information about the materials must be provided as input parameters (like the energy levels, dielectric constant, reorganization energy, and singlet exciton lifetime, for instance). If some information of the analyzed system is missing, default values for the class of material studied can be used. After running the simulation, the rates of the physical processes involved in the charge dynamics at the D/A interface (like the charge transfer or charge recombination rates, for instance) are provided as output. This information is crucial to characterize the photophysical process as a whole and propose solutions for system optimizations.

**The software binaries can be downloaded for the following operating systems:**  [*Unix-like systems (Linux)*](https://github.com/NanoCalc/PLQ-Sim/releases/download/1.0-beta/PLQSim-Unix.zip), [*Windows*](https://github.com/NanoCalc/PLQ-Sim/releases/download/1.0-beta/PLQSim-Windows.zip) and [*macOS*](https://github.com/NanoCalc/PLQ-Sim/releases/download/1.0-beta/PLQSim-MacOS.zip).

Program interface:

<p align="center">  
  <img width="500em" src="https://github.com/NanoCalc/PLQ-Sim/assets/129612477/8af3706e-1f6e-4814-8ebe-63ece4360b8a" />
</p>

Input example for PBDB-TF/ITIC blend:

<p align="center">  
  <img width="500em" src="https://github.com/NanoCalc/PLQ-Sim/assets/129612477/dc95bc6a-2e4f-4ca4-9e83-ed968da57ce8" />
</p> 

Demonstration of part of the generated output for PBDB-TF/ITIC blend:

<p align="center">  
  $PLQ_{D}$ = 84%
</p>
<p align="center">  
  <img width="500em" src="https://github.com/NanoCalc/PLQ-Sim/assets/129612477/0c341d81-f431-45ec-8bd5-df64bdbf0f04" />
</p>
<p align="center">  
  Energy−level representation and transfer rates for the electron dynamics calculated by PLQ-Sim.
</p>

`PLQ-Sim` can also be used online on our website [nanocalc.org](https://nanocalc.org).

# Authors
* [Leandro Benatto](https://orcid.org/0000-0001-9976-3574)<sup>a,b</sup>
* [Graziâni Candiotto](https://orcid.org/0000-0001-6755-660X)<sup>a</sup>
* [Omar Mesquita](https://orcid.org/0000-0002-6656-5683)<sup>a</sup>
* [Lucimara S. Roman](https://orcid.org/0000-0001-6567-5920)<sup>b</sup>
* [Rodrigo B. Capaz](https://orcid.org/0000-0001-5770-5026)<sup>a,c</sup>
* [Marlus Koehler](https://orcid.org/0000-0001-9935-5060)<sup>b</sup>

# Institutions
<sup>a</sup>Institute of  Physics, Federal University of Rio de Janeiro, 21941-909, Rio de Janeiro-RJ, Brazil.<br>
<sup>b</sup>Department of Physics, Federal University of Paraná, 81531-980, Curitiba-PR, Brazil.<br>
<sup>c</sup>Brazilian Nanotechnology National Laboratory (LNNano), Brazilian Center for Research in Energy and Materials (CNPEM), 13083-100, Campinas- SP, Brazil.<br/>

# Developers
* [Leandro Benatto](https://github.com/LeandroBenatto)
* [Omar Mesquita](https://github.com/OmarMesqq)
* [Graziâni Candiotto](https://github.com/gcandiotto)

# Data Sample

# Spectral Data

# Acknowledgments
The authors acknowledge financial support from CNPq (grant 381113/2021-3) and LCNano/SisNANO 2.0 (grant 442591/2019-5), INCT - Carbon Nanomaterials and INCT - Materials Informatics. L.B. (grant E-26/202.091/2022 process 277806), O.M. (grant E-26/200.729/2023 process 285493) and G.C. (grant E-26/200.627/2022 and E-26/210.391/2022 process 271814) are greatfully for financial support from FAPERJ. The authors also acknowledge the computational support of Núcleo Avançado de Computação de Alto Desempenho (NACAD/COPPE/UFRJ), Sistema Nacional de Processamento de Alto Desempenho (SINAPAD) and Centro Nacional de Processamento de Alto Desempenho em São Paulo (CENAPAD-SP) and technical support of SMMOL - solutions in functionalyzed materials.

# How to cite PLQ-Sim software

# Cited by

Papers that recently cited `PLQ-Sim` software are shown below.

