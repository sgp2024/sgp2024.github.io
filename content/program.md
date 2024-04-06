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
#- title: Functional Correspondence from Discrete Geometry to Learning
#  teaser: /images/school-discrete.png
#  speakers:
#    - name: Riccardo Marin 
#      affiliation: University of Tuebingen
#    - name: Emanuele Rodola
#      affiliation: GLADIA
#  abstract: |
#     ***July 1st, 9:00 - 10:30***
#     
#     Geometry processing is a vital component for solving 3D shape-matching problems that have significant relevance in enabling various downstream tasks like artistic designs, CAD modeling, and medical analysis. With the advent of data-driven solutions, flexible alignment techniques have become essential tools to unleash the potential of deep learning methods. This tutorial introduces the Functional Maps paradigm, one of the main frameworks for the past decade. We will explain the main concepts of this elegant and flexible framework on graphs, and then develop the necessary tools for triangular mesh cases. We will review the crucial steps of this long-standing literature, from its inception to the advent of geometric deep learning. Additionally, we will highlight the latest and most promising research directions, giving participants a comprehensive understanding of the current state-of-the-art in this field.  
      
#- title: Hands-On Introduction to FEM in Python
#  teaser: /images/school-Python.png
#  speakers:
#    - name: Teseo Schneider
#      affiliation: University of Victoria
#  abstract: |
#      ***July 1st, 10:45 - 12:15***
#      
#      The numerical solution of partial differential equations (PDEs) is ubiquitous in computer graphics and engineering applications, ranging from the computation of UV maps and skinning weights to the simulation of elastic deformations, fluids, and light scattering. The finite element method (FEM) is the most commonly used discretization of PDEs due to its generality and rich selection of off-the-shelf commercial implementations. In this course, we will implement a FE solver in 1D for the Laplace equation from scratch using only Numpy. We will briefly derive the necessary theory and quickly move into live coding the solver. At the end of the course, you will have a basic applied understanding of how the FEM works and how to extend the current code to higher dimensions and more complicated physics. 
                
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
