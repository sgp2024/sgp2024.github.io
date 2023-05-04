---
title: "Program"
layout: "program"
type: "page"
menu: program


speakers: 
  

graduateSchoolCourses:
- title: Functional Correspondence from Discrete Geometry to Learning
  teaser: /images/school-discrete.png
  speakers:
    - name: Riccardo Marin 
      affiliation: University of Tuebingen
    - name: Emanuele Rodola
      affiliation: GLADIA
  abstract:
     Geometry processing is a vital component for solving 3D shape-matching problems that have significant relevance in enabling various downstream tasks like artistic designs, CAD modeling, and medical analysis. With the advent of data-driven solutions, flexible alignment techniques have become essential tools to unleash the potential of deep learning methods. This tutorial introduces the Functional Maps paradigm, one of the main frameworks for the past decade. We will explain the main concepts of this elegant and flexible framework on graphs, and then develop the necessary tools for triangular mesh cases. We will review the crucial steps of this long-standing literature, from its inception to the advent of geometric deep learning. Additionally, we will highlight the latest and most promising research directions, giving participants a comprehensive understanding of the current state-of-the-art in this field.  
      
- title: Hands-On Introduction to FEM in Python
  teaser: /images/school-Python.png
  speakers:
    - name: Teseo Schneider
      affiliation: University of Victoria
  abstract:
      The numerical solution of partial differential equations (PDEs) is ubiquitous in computer graphics and engineering applications, ranging from the computation of UV maps and skinning weights to the simulation of elastic deformations, fluids, and light scattering. The finite element method (FEM) is the most commonly used discretization of PDEs due to its generality and rich selection of off-the-shelf commercial implementations. In this course, we will implement a FE solver in 1D for the Laplace equation from scratch using only Numpy. We will briefly derive the necessary theory and quickly move into live coding the solver. At the end of the course, you will have a basic applied understanding of how the FEM works and how to extend the current code to higher dimensions and more complicated physics. 

- title: Computational Design of Deployable Structures
  teaser: /images/school-structures.png
  speakers:
    - name: Julian Panetta
      affiliation: UCDavis
  abstract:
    Structures that transform from compact configurations (which are simpler to manufacture and transport) to 3D shapes with specific forms and functions have important advantages for applications like emergency shelters, temporary event spaces, medical devices, and satellite antennas. However, designing such structures is difficult, involving interesting technical challenges like controlling the highly nonlinear large-deformation behavior of elastic beam and membrane structures. This course presents computational techniques for tackling inverse design problems in this space. It will cover shape optimization using differentiable physics simulation and show various strategies for accelerating these optimization algorithms. It will also introduce two-scale design algorithms, where the low-level details of the physical system are abstracted using homogenization to obtain a coarsened design problem that can be solved robustly by traditional computer graphics techniques like surface parametrization algorithms. Then the coarsened solution is "de-homogenized" to a full-scale structure and fine-tuned with shape optimization.

- title: A quick journey into geometry processing
  teaser: /images/school-journey.png
  speakers:
    - name: Bruno Levy
      affiliation: Inria
  abstract:
    This course is a gentle introduction to the set of notions useful in geometry processing that  I consider as the "minimal toolbox". I will illustrate the different notions with tips and tricks on how to efficiently implement them in a computer. Code and demos related to the notions that I'll present is available in Geogram (https://github.com/BrunoLevy/geogram) and Graphite (https://github.com/BrunoLevy/GraphiteThree)
    
- title: Connecting Language to 3D
  teaser: /images/school-language.png
  speakers:
    - name : Angel Chang
      affiliation: Simon Fraser University
  abstract:
    In this tutorial, we will cover recent developments in connecting language to 3D. We will discuss components in multimodal models for language and 3D data. Then we will cover applications such as localizing and describing objects in 3D scenes, and text-to-3D shape and scene generation. We will conclude with open research challenges and opportunities in this emerging research direction.


