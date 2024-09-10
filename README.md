# H-Pd-V-systems

includes data on H induced segregation of V atoms in Pd/V surfaces of the paper 

# The tendency of V segregation in Pd/V(110) and Pd/V(100) surfaces induced by H adsorption
Marianne A. Palmero , Koji Shimizu , Hiroshi Nakanishi , Satoshi Watanabe and Allan Abraham B. Padama

https://doi.org/10.1088/1402-4896/ad3f88

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Abstract
This study employs density functional theory-based calculations to investigate the tendency of V atom segregation in Pd/V(100) and Pd/V(110) surfaces upon adsorption of H at varying coverage (0.25, 0.50, 0.75, and 1.0 ML). Geometric, energetic, and electronic structure analyses were performed to elucidate the stability of H on the surfaces, the V atoms segregation tendency, and the interactions of atoms in the systems. By calculating the relative energies, we found that Pd atoms will favor residing in the topmost layer of pristine Pd/V. Segregation of V atom in pristine Pd/V(100) is more endothermic than in Pd/V(110). For H-Pd/V systems, a tendency of V segregation was observed for 0.50–1.0 ML H coverage on Pd/V(110). V atom segregation was not predicted in H-Pd/V(100). Due to the more endothermic V atom segregation process in pristine (100) than in (110) facet, a larger energy is necessary to induce V segregation by H adsorption in (100). The adsorption energies, charge density difference distributions, and density of states revealed the stronger H-V interaction compared to H-Pd interaction. Hence, H adsorption stabilizes the V atoms in the topmost layers and could induce V segregation in the surface.


## Installation

You can download the data used in this study by cloning the git repository:
   ```sh
   git clone {LINK TO REPO}
   ```

[//]: # (To install the required packages, use)

[//]: # (   ```sh)

[//]: # (   pip install -r requirement.txt)

[//]: # (   ```)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Computational Details (DFT)
> **Software**: Quantum Espresso ver. 6.5
>
> **Pseudopotentials**: V.pbe-spnl-kjpaw_psl.1.0.0.UPF, Pd.pbe-n-kjpaw_psl.1.0.0.UPF, H.pbe-kjpaw_psl.1.0.0.UPF
>
> **Kpoints**: 6 x 6 x 1 Monkhorst-Pack k-points mesh
>
> **Energy Cutoff**: 550 eV
>
> **Force Convergence Threshold**: 0.01 eV/Å
>
> **V Slab Model**:  2x2x6 supercell of the (100) and (110) facet, with 15 Å vacuum layer
>
> **Adsorbate considered in this study**: H
>
> **Adsorption sites considered in this study**: top(t), bridge(b), hollow(h)

## Columns Description (csv file)
> **surface**: type of surface, Pd/V(110) or Pd/V(111)
>
> **configuration**: surface configuration (the integers denote the number of Pd atoms per atomic layer, in which, the first integer corresponds to the topmost layer)
>
> **ΔE_Pd/V (eV)**: relative total energies of pristine Pd/V systems
>
> **ΔE_0.25HPd/V (eV)**: relative total energies of 0.25H-Pd/V systems
>
> **ΔE_0.5HPd/V (eV)**: relative total energies of 0.5H-Pd/V systems
>
> **ΔE_0.75HPd/V (eV)**: relative total energies of 0.75H-Pd/V systems
>
> **ΔE_1.0HPd/V (eV)**: relative total energies of 1.0H-Pd/V systems



<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## Citation
Palmero, M. A., Shimizu, K., Nakanishi, H., Watanabe, S., & Padama, A. A. B. (2024). The tendency of V segregation in Pd/V (110) and Pd/V (100) surfaces induced by H adsorption. Physica Scripta, 99(6), 065933.
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Email: abpadama@up.edu.ph

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This work is primarily funded by the Department of Science and Technology - Philippine Council for Industry, Energy and Emerging Technology Research and Development (DOST-PCIEERD) with Project No. 10128, 2022 (Project Title: Designing High Entropy Alloy Surfaces for Catalytic Applications using Atomistic Calculations and Materials Informatics Investigations (cHEApp)). This project is under the East Asia Science and Innovation Area Joint Research Program (e-ASIA JRP) with the title ‘Computational Design of High Entropy Alloys for Catalyst and BaTtery Applications’ (ACT). This research was carried out using the computing facilities of the Institute of Mathematical Sciences and Physics, University of the Philippines Los Banos, the Nakanishi Lab of the National Institute of Technology, Akashi College, Japan, and the Computing and Archiving Research Environment (COARE) facility of the Department of Science and Technology-Advanced Science and Technology Institute (DOST-ASTI) of the Philippines.
<p align="right">(<a href="#readme-top">back to top</a>)</p>
