---
layout: page
title: ""
mathjax: true
---

## Research Interests and Skills
My general research interest is exploring novel properties of electrons, as well as elementary excitations such as phonons, magnons, excitons, and plasmons, in quantum condensed matter systems. The systems I study include both toy models where analytical calculation with simple and empirical band theory can provide us insight into the underlying physics, and real materials or meta-materials for which first-principles simulations can be applied to achieve a more realistic description for predicting experiments or real-life situations. Particularly interesting topics to me are topology properties, electron-electron correlation, electron-phonon interactions, and possible interplay between them. 

My PhD study has enabled me aquire faithful knowledge in quantum mechanics, solid state physics, (topological) band theory, Green's function, and many-body perturbation theory. In my current postdoc training, I have learned first-principles methods for materials simulations and got familiar with popular computational packages. 

---

## Research Experiences
### Leading Projects
#### Topological phonons and electron-phonon interaction in RhSi. 
<!---
In this on-going project, I study phonon excitations and electron-phonon interaction in RhSi, using density functional perturbation theory implemented in Quantum ESPRESSO (QE) simulations package and Wannier interpolation as implemented in EPW code. RhSi is a uniquely interesting material which was reported to have topologically non-trivial
electronic structure and is believed to be very likely having topologically non-trivial phonons for its structural similarity to a family of topological phonon materials. From my calculated bulk phonon bands, I identify topologically nontrivial Weyl nodes at the Brillouin zone (BZ) center (Γ point) and corners (R point) with opposite chiralities, i.e. χ = 2 at Γ and χ = −2 at R. Due to ”bulk-boundary correspondence”, this feature implies the existence of topological surface phonon states that manifest as iso-frequency loops connecting the projections of Γ and R on the surface BZ. To confirm this, I calculate the band structure and phonon surface density of states of a slab model, and observe mig-gap phonon states that are highly localized on the surfaces of the slab. The dispersions of these topological phonons are chiral on two opposite surfaces. Moreover, I study electron-phonon (EP) coupling in this material and calculate the phonon self-energy, from which I find the coupling strength is particularly enhanced near phonon Weyl points. The underlying physics behind this is still in exploring. I am trying to understand whether the enhanced EP coupling is related to the non-trivial topology of electrons and phonons of RhSi. Furthermore, I plan to study EP interaction on surfaces as well using a slab model. To achieve this, I will try to use real-space format of wannierised EP coupling matrix from EPW code and then apply it to the slab model by Fourier transforming only the in-plane spatial dimension.
-->

#### Intrinsic magnetic damping in iron and its dependence on various factors. 
The motivation of this project was to optimize magnetic materials with low intrinsic magnon damping such that they can be utilized by our experimental collaborates to make hybrid-magnon quantum devices for coherent information processing. To achieve this, I started from a simple ferromagnetic material, the body-centered cubic iron (Fe). Theories have demonstrated the intrinsic magnon damping due to conduction electrons in metals is proportional to the electron density of states at the Fermi level (EDOS-FL) in low scattering limit. I stayed within this scope and studied the influence of phonon temperature, boron (B) doping and structure amorphization on EDOS-FL of Fe using first-principles calculations based on the density functional theory (DFT). The phonon temperature effect was considered by superimposing harmonic phonon modes with random phases and amplitudes according to classical statistics at different temperatures that makes the simulation cell disordered. The simulation cells for B doped Fe were constructed by cluster-expansion method which can determine symmetry-non-equivalent atomic configurations for each doping level. The amorphous Fe structure was constructed through a heating and quenching process by classical MD simulation using LAMMPS. Calculating all these structures, I found that phonon temperature does not change the EDOS-FL much. Doping B into crystal Fe reduces EDOS-FL wich an optimal doping level found to be 6.25%. The amorphous Fe had larger EDOS-FL than the crystal Fe. However, amorphous Fe doped with B was observed to have even lower EDOS-FL than the crystal Fe. My calculation results confirmed the key role played by B doping in reducing EDOS-FL, which is favored for low intrinsic magnetic damping. My results are also consistent with previous experimental works reporting that doping B or carbon (C) into ferromagnetic alloys can make the structure amorphous and reduces magnetic damping.