- title: Hexmesh generation and processing
  teaser: /images/school-hexmeshing.png
  speakers:
    - name: Gianmarco Cherchi 
      affiliation: University of Cagliari
    - name: Marco Livesu
      affiliation: IMATI
  abstract: 
    Hexahedral meshes are a prominent volumetric mesh representation. They are largely used as computational domains for the resolution of partial differential equations for physically based simulation, making them a core ingredient of many software tools used by the automobile, naval, aerospace, medical, and geological industries, as well as for many applications in Computer Graphics and Animation. In academic research and industry, the algorithmic generation and processing of hexahedral meshes have been studied for more than 30 years now. In this course, we will introduce the topic of hexahedral meshes and focus on the most relevant techniques for hexahedral mesh generation in Computer Graphics. For each technique, we will highlight capabilities and limitations, also pointing out the associated unsolved challenges. The required background, pertaining to geometrical as well as combinatorial aspects, will be introduced along the way.

- title: Dive into Neural Implicit-Explicit 3D Representations and their Applications
  teaser: /images/school-neural.png
  speakers: 
    - name: Songyou Peng
      affiliation:  ETH Zurich & MPI
  abstract:
    In this lecture talk, we will delve into the fascinating world of neural implicit-explicit 3D representations from a computer vision perspective. Beginning with the basics of explicit, implicit, and hybrid 3D scene representations, we will establish a foundation for understanding how these representations contribute to the field of 3D computer vision. We will then explore the recent evolution of hybrid implicit-explicit 3D representations in 3D reconstruction, neural rendering, and visual SLAM, discussing seminal works that have significantly advanced the state-of-the-art. In light of the recent hype surrounding ChatGPT, we will also briefly examine how large language models can be combined with implicit and explicit representations to enable new possibilities and innovative solutions in computer vision research
  
- title: Topology-Aware Reconstruction
  teaser: /images/school-topology.png
  speakers:
    - name: Tao Ju
      affiliation: Washington University in St. Louis
  abstract:
    Surface reconstruction from raw and imperfect inputs often results in shapes containing unwanted topological features, such as islands, handles, and voids. These errors are detrimental to downstream geometric processing tasks such as simplification, parameterization, and simulation. Topological errors can either be removed after the shape has been reconstructed (known as topological repair) or prevented during reconstruction by imposing topological constraints. This course will introduce fundamental concepts of topology that are relevant to surface reconstruction, review existing methods for topology repair and topology-constrained reconstruction, and describe several selected methods in detail. The course will end with a discussion of open problems in this area that await future research.
                
- title: Geometry Processing with Implicit Surfaces
  teaser: /images/school-implicit.png
  speakers:
    - name: David M. Palmer
      affiliation: MIT
  abstract:
    The recent popularity of neural implicit surfaces has renewed interest in implicit representations of geometry. In this session, we will dive into the world of implicit surfaces, both classical and neural. First, we will look at the use of implicit surfaces in surface reconstruction from point clouds. We will explore how a classical method, Poisson surface reconstruction, has recently been reinterpreted in a Gaussian process framework. Then we will take a look at recent neural implicit methods for surface reconstruction and the architecture and regularization choices they make. We will take a brief detour to look at NeRF and its descendants and their relationship to neural implicit models. The success of neural implicit representations has driven an interest in building a complete geometry processing pipeline around these representations. We will look at some attempts in this direction and conclude with some reflections about the future of the field.           
                
paperSessions: 
 
---  


<!-- 

The complete program schedule can be downloaded [here.](/images/SGP_2022_Program.pdf) (The file with timestamp 2022-06-20 09:00:00 is the current one)

paperUSB: https://cloud.fraunhofer.at/s/sY2mezd4NgRRoPM/download/USB-SGP2021.zip
paperURL: https://diglib.eg.org/handle/10.2312/2633079     

        affiliation: Università degli Studi di Cagliari   
      - name: Marco Livesu
        affiliation: IMATI
        

    teaser: /images/default_thumbnail.jpg

    abstract: Hexahedral meshes are a prominent volumetric mesh representation. They are largely used as computational domains for the resolution of partial differential equations for physically based simulation, making them a core ingredient of many software tools used by the automobile, naval, aerospace, medical, and geological industries, as well as for many applications in Computer Graphics and Animation. In academic research and industry, the algorithmic generation and processing of hexahedral meshes have been studied for more than 30 years now. In this course, we will introduce the topic of hexahedral meshes and focus on the most relevant techniques for hexahedral mesh generation in Computer Graphics. For each technique, we will highlight capabilities and limitations, also pointing out the associated unsolved challenges. The required background, pertaining to geometrical as well as combinatorial aspects, will be introduced along the way.
    
    

