---
title: "Program"
layout: "program"
type: "page"
menu: program


speakers: 
  - name: Alec Jacobson
    url: https://www.alecjacobson.com
    affiliation: University of Toronto & Adobe Research
    title: The Triangle is Dead, Long Live the Triangle!
    abstract: The geometry processing community has made tremendous progress working with discrete surfaces represented as explicit meshes of triangles. However, recent advances in computer vision and machine learning have demonstrated the power & seeming superiority of unstructured implicit representations. In this talk, I will present thoughts on how our research has been too attached to the triangle, how we can benefit from embracing alternative representations, and why ultimately triangle meshes still have an important role.
    portrait: /images/alec.jpg
  - name: Josephine Carstensen
    url: https://www.carstensen.mit.edu
    affiliation: Massachusetts Institute of Technology 
    title: Human-guided geometry processing in high-performance engineering design
    abstract: Topology optimization has gained traction as a design method for high-performing engineering components and structures. It is a computational approach that generates efficient material layouts, tailored to a user’s specific design requirements. To take full advantage of its exploratory power, topology optimization leaves the user as a passive observer who initiates the design process and assesses the quality of the design upon completion.  The resulting engineering designs are typically high-performing and have high levels of geometric complexity. However, ensuring the physical performance is adequately predicted by a fully automated design approach requires the inclusion of all relevant operating conditions, mechanical behaviors, and fabrication constraints. This requirement limits the widespread use of topology optimization. This talk will focus on recent contributions that address this barrier by introducing human-guided geometry processing as designs are generated. The human experience is actively leveraged to interactively alter local geometric feature size requirements or to encourage similarity to drawn sketches. Integrating human-guided geometry processing is shown to improve known and complex performance considerations related to both mechanical behavior and manufacturability of the designs.
    portrait: /images/josephine.jpeg
  - name: Xin Tong
    url: https://www.microsoft.com/en-us/research/people/xtong/
    affiliation: Microsoft Research Asia
    title: "Deep Learning based 3D Understanding and Generation"
    abstract: Over the past decade, the advancement of deep learning techniques has profoundly transformed the fields of computer vision and natural language processing. However, the distinct characteristics of 3D geometric data present obstacles to the application of deep learning in 3D understanding and generation tasks. In this talk, I will first explore the technical challenges encountered in 3D deep learning. Subsequently, I will present our research work aimed at addressing these challenges in deep learning based 3D understanding and generation. Finally, I will discuss the prospects, highlighting the potential opportunities and challenges in the field of 3D deep learning.
    portrait: /images/xin.jpg   

graduateSchoolCourses:
- title: Equivariant Neural Networks
  teaser: /images/gradschool/robin_rep_image.png
  speakers:
    - name: Robin Walters 
      url: https://www.khoury.northeastern.edu/people/robin-walters/
      affiliation: Northeastern University
    - name: Jung Yeon Park
      url: https://jypark0.github.io
      affiliation: Northeastern University
  abstract: Despite the success of deep learning, there remain challenges to progress. Deep models require vast datasets to train, can fail to generalize under surprisingly small changes in domain, and lack guarantees on performance. Incorporating symmetry constraints into neural networks has resulted in models called equivariant neural networks (ENNs) which have helped address these challenges. I will discuss several applications, such as radar signal processing, computer vision, and robot manipulation.
    

    ***June 22, 9:00 am - 10:30 am***
     
      
- title: Deep Learning for 3D Geometry
  teaser: /images/gradschool/ritchie_rep_image.png
  speakers:
    - name: Daniel Ritchie
      url: https://dritchie.github.io
      affiliation: Brown University
    - name: Zoë Marschner
      url: https://zoemarschner.com
      affiliation: Carnegie Mellon University
  abstract: The application of deep learning to geometry processing gives rise to many questions What kind of tasks are well suited for these new methods? How do deep learning methods play with existing geometry processing techniques? In this course, we'll first discuss geometry tasks that we can solve with learning, touching on tasks involving global analysis, local analysis, synthesis and more. Then, we'll turn to a discussion of traditional ways of representing geometry and how these representations interact with learning methods—looking at the architectures needed to perform learning tasks on these representations and the pros and cons of different choices of representation. We'll then turn to another representation neural implicits, in which the geometry itself is represented by a neural network. We'll introduce neural implicits, and talk about how to work with them, when they are useful, and some of their outstanding problems.
    

    ***June 22, 11:00 am - 12:30 pm***


- title: Fundamentals and Applications of Sketch Processing
  teaser: /images/gradschool/bessmeltsev_thumbnail - Olga Posukh.jpg
  speakers:
    - name: Mikhail Bessmeltsev
      url: http://www-labs.iro.umontreal.ca/~bmpix/
      affiliation: University of Montreal
    - name: Chenxi Liu
      affiliation: University of Toronto
  abstract: Sketches serve as a powerful medium for visual creation and communication, and are commonly used as an intuitive means to edit and model 2D or 3D shapes. This tutorial will explore sketches as a geometry representation strokes can be viewed as 1D curves on 2D or 3D domain, forming complex often non-manifold shapes. We will begin by discussing the common representations of sketches, examining their key geometric and topological properties, and addressing concepts about perception that are essential for processing human-created sketches. Building on these fundamentals, the tutorial will continue to cover research and developments in sketch processing, starting with methods that process sketches at the stroke level. We will then explore applications taking sketches as inputs and discuss advancements in learning-based methods that enhance sketch processing. (Image copyright (C) Olga Posukh.)
    

    ***June 22, 2:00 pm - 3:30 pm***


