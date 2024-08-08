# Topological Matter
Topological insulators and semimetals are a fascinating class of materials that have recently emerged as a prominent subject of study in condensed matter physics. They represent new phases of matter that possess unique properties at their surfaces, hinges, edges or corners, distinct from those in the bulk. This results ultimately from the underlying non-trivial topology of the electronic band structure rather than any specific material property.

These are some key questions that inform my research:
- How can we systematically classify different topological phases of matter, including topological insulators, superconductors, and semimetals?
- What are the most general experimental signatures of topological phases and their photonic analogs?

### Topological photonics
<details>
<summary>Read more</summary>
<br>
<img align="left" src="https://raw.githubusercontent.com/sachin4594/svaidya.github.io/master/images/weyl.png" width="300" style="margin: 20px">
<div style="text-align: justify"> 
In the last decade, many ideas from topological matter have been extended to other systems that host wave-like excitations (such as light propagating in photonic crystals or sound waves in acoustic metamaterials). I am interested in extending the theory of topological phases to photonic systems, and their finding their associated experimental signatures.
<br/><br/>
One part of my research has focussed on Weyl points. Weyl points are robust band degeneracies that occur in the momentum space of 3D periodic systems and are enforced by an integer topological charge known as the Chern number. In the photonic domain, Weyl points may enable the creation of large-volume single-mode lasing devices. Furthermore, they can mediate unique long-range interactions between embedded quantum emitters. However, due to fabrication challenges, experimental realization of photonic Weyl points at near-IR wavelengths has remained elusive. Our work on Weyl points addressed these challenges by employing a novel micro-printing technique to fabricate 3D photonic crystals that host Weyl points at mid- and near-infrared wavelengths [1, 2, 3].
<br/><br/>
More recently, we developed a complete classification of topological phases in photonic crystals under crystalline symmetries and proposed a design strategy based on this classification [4]. We also quantified the prevalence of various important topological phases in two-dimensional photonic crystals [5]. 
<br/><br/>

**References:** <br/>
[1] **Sachin Vaidya***, Jiho Noh*, Alexander Cerjan, Christina, Jörg, Georg von Freymann and Mikael C. Rechtsman, Observation of a charge-2 photonic Weyl point in the infrared, Physical Review Letters 125, 253902 (2020)
<br/><br/>
[2] Julian Schulz, **Sachin Vaidya** and Christina Jörg, Topological photonics in 3D micro-printed systems, APL Photonics 6, 080901 (2021)
<br/><br/>
[3] Christina Jörg*, **Sachin Vaidya***, Jiho Noh, Alexander Cerjan, Shyam Augustine, Georg von Freymann and Mikael C. Rechtsman, Observation of quadratic (charge-2) Weyl point splitting in near-infrared photonic crystals, Laser & Photonics Reviews 16, 2100452 (2022)
<br/><br/>
[4] **Sachin Vaidya**, Ali Ghorashi, Thomas Christensen, Mikael C. Rechtsman and Wladimir A.Benalcazar, Topological phases of photonic crystals under crystalline symmetries, Physical Review B 108, 085116 (2023)
<br/><br/>
[5] Ali Ghorashi, **Sachin Vaidya**, Mikael C. Rechtsman, Wladimir A. Benalcazar, Marin Soljačić, and Thomas Christensen, Physical Review Letters 133, 056602 (2024)
</details>


### Novel topological phases
<details>
<summary>Read more</summary>
<br>
The momentum space of lattice systems forms a manifold that is topologically equivalent to a torus, and the process of classifying wave functions over this manifold leads to various topological invariants. The following question naturally arises: what if the momentum space manifold was not a torus? In a recent work, we explored the consequences of changing the topology of this underlying manifold on the properties of quasiparticles that exist on them. In particular, we showed that Weyl fermions living on a non-orientable manifold have markedly different topological invariants describing them, leading to a range of unique properties [1].
<br/><br/>

In a different paper, we resolved a long-standing debate on whether the concept of electric polarization is meaningful in Chern insulators. Chern insulators are paradigmatic topological insulators known for exhibiting quantized Hall conductance even without a magnetic field. Due to their topological nature, electrons within these materials are fundamentally delocalized and resist forming compact wave packets, known as Wannier functions. The concept of electric polarization, which is pivotal in understanding insulating phases of matter, relies on the presence of compact electronic Wannier functions. Due to this, it has not been clear how to understand electric polarization in Chern insulators. In our work, we tackled this issue and showed that Chern insulators, and by extension, strong topological insulators, can indeed exhibit a physical response to spatial and temporal changes in electric polarization, accompanied by measurable quantities [2].
<br/><br/>

**References:** <br/>
[1] André Grossi e Fonseca*, **Sachin Vaidya***, Thomas Christensen, Mikael C. Rechtsman, Taylor L.
Hughes and Marin Soljačić, Weyl points on non-orientable manifolds, Physical Review Letters 132, 266601 (2024)
<br/><br/>
[2] **Sachin Vaidya**, Mikael C. Rechtsman and Wladimir A. Benalcazar, Polarization and weak topology in Chern insulators, Physical Review Letters 132, 116602 (2024)
</details>