speakers: 
- name: Angela Dai
    url: https://www.professoren.tum.de/dai-angela
    affiliation: Technical University of Munich
    title: "Towards Structured Geometric Understanding for 3D Perception"
    abstract: "Semantic perception of 3D environments has seen remarkable advances in recent years, with a significant focus on object-based understanding. We propose to learn structured, intermediary representations, such as object parts, in order to provide a robust understanding of diverse 3D geometric structures from observations of real-world environments. This can enable more effective geometric reconstruction of objects in 3D scenes, enabling inter- and intra-object reasoning, as well as establish efficient structured representations for reconstruction and tracking of objects undergoing complex deformations."
    portrait: /images/Dai.jpg
  - name: Ligang Liu
    url: http://staff.ustc.edu.cn/~lgliu/
    affiliation: University of Science and Technology of China
    title: "Computational 3D Visual Art Design"
    abstract: "3D visual arts are highly diverse, including sculpture, architecture, ceramics, etc., in our lives.  Traditionally, artists use their rich imagination and experience to design 3D objects to give the audience a memorable experience. The design process takes a lot of trial and error, so it is often very time-consuming. It has attracted the attention of many researchers in the community of geometry processing and computer graphics, proposing various algorithms to simplify the initial complicated design process and help artists quickly realize the art in their minds. Moreover, the advent of digital modeling and 3D printing enables artists to create more complex 3D visual artworks.  In this talk, we will show a few interesting 3D visual art works and propose automatic methods to solve various problems in the design process of these art works.  From these examples, we reveal the close connection between geometry processing techniques and various 3D visual art design problems. Moreover, we will discuss about the current research trends and provide an outlook for future research directions and solutions."
    portrait: /images/Liu.png     
  - name: Caitlin Mueller
    url: http://www.caitlinmueller.com/
    affiliation: MIT Architecture
    title: "Geometry for design and construction of high-performance architecture"
    abstract: "Design and construction in the built environment present significant challenges and opportunities for impact: Buildings contribute to about 40% of global carbon emissions through their materials and operations, often due to inefficiencies stemming from a lack of integration between architectural design, engineering, and construction processes.  While this disconnect has been critiqued for decades, today's emerging techniques in computation, and in particular, geometry, can allow for a new layer of interdisciplinary communication and collaboration that transforms traditional workflows and empowers novel visual languages for high-performance architecture.  In this talk, Mueller will share recent work that contributes to this goal, demonstrating new techniques for computational design that integrate engineering principles and sustainability goals without overriding creative autonomy, and new fabrication methods that can materialize efficient geometries economically.  In particular, the talk will demonstrate how techniques developed in geometry processing and related fields can empower significant innovation in architectural domains, and will propose emerging problem spaces and applications for future geometry research."  
    portrait: /images/Mueller.png      
  - name: Daniele Panozzo
    url: https://cims.nyu.edu/gcl/daniele.html
    affiliation: New York University
    title: "Robust Geometry Processing for Physical Simulation"
    abstract: "The numerical solution of partial differential equations (PDE) is ubiquitously used for physical simulation in scientific computing, computer graphics, and engineering. Ideally, a PDE solver should be opaque: the user provides as input the domain boundary, boundary conditions, and the governing equations, and the code returns an evaluator that can compute the value of the solution at any point of the input domain. This is surprisingly far from being the case for all existing open-source or commercial software, despite the research efforts in this direction and the large academic and industrial interest. To a large extent, this is due to lack of robustness and generality in the geometry processing algorithms used to convert raw geometrical data into a format suitable for a PDE solver. I will discuss the limitations of the current state of the art, and present a proposal for an integrated pipeline, considering data acquisition, meshing, basis design, and numerical optimization as a single challenge, where tradeoffs can be made between different phases to increase automation and efficiency. I will demonstrate that this integrated approach offers many advantages, while opening exciting new geometry processing challenges, and that a fully opaque meshing and analysis solution is already possible for heat transfer and elasticity problems with contact. I will present a set of applications enabled by this approach in reinforcement learning for robotics, force measurements in biology, shape design in mechanical engineering, stress estimation in biomechanics, and simulation of deformable objects in graphics."
    portrait: /images/Panozzo.jpg

    
    