- title: Introduction to Optimization Time Integration for Solids and Fluids
  teaser: /images/gradschool/sgp2024-minchen-eris.png
  speakers:
    - name: Minchen Li 
      url: https://www.cs.cmu.edu/~minchenl/
      affiliation: Carnegie Mellon University
    - name: Jiayi (Eris) Zhang
      url: https://eriszhang.github.io
      affiliation: Stanford University
  abstract: Second-order optimization methods, such as Newton's Method, are critical not only in geometry processing for applications like shape deformation and mesh parameterization but also in the robust and accurate simulation of solid and fluid dynamics. In the first part of this course, we will provide a high-level overview of optimization time integration methods, starting from a geometric perspective focused on distortion minimization. Participants will learn how to extend distortion minimization methods to an elastodynamic simulation framework and will explore methods for simulating a variety of materials and phenomena, including cloth, hair, stiff objects, contacts, and fluids. The session also links to a comprehensive online book and a set of illustrative Python examples for the elastodynamic contact part to enhance understanding. In the second part of the course, we will show how various recent advancements in elastodynamic simulation are rooted in such a shared framework. This framework readily supports extensions like subspace methods for fast simulations, enhancements to rig-based animations with physical secondary motion, and the integration of multilevel methods for rapid previews and enhanced user interactivity, among many other applications. By the end of this course, attendees will gain a deeper insight into the close connection between geometry processing and physics-based simulation.
    

    ***June 22, 4:00 pm - 5:30 pm***


- title: Geometric Techniques for Digital Fabrication
  teaser: /images/gradschool/thumbnail_teaser-Attene-Livesu.jpg
  speakers:
    - name: Marco Attene 
      url: https://publications.cnr.it/authors/marco.attene
      affiliation: IMATI-CNR
    - name: Marco Livesu
      url: http://pers.ge.imati.cnr.it/livesu/
      affiliation: IMATI-CNR
  abstract: Digital fabrication is gathering increasing interest for its potential to revolutionize manufacturing. By leveraging computer-aided design (CAD) and additive manufacturing techniques, such as 3D printing, digital fabrication allows for rapid prototyping, customization, and complex geometries that would be challenging or impossible to achieve with traditional manufacturing methods. This shift towards digital methods offers significant reductions in waste and energy consumption, aligning with sustainable practices and the growing demand for eco-friendly production. 

    In such a context, geometry processing plays a pivotal role as an enabler to create and manipulate geometric data to optimize shapes and structures for manufacturing. Effective geometry processing can lead to more efficient use of materials, improved product strength and functionality, and the ability to create intricate designs that meet precise specifications. A strong synergy between geometry processing and digital fabrication is essential for advancing the capabilities and applications of manufacturing in the digital age. 

    This lecture gives an overview of various manufacturing technologies, explaining their strenghts and limitations, and showing how clever geometric techniques are necessary to best exploit them. We describe the main approaches to cope with each single step along the processing pipeline that prepares the 3D model for fabrication, and show how to actually implement some of the most important algorithms along the pipeline. Finally, we discuss open and challenging problems from both an academic and an industrial perspective.
    

    ***June 23, 9:00 am - 10:30 am*** 


- title: Introduction to Physically-Based Rendering Related to Geometry Simplification
  teaser: /images/gradschool/zahra_junqiu_rep_image.png
  speakers:
    - name: Zahra Montazeri
      affiliation: University of Manchester
    - name: Junqiu Zhu
      url: http://junqiuzhu.com
      affiliation: University of California Santa Barbara
  abstract: Physically-based rendering (PBR) is a method of shading and rendering that provides a more accurate representation of how light interacts with material properties. A pivotal technique within PBR is ray tracing, which realistically simulates the lighting of a scene. This technique involves tracing the path of light as it travels from the camera through the pixel plane and interacts with objects in the 3D scene before reflecting back to the light sources. Despite its advantages, ray tracing and the rendering of detailed geometries, especially in dynamic scenes like cloth rendering, are computationally demanding. To balance performance with visual fidelity, geometry simplification is often employed. This involves reducing the complexity of 3D models while trying to maintain an appearance that is as close as possible to the original. The trade-off between the level of geometry simplification and the resulting appearance is crucial, as excessive simplification can lead to a loss of realism, particularly in how materials and light interact. In this course we will first introduce the basic concept of physically-based rendering and ray-tracing, and then we will highlight the challenges and considerations in achieving both efficient and visually compelling results by balancing the geometry.
    

    ***June 23, 11:00 am - 12:30 pm***


