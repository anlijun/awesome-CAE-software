# 语言
- [English](./README.md)
- [简体中文](./README.zh-CN.md)

# 优秀的CAE软件——从CAD到AI

从完整的CAE工作流程角度，精心整理了一系列优秀的CAE框架、库和软件，包括AI技术的集成。

---

# CAD (计算机辅助设计)

*用于设计阶段的软件工具，用于创建详细的几何模型，这些模型是进一步CAE过程的基础。*

| 工具名称 | 语言 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [FreeCAD](https://github.com/FreeCAD/FreeCAD) | Windows, Mac, Linux | 开源 | FreeCAD 是一个开源的参数化3D建模器，允许用户设计实际物体，使用参数化建模修改设计，从2D草图创建3D模型，适用于产品设计、机械工程和建筑等多个领域。 |
| [Blender](https://www.blender.org/) | Windows, Mac, Linux | 开源 | Blender 是一个免费的开源3D创建套件，支持整个3D管道，提供建模、动画、渲染等工具，并拥有可定制的Python API。 |
| [LibreCAD](https://github.com/LibreCAD/LibreCAD) | C++17 | 开源 | LibreCAD 是一个跨平台的2D CAD程序，使用C++17编写。它可以读取DXF/DWG文件，并可以输出DXF/PDF/SVG文件。支持点、线、圆、椭圆、抛物线、样条等图元，界面高度可定制，拥有几十种语言版本。 |
| [OpenSCAD](https://github.com/openscad/openscad) | Windows, Mac, Linux | 开源 | LibreCAD 是一个跨平台的2D CAD程序，使用C++17编写。它可以读取DXF/DWG文件，并可以输出DXF/PDF/SVG文件。支持点、线、圆、椭圆、抛物线、样条等图元，界面高度可定制，拥有几十种语言版本。 |
| [QCAD](https://www.qcad.org/) | Windows, Mac, Linux | 开源 | QCAD 是一个免费的开源2D CAD应用程序，用于创建建筑平面图、室内布局、机械零件、示意图和图表等技术图纸。QCAD注重模块化、可扩展性和可移植性，界面直观，用户即使没有CAD经验也能快速开始绘图和设计。 |
| [LeoCAD](https://github.com/leozide/leocad) | Windows, Mac, Linux | 开源 | 一个用于创建虚拟乐高模型的CAD应用程序。 |
| [CAD_Sketcher](https://github.com/hlorus/CAD_Sketcher) | Python | 开源 | 这是Blender的基于约束的草图扩展，允许通过定义切线、距离、角度、相等等几何约束来创建精确的2D形状。草图保持可编辑，并支持完全非破坏性工作流程。 |
| [cadmium](https://github.com/jay3sh/cadmium) | Python | 开源 | Cadmium 是一个用于实体建模的Python库，允许创建原始形状、应用CSG操作，并执行仿射变换，如平移和旋转。 |
| [CadQuery](https://github.com/CadQuery/cadquery) | Python | 开源 | CadQuery 是一个易于使用的Python模块，用于创建参数化3D CAD模型，相较于OpenSCAD，它具有强大的CAD内核、先进的建模能力、高效的脚本编写能力，并支持高质量格式如STEP和DXF，适合集成到服务器和科学应用中。 |
| [Build123d](https://build123d.readthedocs.io/) | Python | 开源 | Build123d 可以被认为是 [CadQuery](https://github.com/CadQuery/cadquery) 的进化版。它是一个基于Python的高级CAD框架，利用Open Cascade内核进行直观的2D/3D BREP建模，方便复杂设计的多样制造需求，且通过更灵活强大的脚本环境与主流CAD软件无缝集成。 |
| [oce](https://github.com/tpaviot/oce) | C++ | 开源 | OCE（Open Cascade Community Edition）是Open Cascade 3D C++建模库的一个分支，收集了来自OCC社区的补丁、变更和改进，官方文档和源码可在Open Cascade Development网站上获取。 |
| [OpenJSCAD](https://github.com/jscad/OpenJSCAD.org) | Javascript | 开源 | JSCAD 是一组模块化的、基于浏览器和命令行的开源工具，用于使用JavaScript代码创建参数化的2D和3D设计。它为生成3D模型提供了一种快速、精确且可重复的方法，特别适用于3D打印应用。 |
| [pythonocc](https://github.com/tpaviot/pythonocc) | Python | 开源 | pythonocc 是一个基于OpenCascade技术建模内核的Python库，提供用于CAD、PDM、PLM和BIM开发的3D建模和数据交换功能，支持全面访问OpenCascade的C++类，在各种Python GUI框架、网页浏览器和Jupyter笔记本中进行3D可视化，并支持常见的数据交换格式如IGES、STEP、STL、PLY、OBJ和GLTF。 |
| [Fornjot](https://github.com/hannobraun/Fornjot) | Rust | 开源 | Fornjot 是一个早期阶段的CAD内核，使用Rust编写，专注于3D打印和机械加工等机械CAD应用，优先考虑可靠性、适合代码优先建模的友好API，并支持第三方扩展，仍在积极开发中。 |

---

# 网格划分

*专用于从CAD模型生成高质量网格的工具和库，这是准确高效模拟的基础。*

| 工具名称 | 语言 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [Gmesh](https://gmsh.info/) | C++ | 开源 | Gmsh 是一个开源的3D有限元网格生成器，带有内置的CAD引擎和后处理器。其设计目标是提供一个快速、轻量且用户友好的网格工具，具有参数化输入和灵活的可视化功能。 |
| [gridder](https://github.com/lanl/gridder) | C | 开源 | GRIDDER 是一个交互式网格生成工具，可以创建正交的2D四边形或3D六面体网格，支持多个区域和维度的均匀、对数或几何网格间距，并提供AVS、Tracer 3D、Vector和FEHM等格式的输出选项。 |
| [libMesh](https://github.com/libMesh/libmesh) | C++ | 开源 | libMesh 是一个数值模拟库，旨在使用非结构化离散化方法解决偏微分方程，适用于串行和并行平台，重点支持自适应网格细化和各种几何和有限元类型。 |
| [meshpy](https://mathema.tician.de/software/meshpy) | Python | 开源 | MeshPy 是一个用于生成高质量三角形和四面体网格的Python库，主要用于有限元模拟，也可用于计算机图形和机器人学，提供对知名网格生成器如Triangle和TetGen的接口。 |
| [meshzoo](https://github.com/nschloe/meshzoo) | Python | 开源 | Meshzoo 是一个简单高效的网格生成工具，适用于有限元和有限体积计算，特别适合简单几何体，它利用域的结构而不需要复杂的高级网格生成器。 |
| [Netgen](https://github.com/NGSolve/netgen) | C++ | 开源 | NETGEN 是一个自动3D四面体网格生成器，支持CSG、BRep（STL）输入，并处理IGES和STEP文件，提供网格优化和分层细化模块。 |
| [pygmsh](https://github.com/nschloe/pygmsh) | Python | 开源 | pygmsh 将Gmsh的强大功能与Python的多功能性结合在一起。它提供了Gmsh自己的Python接口的有用抽象，使您可以更轻松地创建复杂的几何体。 |
| [pymesh](http://pymesh.readthedocs.io/en/latest) | Python | 开源 | PyMesh 是一个用于快速原型设计的几何处理平台，集成了各种网格处理功能，并与顶级开源软件包接口，支持网格读写、本地网格处理、网格布尔运算、网格生成以及有限元矩阵组装等操作。 |
| [Robust-Hexahedral-Re-Meshing](https://github.com/gaoxifeng/Robust-Hexahedral-Re-Meshing) | Windows, Mac, Linux | 开源 | 该仓库包含了用于强健六面体重新网格划分的网格软件，展示于Xifeng Gao等人在ACM Transactions on Graphics (SIGGRAPH ASIA 2017)发表的论文中。 |
| [smesh](https://github.com/tpaviot/smesh) | C++ | 开源 | smesh 是一个基于OpenCascade的独立网格框架，分支自SALOME SMESH项目，专为pythonocc项目设计。它基于Fotis Soutis的原始SALOME项目，提供独立的网格功能。 |
| [TetGen Python](https://github.com/pyvista/tetgen) | Python/C++ | 开源 | 一个 [TetGen](https://github.com/ufz/tetgen) 库的Python接口，用于生成任何3D多面体域的四面体网格。 |

---

# 预处理和边界条件定义

*更广泛的预处理工具，包括网格划分、定义边界条件、设置材料属性和其他在运行分析之前的仿真参数。*

| 工具名称 | 语言 | 开源/商业 | 描述 |
| -------- | ---- | -------- | ---- |
| [abapy](https://github.com/lcharleux/abapy) | Python | 开源 | AbaPy 是一个用于在 Abaqus 中自动化有限元仿真的 Python 工具包，提供了网格生成、仿真结果后处理、材料预处理、压痕分析以及高级研究任务的示例工具。 |
| [abaqus2dyna](https://github.com/tbhartman/abaqus2dyna) | Python | 开源 | abaqus2dyna 是一个脚本，用于有限程度地将 Abaqus 关键字输入文件转换为 LS-DYNA 关键字输入文件。当前功能非常有限，示例文件见 example.inp。 |
| [AbqParse](https://github.com/crmccreary/AbqParse) | Python | 开源 | 一个简单的 Abaqus 输入文件解析器，可以解析出关键字、参数和数据行。 |
| [pyDOE](https://github.com/tisimst/pyDOE) | Python | 开源 | 用于创建实验设计研究的库。 |
| [pyvista](https://github.com/pyvista/pyvista) | Python | 开源 | PyVista 是一个用于 VTK 的 Python 接口，简化了 3D 绘图、网格数据操作和空间数据集的可视化，提供了一个高层次的 API，用于快速原型设计和复杂几何体的分析。 |
| [qd-ansa](https://github.com/qd-cae/qd-ansa) | Python | 开源 | 这是一个用于 Beta CAE Systems SA 的 ANSA 和 META 的 Python 实用程序库。 |
| [Simright WebMesher](https://www.simright.com/apps/simright-webmesher) | Web | 商业 | 基于 Web 的预处理器，支持交互式网格划分和载荷与边界条件的定义。 |
| [VTK](https://github.com/Kitware/VTK) | C++ | 开源 | VTK 是一个开源软件系统，用于图像处理、3D 图形、体绘制和可视化，广泛应用于学术界、政府研究机构和工业界，提供先进的算法和渲染技术，其起源与教材《The Visualization Toolkit》相关。 |

---

# 材料

*致力于定义材料属性和本构模型的库和资源，包括用于定制材料行为的用户子程序。*

| 工具名称 | 语言 | 开源/商业 | 描述 |
| -------- | ---- | -------- | ---- |
| [ABAQUS_Subroutines](https://github.com/ALandauer/ABAQUS_Subroutines) | Fortran | 开源 | 含粘塑性 UMAT、旋转体力 UEL、根据 Linder 等 2011 年提出的三元聚合物粘弹性模型的 UMAT 实现（与 Pinkesh Malhotra 共同编写）。 |
| [ABAQUS_Subroutines 2](https://github.com/WeilinDeng/ABAQUS) | Fortran | 开源 | Abaqus 用户材料的集合（.inp 示例）。 |
| [ABAQUS-US](https://github.com/jgomezc1/ABAQUS-US) | Fortran | 开源 | 包含用户单元（UEL）和用户材料（UMAT）子程序的 Abaqus 仓库，提供经典和 Cosserat 单元以及多种本构模型，输入文件通过 versheet.dat 链接以方便使用。 |

---

# 求解器

*用于解决各种物理问题的核心计算工具，包括结构、热学和流体仿真。*

| 工具名称 | 语言 | 开源/商业 | 描述 |
| -------- | ---- | -------- | ---- |
| [CalculiX](https://github.com/Dhondtguido/CalculiX) | Fortran/C | 开源 | CalculiX 是一个开源的有限元分析软件，用于解决复杂的结构和流体动力学问题，其输入格式基于 ABAQUS。 |
| [CFDEM](https://github.com/CFDEMproject/CFDEMcoupling-PUBLIC) | C++ | 开源 | 一个开源框架，将计算流体动力学（CFD）与离散元法（DEM）集成，结合了 LIGGGHTS® DEM 代码和 OpenFOAM® CFD 包，用于高级流体颗粒仿真。 |
| [Code_Aster](https://code-aster.org/spip.php?rubrique21) | Fortran/Python | 开源 | Code_ASTER 是一个开源软件套件，主要用于土木工程和工业领域的结构力学中的有限元分析和数值仿真。 |
| [deal.II](https://www.dealii.org/) | C++ | 开源 | 一个支持创建有限元代码的 C++ 软件库，拥有一个开放的用户和开发者社区。 |
| [FEATool Multiphysics](https://github.com/precise-simulation/featool-multiphysics) | Matlab | 开源 | FEATool Multiphysics 是一个集成的多物理分析仿真平台，提供易用的图形界面和用于 1D、2D 和 3D 几何建模、自动网格划分、物理求解器以及多种预定义物理方程的集成工具。 |
| [FEBio](https://github.com/febiosoftware/FEBio) | C++ | 开源 | FEBio 是一个专为生物力学应用设计的开源非线性有限元求解器，提供专门的建模场景、本构模型和边界条件，用于解决计算生物力学中的复杂 3D 问题。 |
| [FEniCS](https://fenicsproject.org/) | C++ | 开源 | FEniCS 是一个用于高效解决偏微分方程（PDE）的开源计算平台，采用有限元方法（FEM），提供高层次的 Python 和 C++ 接口，支持从笔记本电脑到高性能计算系统的广泛平台。 |
| [FreeFEM](https://github.com/FreeFem/FreeFem-sources) | C++ | 开源 | FreeFEM 是一个在非线性多物理系统中使用有限元方法求解偏微分方程的求解器，支持 2D 和 3D，具有快速插值算法和处理多个网格数据的专用语言。 |
| [JuliaFEM](https://github.com/JuliaFEM/JuliaFEM.jl) | Julia | 开源 | JuliaFEM 是一个允许在计算集群上分布式处理大型有限元模型的软件库，设计目标是从单一服务器扩展到数千台计算机。 |
| [MFEM](https://github.com/mfem/mfem) | C++ | 开源 | MFEM 是一个模块化并行 C++ 库，支持有限元方法，目标是为高性能可扩展的有限元离散化研究和应用开发提供支持，适用于从笔记本电脑到超级计算机的各种平台。 |
| [MYSTRAN](https://github.com/MYSTRANsolver/MYSTRAN) | Fortran | 开源 | 对于熟悉 1970 年代 NASA（美国国家航空航天局）开发的流行 NASTRAN 计算程序的人来说，MYSTRAN 的输入格式将非常熟悉。许多为 NASTRAN 模型的结构分析可以在 MYSTRAN 中运行，几乎不需要修改。MYSTRAN 是一个独立的程序，采用现代 Fortran 95 编写。 |
| [NASTRAN-95](https://github.com/nasa/NASTRAN-95) | Fortran | 开源 | NASTRAN 是 NASA 的结构分析系统，一个于 1970 年代早期完成的有限元分析程序。它是第一款此类软件，开启了计算机辅助工程的大门。 |
| [Netgen/NGSolve](https://github.com/NGSolve/ngsolve) | C++ | 开源 | Netgen/NGSolve 是一个高性能的多物理有限元软件，广泛用于分析固体力学、流体动力学和电磁学模型。通过其灵活的 Python 接口，可以轻松实现新的物理方程和求解算法。 |
| [OpenFoam](https://github.com/OpenFOAM?tab=repositories) | C++ | 开源 | OpenFOAM 是一个免费、开源的计算流体动力学（CFD）软件包，广泛应用于工程和科学领域。OpenFOAM 提供了广泛的功能，用于解决涉及化学反应、湍流和热传递的复杂流体流动问题。 |
| [pyNastran](https://github.com/SteveDoyle2/pyNastran) | Python | 开源 | pyNastran 是一个用于处理多种 Nastran文件格式（BDF、OP2 和 F06）的 Python 库，提供了在 Nastran 中处理模型、查看文件内容和简化仿真的工具。 |

---
# 后处理与可视化

*用于分析仿真结果、可视化数据及从仿真输出中提取关键见解的软件。*

| Tool Name | 编程语言 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [abaqusPython](https://github.com/quisten/abaqusPython) | Python | 开源 | 一组常用的Abaqus脚本和其他有用的工具集。 |
| [ParaView](https://github.com/Kitware/ParaView) | C++ | 开源 | 基于可视化工具包（VTK）的开源、多平台数据分析和可视化应用程序。 |
| [PyQus](https://github.com/JorgeDeLosSantos/pyqus) | Python | 开源 | 用于后处理Abaqus ODB文件的Python代码。 |
| [pyNastran](https://github.com/SteveDoyle2/pyNastran) | Python | 开源 | pyNastran是各种Nastran文件格式（BDF、OP2、OP4）的接口库。使用BDF接口，您可以在不担心字段格式的情况下读取、编辑和写入Nastran几何体。还执行了许多检查以验证模型的正确性。使用OP2接口，您可以快速高效地读取大文件的结果，并提取结果数据子集，生成OP2/F06结果文件。 |
| [Simright Viewer](https://www.simright.com/apps/simright-viewer) | Web | 商业 | 基于网页的CAD/CAE模型查看器，用于创建和分享3D快照。 |

---

# 优化

*用于优化和设计探索的工具，通过迭代模型参数提升性能并满足设计标准。*

| Tool Name | 编程语言 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [CasADi](https://github.com/casadi/casadi) | Python | 开源 | CasADi是一款用于非线性优化和算法微分的开源工具，能够快速高效地实现各种数值最优控制方法，适用于离线和非线性模型预测控制（NMPC）。 |
| [OpenMDAO](https://github.com/OpenMDAO/OpenMDAO-Framework) | Python | 开源 | 一款用于系统分析和多学科优化的开源高性能计算平台，基于Python编写。 |
| [opti4Abq](https://github.com/mengomarlene/opti4Abq) | Python | 开源 | 适用于Python2和ABAQUS的优化方法。 |
| [ToOptiX](https://github.com/ldslpm/ToOptiX) | Python | 开源 | 用于多物理拓扑优化的工具。 |
| [YALMIP](https://github.com/yalmip/YALMIP) | MATLAB | 开源 | MATLAB优化建模工具箱。 |

---

# CAE中的AI

*利用人工智能和机器学习增强CAE工作流程的各个方面，包括模型生成、优化和决策。*

| Tool Name | 编程语言 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [CAE Simulation Expert](https://chatgpt.com/g/g-BLkzsyrRZ-cae-simulation-expert-ansys-fluent-ls-dyna-abaqus) | 自然语言 | ChatGPT Plus | CAE仿真专家，提供详细的技术性回答。 |

---

# 工具与实用程序

*辅助CAE工作流程各个方面的工具，如文件转换、脚本编写和数据交换。*

| Tool Name | 编程语言 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [abqpy](https://github.com/haiiliin/abqpy) | Python | 开源 | abqpy是一个提供Abaqus脚本编写类型提示的Python包，允许在不直接访问Abaqus的情况下流畅地编写脚本，并包含简单的API以执行Abaqus命令，实现从一个Python脚本中构建模型、提交作业和提取数据。 |
| [FEconv](https://github.com/victorsndvg/FEconv) | Python | 开源 | FEconv可以将有限元（FE）网格转换为多种商业文件格式。它还可以转换有限元类型和/或执行一些带宽优化。 |
| [nastran-find](https://github.com/setvisible/nastran-find) | Python | 开源 | 浏览Nastran输入文件的解决方案。 |
| [odb2vtk](https://github.com/Liujie-SYSU/odb2vtk) | Python | 开源 | 将Abaqus ODB文件转换为VTK格式以供Paraview可视化使用。 |
| [ODB2VTKplus](https://github.com/Liu-Qingbin/ODB2VTKplus) | Python | 开源 | 另一种Python版的odb2vtk工具。 |
| [ODB2VTK](https://github.com/Arris-Composites/ODB2VTK) | C++ | 开源 | 另一种C++版的odb2vtk工具。 |
| [PyMAPDL Reader](https://github.com/ansys/pymapdl-reader) | Python/C++ | 开源 | 用于读取从MAPDL生成的二进制和ASCII文件的传统模块。ansys-mapdl-reader模块支持以下格式：*.rst *.rth *.emat *.full *.cdb |
| [Simright Converter](https://www.simright.com/apps/simright-converter) | Web | 商业 | 基于网页的CAE模型格式转换工具。 |
| [YJExchanger](https://www.simversus.com/solutions/yjexchanger) | SDK | 商业(国产自主可控) | 商业化的网格格式和CAE/CFD结果文件格式转换组件，支持Abaqus .inp .odb / Ansys .cdb .rst / Fluent .cas .dat .cas.h5 .dat.h5 .msh  / LS-DYNA .k .d3plot / Ensight .case (StarCCM+) / Nastran .bdf .op2 / Tecplot .dat .plt / VTK .vtk .vtu .vtp |
| [CEETRON Access](https://docs.techsoft3d.com/ceetron/latest/solve-access-mesh/access/index.html) | SDK | 商业 | CEETRON Access是Tech Soft 3D推出的工具包，提供了一种全面的机制，用于访问机械计算机辅助工程（MCAE）和计算流体动力学（CFD）中使用的各种主要商业有限元分析（FEA）软件系统的模型和解决方案结果文件的数据。 |

---

# 编辑器与插件

*提供语法高亮和支持编写CAE脚本及输入文件的编辑器与插件。*

| Tool Name | 平台 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [ATOM language-abaqus](https://atom.io/packages/language-abaqus) | Atom | 开源 | ATOM编辑器中的ABAQUS语言高亮插件。 |
| [ATOM language-nastran](https://atom.io/packages/language-nastran) | Atom | 开源 | 为NASTRAN文件添加语法高亮功能的Atom插件。 |
| [vim-abaqus](https://github.com/gradzikb/vim-abaqus) | Vim | 开源 | 适用于ABAQUS输入文件的Vim插件。 |
| [vim-lexer-lsdyna](https://github.com/tbhartman/vim-lexer-lsdyna) | Vim | 开源 | 用于Vim的LS-DYNA关键字输入文件语法分析器。 |
| [vim-radioss](https://github.com/gradzikb/vim-radioss) | Vim | 开源 | 用于RADIOSS输入文件的Vim插件。 |

---

# 文档工具

*与提取、管理和增强CAE软件文档相关的项目，提升可访问性和可用性。*

| Tool Name | 平台 | 开源/商业 | 描述 |
| --------- | -------- | ---------------------- | ----------- |
| [Abaqus-Documentation-Scraper](https://github.com/bendeaton/Abaqus-Documentation-Scraper) | Python | 开源 | Python脚本，用于从Abaqus HTML文档中提取关键字、参数和参数值。 |
| [Abaqus-Sublime](https://github.com/bendeaton/Abaqus-Sublime) | Sublime Text | 开源 | Abaqus有限元软件的Sublime Text语法高亮插件。 |
| [LS-DYNA-Sublime](https://github.com/bendeaton/LS-DYNA-Sublime) | Sublime Text | 开源 | LS-DYNA有限元软件的Sublime Text语法高亮插件。 |

---

# 总结

这个经过精心挑选的CAE框架、库和工具列表涵盖了CAE工作流程的整个范围，从CAD建模和网格划分到求解器、后处理和优化。随着CAE中的AI应用，仿真的未来正在被机器学习重塑，使得模型预测更快、数据驱动的优化更高效，并增强了工程流程中的自动化能力。
