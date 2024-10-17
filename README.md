# Awesome CAE Software -- From CAD to AI

A curated list of awesome CAE frameworks, libraries, and software from a full CAE workflow perspective, including the integration of AI technologies.

---

# CAD (Computer-Aided Design)

*Software tools used in the design phase for creating detailed geometric models, which serve as the foundation for further CAE processes.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [FreeCAD](https://github.com/FreeCAD/FreeCAD) | Windows, Mac, Linux | Open Source | FreeCAD is an open-source parametric 3D modeler that allows users to design real-life objects, modify designs via parametric modeling, create 3D models from 2D sketches, and is suitable for various fields such as product design, mechanical engineering, and architecture. |
| [cadmium](https://github.com/jay3sh/cadmium) | Python | Open Source | Cadmium is a Python library for Solid Modeling that lets you create primitive shapes, apply CSG operations, and perform affine transformations like translation and rotation. |
| [CadQuery](https://github.com/CadQuery/cadquery) | Python | Open Source | CadQuery is an easy-to-use Python module for creating parametric 3D CAD models, offering advantages over OpenSCAD through its powerful CAD kernel, advanced modeling capabilities, efficient scripting, and support for high-quality formats like STEP and DXF, making it suitable for integration into servers and scientific applications. |
| [oce](https://github.com/tpaviot/oce) | C++ | Open Source | OCE (Open Cascade Community Edition) is a fork of the Open Cascade 3D C++ modeling library that collects patches, changes, and improvements from the OCC community, with official documentation and sources available at the Open Cascade Development website. |
| [pythonocc](https://github.com/tpaviot/pythonocc) | Python | Open Source | pythonocc is a Python library based on the OpenCascade Technology modeling kernel, providing 3D modeling and data exchange features for CAD, PDM, PLM, and BIM development, with capabilities including full access to OpenCascade C++ classes, 3D visualization in various Python GUI frameworks, web browsers, and Jupyter notebooks, as well as support for popular data exchange formats like IGES, STEP, STL, PLY, OBJ, and GLTF. |

---

# Meshing

*Tools and libraries specifically for generating high-quality meshes from CAD models, essential for accurate and efficient simulation.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [gridder](https://github.com/lanl/gridder) | C | Open Source | GRIDDER is an interactive grid generation tool that creates orthogonal 2D quadrilateral or 3D hexahedral grids, allowing for even, logarithmic, or geometric grid spacing across multiple regions and dimensions, with output options in formats such as AVS, Tracer 3D, Vector, and FEHM. |
| [libMesh](https://github.com/libMesh/libmesh) | C++ | Open Source | libMesh is a numerical simulation library designed for solving partial differential equations using unstructured discretizations on both serial and parallel platforms, with a focus on adaptive mesh refinement and support for various geometric and finite element types. |
| [meshpy](https://mathema.tician.de/software/meshpy) | Python | Open Source | MeshPy is a Python library for generating high-quality triangular and tetrahedral meshes, primarily for finite-element simulations, while also serving applications in computer graphics and robotics, utilizing interfaces to well-known mesh generators like Triangle and TetGen. |
| [meshzoo](https://github.com/nschloe/meshzoo) | Python | Open Source | Meshzoo is a straightforward and efficient mesh generation tool for finite element and finite volume computations, ideal for simple geometries, as it leverages the domain's structure without the complexity of advanced mesh generators. |
| [pygmsh](https://github.com/nschloe/pygmsh) | Python | Open Source | pygmsh combines the power of Gmsh with the versatility of Python. It provides useful abstractions from Gmsh's own Python interface so you can create complex geometries more easily. |
| [pymesh](http://pymesh.readthedocs.io/en/latest) | Python | Open Source | PyMesh is a geometry processing platform for rapid prototyping that integrates various mesh processing functionalities and interfaces with top open-source packages, enabling operations like mesh reading/writing, local mesh processing, mesh booleans, mesh generation, and finite element matrix assembly in a unified environment. |
| [Robust-Hexahedral-Re-Meshing](https://github.com/gaoxifeng/Robust-Hexahedral-Re-Meshing) | Windows, Mac, Linux | Open Source | This repository contains the meshing software developed for Robust Hexahedral Re-Meshing as presented in the publication by Xifeng Gao et al. in ACM Transactions on Graphics (SIGGRAPH ASIA 2017). |
| [smesh](https://github.com/tpaviot/smesh) | C++ | Open Source | smesh is a standalone MESH framework based on OpenCascade, forked from the SALOME SMESH project, designed for use in the pythonocc project. It builds on the original SALOME project by Fotis Soutis to offer mesh functionalities independently. |

---

# Preprocessing and Boundary Condition Definition

*Broader preprocessing tools, including meshing, defining boundary conditions, setting material properties, and other simulation parameters before running analysis.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [abapy](https://github.com/lcharleux/abapy) | Python | Open Source | AbaPy is a Python toolkit for automating finite element simulations in Abaqus, offering tools for mesh generation, post-processing of simulation results, material preprocessing, indentation analysis, and advanced examples for high-level research tasks. |
| [abaqus2dyna](https://github.com/tbhartman/abaqus2dyna) | Python | Open Source | abaqus2dyna is a script to convert, in a limited fashion, Abaqus keyword input files to LS-DYNA keyword input files. It is currently very limited. See example.inp for an example Abaqus file that can be converted. |
| [AbqParse](https://github.com/crmccreary/AbqParse) | Python | Open Source | A simple parser for Abaqus input files that parses out the keywords, parameters, and data lines. |
| [pycalculix](https://github.com/spacether/pycalculix) | Python | Open Source | PyCalculix is a Python 3 library to automate and build finite element analysis (FEA) models in Calculix.(Archived by the owner on Feb 14, 2024) |
| [pyDOE](https://github.com/tisimst/pyDOE) | Python | Open Source | Library for creating design of experiments studies. |
| [pyNastran](https://github.com/SteveDoyle2/pyNastran) | Python | Open Source | pyNastran is an interface library to the various Nastran file formats (BDF, OP2, OP4). Using the BDF interface, you can read/edit/write Nastran geometry without worrying about field formatting. Many checks are also performed to verify that your model is correct. Using the OP2 interface, you can read large result files quickly and efficiently. Additionally, you can also extract a subset of the result data and write OP2/F06 result files. |
| [pyvista](https://github.com/pyvista/pyvista) | Python | Open Source | PyVista is a Pythonic interface for VTK that simplifies 3D plotting, mesh data manipulation, and visualization of spatial datasets, offering a high-level API for rapid prototyping and analysis of complex geometries. |
| [qd-ansa](https://github.com/qd-cae/qd-ansa) | Python | Open Source | This library is a python utility library for ANSA and META from Beta CAE Systems SA. |
| [Simright WebMesher](https://www.simright.com/apps/simright-webmesher) | Web | Commercial | Web-based preprocessor supporting interactive meshing and definitions of loads & BCs. |
| [VTK](https://github.com/Kitware/VTK) | C++ | Open Source | VTK is an open-source software system for image processing, 3D graphics, volume rendering, and visualization, widely used in academia, government research institutions, and industry, offering advanced algorithms and rendering techniques, with its origins tied to the textbook "The Visualization Toolkit." |

---

# Materials

*Libraries and resources dedicated to defining material properties and constitutive models, including user subroutines for customized material behavior.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [ABAQUS_Subroutines](https://github.com/ALandauer/ABAQUS_Subroutines) | Fortran | Open Source | Viscoplastic UMAT, rotational body force UEL, UMAT implmenentation of Linder et al. 2011-based three-element polymer viscoelasticity model (co-written with Pinkesh Malhotra). |
| [ABAQUS_Subroutines 2](https://github.com/WeilinDeng/ABAQUS) | Fortran | Open Source | Collection of Abaqus user materials(.inp sample). |
| [ABAQUS-US](https://github.com/jgomezc1/ABAQUS-US) | Fortran | Open Source | ABAQUS-US is a repository containing user element (UEL) and user material (UMAT) subroutines for ABAQUS, featuring classical and Cosserat elements with various constitutive models, along with input files linked in versheet.dat for easier use. |

---

# Solvers

*Core computational tools that solve numerical models for various physics, including structural, thermal, and fluid simulations.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [CalculiX](https://github.com/GeneralElectric/CalculiX) | C++ | Open Source | CalculiX is an OSS package designed to solve field problems using the finite element method. |
| [CFDEM](https://github.com/CFDEMproject/CFDEMcoupling-PUBLIC) | C++ | Open Source | an Open Source framework that integrates Computational Fluid Dynamics (CFD) with the Discrete Element Method (DEM), combining the LIGGGHTS® DEM code and the OpenFOAM® CFD package for advanced fluid-particle simulations. |
| [FEniCS](https://fenicsproject.org/) | C++ | Open Source | FEniCS is an open-source computing platform for efficiently solving partial differential equations (PDEs) using the finite element method (FEM), providing both high-level Python and C++ interfaces, and supporting a range of platforms from laptops to high-performance computing systems. |
| [JuliaFEM](https://github.com/JuliaFEM/JuliaFEM.jl) | Julia | Open Source | The JuliaFEM software library is a framework that allows for the distributed processing of large Finite Element Models across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. |
| [NASTRAN-95](https://github.com/nasa/NASTRAN-95) | Fortran | Open Source | NASTRAN is the NASA Structural Analysis System, a finite element analysis program (FEA) completed in the early 1970's. It was the first of its kind and opened the door to computer-aided engineering. Subsections of a design can be modeled and then larger groupings of these elements can again be modeled. NASTRAN can handle elastic stability analysis, complex eigenvalues for vibration and dynamic stability analysis, dynamic response for transient and steady state loads, and random excitation, and static response to concentrated and distributed loads, thermal expansion, and enforced deformations. |
| [OpenFoam](https://github.com/OpenFOAM?tab=repositories) | C++ | Open Source | OpenFOAM is a free, open source computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. It has a large user base across most areas of engineering and science, from both commercial and academic organisations. OpenFOAM has an extensive range of features to solve anything from complex fluid flows involving chemical reactions, turbulence and heat transfer, to solid dynamics and electromagnetics. |
| [SU2](https://github.com/su2code/SU2) | C++ | Open Source | SU2 is an open-source C++ software suite designed for solving partial differential equations and performing PDE-constrained optimization, primarily used in computational fluid dynamics and aerodynamic shape optimization, but also extended to handle equations in areas like electrodynamics and chemically reacting flows. |
| [SurveyofPDEPackages](https://github.com/JuliaPDE/SurveyofPDEPackages) | Library list | Open Source | This is a brief list of packages relevant when solving partial differential equations with Julia. |

---

# Postprocessing and Visualization

*Software for analyzing simulation results, visualizing data, and extracting key insights from simulation outputs.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [abaqusPython](https://github.com/quisten/abaqusPython) | Python | Open Source | A collection of frequently used Abaqus scripts and other useful gems. |
| [ParaView](https://github.com/Kitware/ParaView) | C++ | Open Source | Open-source, multi-platform data analysis and visualization application based on Visualization Toolkit (VTK). |
| [PyQus](https://github.com/JorgeDeLosSantos/pyqus) | Python | Open Source | Python codes for post-processing Abaqus ODB files. |
| [pyNastran](https://github.com/SteveDoyle2/pyNastran) | Python | Open Source | pyNastran is an interface library to the various Nastran file formats (BDF, OP2, OP4). Using the BDF interface, you can read/edit/write Nastran geometry without worrying about field formatting. Many checks are also performed to verify that your model is correct. Using the OP2 interface, you can read large result files quickly and efficiently. Additionally, you can also extract a subset of the result data and write OP2/F06 result files. |
| [Simright Viewer](https://www.simright.com/apps/simright-viewer) | Web | Commercial | Web-based viewer for CAD/CAE models, used to create and share 3D snapshots. |

---

# Optimization

*Tools for optimization and design exploration, enhancing performance and meeting design criteria by iterating on model parameters.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [CasADi](https://github.com/casadi/casadi) | Python | Open Source | CasADi is an open-source tool for nonlinear optimization and algorithmic differentiation, enabling rapid and efficient implementation of various numerical optimal control methods for both offline contexts and nonlinear model predictive control (NMPC). |
| [OpenMDAO](https://github.com/OpenMDAO/OpenMDAO-Framework) | Python | Open Source | Open-source high-performance computing platform for systems analysis and multidisciplinary optimization, written in Python. |
| [opti4Abq](https://github.com/mengomarlene/opti4Abq) | Python | Open Source | Optimization method for Python2 and ABAQUS. |
| [ToOptiX](https://github.com/ldslpm/ToOptiX) | Python | Open Source | ToOptix is used for multiphysical topology optimization.  |
| [YALMIP](https://github.com/yalmip/YALMIP) | MATLAB | Open Source | MATLAB toolbox for optimization modeling. |

---

# AI in CAE

*Leveraging artificial intelligence and machine learning to enhance various aspects of the CAE workflow, including model generation, optimization, and decision-making.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| *Content to be added.* | | | |

---

# Tools and Utilities

*Miscellaneous tools that assist in various aspects of the CAE workflow, such as file conversion, scripting, and data exchange.*

| Tool Name | Language | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [abqpy](https://github.com/haiiliin/abqpy) | Python | Open Source | abqpy is a Python package that offers type hints for scripting Abaqus in Python, allowing fluent scriptwriting without accessing Abaqus directly, and includes simple APIs to execute Abaqus commands, enabling model building, job submission, and data extraction from a single Python script without opening Abaqus/CAE. |
| [FEconv](https://github.com/victorsndvg/FEconv) | Python | Open Source | FEconv can convert finite element (FE) mesh written in several commercial file formats. It can also transform the FE type and/or perform some bandwidth optimizations. |
| [nastran-find](https://github.com/setvisible/nastran-find) | Python | Open Source | Solution for browsing Nastran input deck files. |
| [odb2vtk](https://github.com/Liujie-SYSU/odb2vtk) | Python | Open Source | Converts Abaqus ODB files to VTK format for Paraview visualization. |
| [ODB2VTKplus](https://github.com/Liu-Qingbin/ODB2VTKplus) | Python | Open Source | Another python version of odb2vtk. |
| [ODB2VTK](https://github.com/Arris-Composites/ODB2VTK) | C++ | Open Source | Another C++ version of odb2vtk. |
| [Simright Converter](https://www.simright.com/apps/simright-converter) | Web | Commercial | Web-based tool for converting CAE models between different formats. |
| [YJExchanger](https://www.simversus.com/solutions/yjexchanger) | SDK | Commercial | Commercialized mesh format and CAE/CFD result format conversion components, support Abaqus *.odb / Ansys *.rst / Fluent *.cas *.dat *.cas.h5 *.dat.h5. |
| [CEETRON Access](https://docs.techsoft3d.com/ceetron/latest/solve-access-mesh/access/index.html) | SDK | Commercial | CEETRON Access from Tech Soft 3D is a toolkit designed to offer a comprehensive mechanism for accessing data from model and solution result files of various key commercial finite element analysis (FEA) software systems utilized in mechanical computer-aided engineering (MCAE) and computational fluid dynamics (CFD). |
---

# Editors and Plugins

*Editors and plugins that provide syntax highlighting and features to support writing CAE scripts and input files.*

| Tool Name | Platform | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [ATOM language-abaqus](https://atom.io/packages/language-abaqus) | Atom | Open Source | ABAQUS language highlighting in the editor ATOM. |
| [ATOM language-nastran](https://atom.io/packages/language-nastran) | Atom | Open Source | Adds syntax highlighting to NASTRAN files in Atom. |
| [vim-abaqus](https://github.com/gradzikb/vim-abaqus) | Vim | Open Source | Vim-plugin for ABAQUS input files. |
| [vim-lexer-lsdyna](https://github.com/tbhartman/vim-lexer-lsdyna) | Vim | Open Source | LS-DYNA keyword input file lexer for Vim. |
| [vim-radioss](https://github.com/gradzikb/vim-radioss) | Vim | Open Source | Vim-plugin for RADIOSS input files. |

---

# Documentation Tools

*Projects related to extracting, managing, and enhancing documentation for CAE software, enabling better accessibility and usability.*

| Tool Name | Platform | Open Source/Commercial | Description |
| --------- | -------- | ---------------------- | ----------- |
| [Abaqus-Documentation-Scraper](https://github.com/bendeaton/Abaqus-Documentation-Scraper) | Python | Open Source | Python script to extract keywords, parameters, and parameter values from the Abaqus HTML documentation. |
| [Abaqus-Sublime](https://github.com/bendeaton/Abaqus-Sublime) | Sublime Text | Open Source | Sublime Text syntax highlighting for the Abaqus finite element software. |
| [LS-DYNA-Sublime](https://github.com/bendeaton/LS-DYNA-Sublime) | Sublime Text | Open Source | Sublime Text syntax highlighting for the LS-DYNA finite element software. |

---

# Summary

This curated list of CAE frameworks, libraries, and tools covers the full spectrum of the CAE workflow, from CAD modeling and meshing to solvers, postprocessing, and optimization. With the addition of AI in CAE, the future of simulation is being reshaped by machine learning, enabling faster model predictions, data-driven optimization, and enhanced automation in engineering processes.