- title: Geometry Processing Research in Python
  teaser: /images/gradschool/oded_rep_image.png
  speakers:
    - name: Oded Stein
      url: https://odedstein.com
      affiliation: University of Southern California
  abstract: Are you new to geometry processing research, or are you new to geometry processing in Python? This course will teach you all you need to quickly get started with geometry processing in Python. We will learn how to prototype using the NumPy, Gpytoolbox and Polyscope libraries. If you are already used to MATLAB or libigl, then this will be an easy transition. If you are completely new to the field, then you will learn how to quickly translate your geometry ideas into computer code. The only required prerequisite for this class is basic Python knowledge.
    

    ***June 23, 2:00 pm - 3:00 pm***        


- title: Monte Carlo Geometry Processing
  teaser: /images/gradschool/rohan_rep_image.png
  speakers:
    - name: Rohan Sawney
      url: http://rohansawhney.io
      affiliation: NVIDIA
    - name: Bailey Miller
      url: https://www.bailey-miller.com
      affiliation: Carnegie Mellon University
  abstract: The ability to accurately analyze large amounts of geometric information is fundamental to many scientific and engineering disciplines, ranging from geology to medicine, and autonomous driving to industrial design. Techniques based on partial differential equations (PDEs) provide powerful tools for analyzing many physical systems, but conventional grid-based methods for solving PDEs are not yet at a stage where they “just work” on problems of real-world complexity. A constant challenge is the need for spatial discretization, which traditionally involves dividing the domain into a high-quality volumetric mesh to perform PDE-based analysis. Unfortunately, this approach does not scale well to modern computer architectures as it is inherently sequential and memory intensive, and as such, there remains a large divide between our ability to visualize and analyze the natural world.

    Techniques based on the walk on spheres (WoS) algorithm make a radical departure from conventional PDE solvers, by reformulating the solution to fundamental PDEs like the Poisson equation as recursive integrals that can be solved using the Monte Carlo method. Since these integrals closely resemble those found in light transport theory, we can leverage deep knowledge from Monte Carlo rendering to build new scalable algorithms for solving PDEs with vastly different numerical tradeoffs, such as avoiding volumetric meshing altogether.

    This course will provide a broad overview of grid-free Monte Carlo methods for PDEs, with an emphasis on teaching the key principles of Monte Carlo, from sample generation and variance reduction to system design, by ways of WoS and its recent generalizations.
    

    ***June 23, 3:30 pm - 5:00 pm***

paperSessions: 
#- name: Meshing (Monday 10:45-12:45)
#  papers:
#      - title: "HalfedgeCNN for Native and Flexible Deep Learning on Triangle Meshes"
#        authors:
#          - name: Daniel Tyson
#          - name: Ingmar Ludwig        
#          - name: Marcel Campen
#      - title: "HexBox: Interactive Box Modeling of Hexahedral Meshes"
#        authors:
#          - name: Francesco Zoccheddu          
#          - name: Enrico Gobbetti
#          - name: Marco Livesu
#          - name: Nico Pietroni
#          - name: Gianmarco Cherchi                    
#      - title: "Quadratic-Attraction Subdivision"
#        authors:
#          - name: Kestutis Karciauskas
#          - name: Jorg Peters          
#
#- name: 2D Geometry (Monday 15:00-16:00)  
#  papers:
#      - title: "Singularity-Free Frame Fields for Line Drawing Vectorization"      
#        authors:
#          - name: Olga Guțan        
#          - name: Shreya Hegde         
#      - title: "Variational Pruning of Medial Axes of Planar Shapes"   
#        authors:
#          - name: Peter Rong           
#          - name: Tao Ju


---  


<!-- 

Toponet?


paper1055	Partial Matching of Nonrigid Shapes by Learning Piecewise Smooth Functions		Ron Kimmel                             David Bensaid                             Noam Rotstein                             Nelson Goldenstein


          

The complete program schedule can be downloaded [here.](/images/SGP_2022_Program.pdf) (The file with timestamp 2022-06-20 09:00:00 is the current one)

paperUSB: https://cloud.fraunhofer.at/s/sY2mezd4NgRRoPM/download/USB-SGP2021.zip
paperURL: https://diglib.eg.org/handle/10.2312/2633079     

        affiliation: Università degli Studi di Cagliari   
      - name: Marco Livesu
        affiliation: IMATI
        

    teaser: /images/default_thumbnail.jpg

    abstract: Hexahedral meshes are a prominent volumetric mesh representation. They are largely used as computational domains for the resolution of partial differential equations for physically based simulation, making them a core ingredient of many software tools used by the automobile, naval, aerospace, medical, and geological industries, as well as for many applications in Computer Graphics and Animation. In academic research and industry, the algorithmic generation and processing of hexahedral meshes have been studied for more than 30 years now. In this course, we will introduce the topic of hexahedral meshes and focus on the most relevant techniques for hexahedral mesh generation in Computer Graphics. For each technique, we will highlight capabilities and limitations, also pointing out the associated unsolved challenges. The required background, pertaining to geometrical as well as combinatorial aspects, will be introduced along the way.
    
    
    
    
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