#### Coulomb engineering of plasmons in 2D materials. 
This project aimed for exploring opportunities to control plasmons in 2D materials via Coulomb engineering. Coulomb interactions in 2D materials are very susceptible to the surrounding environment, and can be easily tuned by varying dielectric substrates. I calculated plasmons on a reasonably parameterized 2D tight-binding model deposited on a structured dielectric substrate. The structured screening environment created locally “bright areas” (where the dielectric constant of the substrate is small) and “dark areas” (where the dielectric constant of the substrate is large) for plasmons, and therefore spatially modulated plasmon modes according to the substrate structure underneath. This observation motivated me to propose a Coulomb engineered plasmonic waveguide by creating an ”active plasmon channel” from structured substrate. This concept is fundamentally novel from traditional ways of manufacturing plasmonic waveguides by either shaping the activate material itself (like narrow ribbons) or by changing single-particle properties of the plasmon-hosting system (like applying gating voltage). The idea here is engineering many-body interactions in hosting material through the screening environment, without changing the hosting material itself. The entire scenario just relies on a pre-structured dielectric substrate on which we can deposit the hosting material.

#### Plasmons in topological insulators (TIs). 
The motivation of this project was to explore topological features in collective excitations of electrons, although single-electron properties of TIs have been extensively studied for many years and can be well described in independent-particle physics. Plasmons are collective oscillations of electron density rendered by electron-electron Coulomb interactions, which necessarily brings many-body effects into consideration. I calculated plasmonic excitations in various models of TIs including the Su-Schrieffer-Heeger (SSH) model in one-dimensional (1D) and two-dimensional (2D) spaces, 2D Haldane model, and 2D Kane-Mele (KM) model, using self-developed code based on the random phase approximation (RPA) in the real space. In the topologically non-trivial phase of all these TIs, I observed localized edge plasmons which originate from topological single-electron edge states. Moreover, these edge plasmons inherit some characteristic features from the underlying electronic structure, depending on the model symmetry. In the Haldane model where electron edge states are chiral due to the broken time-reversal (TR) symmetry, I found that edge plasmons are also chiral. In the KM model, the overall plasmon spectrum is TR symmetry, but each spin channel is chiral, resembling the quantum spin Hall effect for electrons. Despite many resemblances between edge plasmons and single-electron edge states, there are key differences. While topological electronic edge states can be well detached from bulk bands, edge plasmons always involve admixture of bulk electronic states through intrinsic dielectric screening. Therefore, edge plasmons in TIs are less robust against disorder than single-electron edge states. In additional, edge plasmons do not have pinned excitation energies as they sensitively depend on the Coulomb interactions. These differences reflect key distinctions between many-body excitations and independent-electron physics, even though they share many features in TIs due to the topology of the system.

### Collaboration Projects
#### Magnetic phase of Li2CoCl4. 
In this project, my experimental colleagues from Professor Daniel Shoemaker’s group fabricated the cobalt chain compound Li2CoCl4 and explored the magnetic phase of Co2+ ions. I collaborated by performing first-principles DFT calculations to find ground state magnetic configuration of Co2+ ions using a non-collinear setup with spin-orbit coupling (SOC) included. My DFT calculations predicted a ground state configuration of ferromagnetic cobalt chains with antiferromagnetic interactions between them, matching the interaction types of the zero-field antiferromagnetic structure found with neutron powder diffraction. Moreover, with spin-polarized calculation on this DFT ground state magnetic configuration, I predicted Co2+ to be in a high-spin (spin-3/2) state. The prediction matched their high-temperature susceptibility data measured from experiments.

#### Surface plasmon enhanced fluorescence. 
In this project, my experimental collaborators from Professor Wei Wu’s group fabricated a nano-gap structure consisting of pairs of collapsible metallic nanofingers with a dielectric spacing layer of tunable gap size. Largely enhanced Raman and fluorescence signal were observed for molecules placed at plasmonic hotspots due to strong local field enhancement, which were however, showing signal maxima at different gap sizes. My contribution was to analyze experimental data and provide physical understanding behind their observation, which was complicated due the co-existing effects of field enhancement and quenching that are both affecting the fluorescence signal. I normalized the fluorescence data by the simultaneously measured Raman signal, such that the field enhancement effect was effectively eliminated. Then, I proposed a quantum mechanical model to explain quenching mechanisms, which nicely accounted for the experimental results. Particularly, in my model, quantum tunneling effects of electrons played an important role, which can also explain different quantitative behaviors observed when different dielectric materials were used for the spacing layer.