# Nanophotonics
The field of nanophotonics focuses on the manipulation and control of light on the nanometer scale. The unique properties of light-matter interactions at these scales arise from the confinement of photons to dimensions smaller than the wavelength of light. This confinement leads to phenomena such as enhanced optical forces, strong light-matter coupling, and the ability to manipulate light in ways that are impossible with traditional optical components. Furthermore, nanophotonics holds promise for a wide range of applications, from telecommunications and information processing to sensing, imaging, and quantum computing.

Some key questions that inform my research:
- Can we find novel strategies for trapping and guiding light at the nanoscale to achieve strong light-matter coupling?
- What new functionalities can be achieved by combining nanophotonics with conventional medical imaging techniques?

### Bound States in the Continuum
<details>
<summary>Read more</summary>
<br>
<img align="right" img src="https://raw.githubusercontent.com/sachin4594/svaidya.github.io/master/images/BIC.png" width="325" style="margin: 20px">
<div style="text-align: justify"> 
Photonic crystals are lattices of dielectric materials, such as glasses or semiconductors, that enable fine control over the properties of light. They are known to possess band gaps, making them act as perfect mirrors for a range of frequencies. These band gaps have traditionally been utilized for trapping light to defects, creating one-dimensional waveguides and zero-dimensional nanocavities. However, the reliance on a band gap limits the choice of materials to those with a sufficiently high refractive index.
<br/><br/>

We proposed a new method for trapping light within nanocavities embedded in two-dimensional photonic crystals that lack band gaps. We demonstrated that it is possible to engineer the photonic crystal and nanocavity such that a symmetry mismatch with the photonic crystal's modes prohibits light within the cavity from leaking away. This state of light is an example of a "bound state in the continuum", which is a localized state that co-exists with a continuum of propagating states of the photonic crystal. Furthermore, we showed that such states can be utilized to create slow-light modes in complex photonic crystal fibers. Our work enables the construction of nanocavities within photonic crystals made of versatile, low-index materials like glasses and polymers.
<br/><br/>
</div>
</details>

### Nanophotonic Scintillators
<details>
<summary>Read more</summary>
<br>
<img align="right" img src="https://raw.githubusercontent.com/sachin4594/svaidya.github.io/master/images/BIC.png" width="325" style="margin: 20px">
<div style="text-align: justify"> 
Scintillators are materials that convert high-energy particles, such as X-rays, free electrons, or gamma rays, into optical photons through a complex cascade of processes. These materials are central to various modern imaging technologies, including diagnostic medical imaging and non-destructive testing. Integrating nanophotonics with scintillators represents a promising direction poised to advance several technologies by directly controlling and tailoring the light emission process. For instance, utilizing the Purcell effect can increase the rate of spontaneous emission, yielding significantly brighter scintillators. This enhancement would directly translate to reduced X-ray dosage in medical settings, thereby decreasing the risk of radiation exposure to patients. 
<br/><br/>

I am currently working towards demonstrating that bulk-patterned (volumetric), two-dimensional photonic crystal scintillators can exhibit significant emission enhancement while being several hundred microns thick.
<br/><br/>
</div>
</details>


# Classical and quantum nonlinear optics
Some key questions that inform my research:
- What new physical phenomena emerge from the interplay of topology, symmetry and interactions in nonlinear optical systems?
- How can we robustly control noise in quantum systems and generate non-classical states of light?
<details>
<summary>Read more</summary>
<br>
  empty
</details>

# Interpretable AI for physics
Current AI models, while capable of achieving high accuracies in various tasks, are fundamentally limited in terms of interpretability. In contrast, advancements in physics often rely on key insights derived from experimental observations or numerical data. Consequently, developing novel AI frameworks that align closely with scientific goals is crucial for leveraing AI's capabilities for fundamental discoveries. 

Some key questions that inform my research:
- How do we develop interpretable AI models that are closely aligned with scientific goals?
- What does a future that employs AI for physics experiments look like?
<details>
<summary>Read more</summary>
<br>
I'm interested in developing and applying two distinct strategies for enhancing interpretability: (1) Encouraging sparsity in conventional multi-layer perceptrons (MPs) that leads to compact and highly interpretable networks, well-suited for discovering phenomenological laws and modularity in scientific tasks. (2) Replacing weights with with learnable activation functions makes it possible to extract symbolic expressions for various scientific problems.
  
This architecture, known as 'Kolmogorov-Arnold Networks (KANs)', significantly outperforms MLPs in both accuracy and interpretability. As an example, we apply KANs to a problem in condensed matter physics, showing that these networks, when trained on numerical data, can derive exact symbolic expressions for phase transition boundaries between metallic and insulating states in disordered quantum systems.
</details>