paperSessions: 
 - name: MODELING & MAPPING
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Harmonic Shape Interpolation on Multiply-connected Domains"
        authors:
          - name: Dongbo Shi
          - name: Renjie Chen
      - title: "Localized Shape Modelling with Global Coherence: An Inverse Spectral Approach"
        authors: 
          - name: Marco Pegoraro
          - name: Simone Melzi
          - name: Umberto Castellani, Riccardo Marin, Emanuele Rodola
          - name: Umberto Castellani
          - name: Riccardo Marin
          - name: Emanuele Rodola
      - title: "Non-Isometric Shape Matching via Functional Maps on Landmark-Adapted Bases (CGF)"
        authors: 
          - name: Mikhail Panine
          - name: Maxime Kirgo
          - name: Maks Ovsjanikov
          
  - name: CURVES & FEATURES
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Smooth Interpolating Curves with Local Control and Monotone Alternating Curvature"
        authors:
          - name: Alexandre Binninger
          - name: Olga Sorkine-Hornung
      - title: "b/Surf: Interactive Bézier Splines on Surface Meshes (TVCG)"
        authors:
          - name: Claudio Mancinelli
          - name: Giacomo Nazzaro   
          - name: Fabio Pellacini    
          - name: Enrico Puppo     
      - title: "SGLBP: Subgraph-based Local Binary Patterns for Feature Extraction on Point Clouds (CGF)"
        authors:
          - name: Bao Guo
          - name: Yuhe Zhang     
          - name: Jian Gao,  
          - name: Chunhui Li
          - name: Yao Hu   
 
  - name: LEARNING & CREATING
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "PriFit: Learning to Fit Primitives Improves Few Shot Point Cloud Segmentation"
        authors:
          - name: Gopal Sharma
          - name: Bidya Dash
          - name: Aruni RoyChowdhury
          - name: Matheus Gadelha
          - name: Marios Loizou
          - name: Liangliang Cao
          - name: Rui Wang
          - name: Erik G. Learned-Miller
          - name: Subhransu Maji
          - name: Evangelos Kalogerakis
      - title: "SDF-StyleGAN: Implicit SDF-Based StyleGAN for 3D Shape Generation"
        authors:
          - name: Xinyang Zheng
          - name: Yang Liu
          - name: Pengshuai Wang
          - name: Tong Xin
      - title: "MendNet: Restoration of Fractured Shapes Using Learned Occupancy Functions"
        authors:
          - name: Nikolas Lamb
          - name: Sean Banerjee
          - name: Natasha Banerjee

  - name: MESHES & PARTITIONS
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Precise High-order Meshing of 2D Domains with Rational Bézier Curves"
        authors:
          - name: Jinlin Yang
          - name: Shibo Liu
          - name: Shuangming Chai
          - name: Ligang Liu
          - name: Xiao-Ming Fu
      - title: "Rational Bézier Guarding"
        authors:
          - name: Payam Khanteimouri
          - name: Manish Mandad
          - name: Marcel Campen
      - title: "Simplification of 2D Polygonal Partitions via Point-line Projective Duality, and Application to Urban Reconstruction (CGF)"
        authors:
          - name: Julien Vuillamy
          - name: Andre Lieutier    
          - name: Florent Lafarge   
          - name: Pierre Alliez
         
  - name: TOOLS & DATA
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Deterministic Linear Time for Maximal Poisson-Disk Sampling using Chocks without Rejection or Approximation"
        authors:
          - name: Scott Mitchell 
      - title: "TinyAD: Automatic Differentiation in Geometry Processing Made Simple"
        authors:
          - name: Patrick Schmidt
          - name: Janis Born
          - name: David Bommes 
          - name: Marcel Campen  
          - name: Leif Kobbelt
      - title: "Hex Me If You Can"
        authors:
          - name: Pierre-Alexandre Beaufort
          - name: Maxence Reberol
          - name: Denis Kalmykov
          - name: Heng Liu
          - name: Franck Ledoux
          - name: David Bommes 

  - name: TILING & NESTING
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Constructing L∞ Voronoi Diagrams in 2D and 3D"
        authors:
          - name: Dennis Bukenberger
          - name: Kevin Buchin
          - name: Mario Botsch
      - title: "Fabricable Multi-Scale Wang Tiles"
        authors:
          - name: Xiaokang Liu
          - name: Chenran Li
          - name: Lin Lu
          - name: Oliver Deussen
          - name: Changhe Tu 
      - title: "Topological Simplification of Nested Shapes"
        authors:
          - name: Dan Zeng
          - name: Erin Chambers 
          - name: David Letscher
          - name: Tao Ju
          
          
-->
