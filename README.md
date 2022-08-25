# 3rd Workshop on DevOps support for Cloud FPGA platforms

## Why is cFDevOps important?

With the slowdown of Moore's law as we know it, the Cloud is resorting to heterogeneous, accelerated computing to satisfy the ever-increasing demand for performance and power efficiency. In just a few years, FPGAs have emerged as compute accelerators next to GPUs and are part of the standard offerings from many Cloud vendors. However, the development environment, deployment procedures, security measures, and monitoring tools are different for each platform and the portability of FPGA kernel designs remains limited. 

In this workshop, leading platform providers, designers of development environments, and developers present the state-of-the-art for Cloud FPGA platforms and explore opportunities and directions for future improvements from the developer's point of view. Instead of focusing on the performance and optimization of a specific application, the goal of this workshop is to highlight the challenges, which a Cloud application developer faces when designing, implementing, deploying, scaling and debugging Cloud services on Cloud FPGA platforms. 

A focus area for this years edition are end-to-end tool chains including compilation as well as the runtime environment for heterogeneous platforms. 


## Program

The workshop will take place on  **Thursday, September 1st, 14:00h - 18:00h GMT+1** (local Belfast time). The workshop will be held in a **hybrid mode**, allowing speakers and participants to join on-site or remote. Details will be updated here.


| **Time (GMT+1)**| **Title**                                                                                            | **Presenters**                                           |
|:---------------:|:---------------------------------------------------------------------------------------------------- |:-------------------------------------------------------- |
| 14:00           | Opening                                                                                              | *The Organizers*                                         |
|                 | **Session 1**                                                                                        | **Design time compilation**                            |
| 14:10           | Creating reusable MLIR abstractions for heterogeneous systems                                        |  Karl F. A. Friebel, TUD, Germany                       |
| 14:45           | Automatic Partitioning, Compilation, Deployment & Debugging of CNNs on Cloud FPGAs                   |  Burkhard Ringlein, IBM Europe, Switzerland            |
| 15:20           | Building a practical and developer friendly FPGA toolchain                                           |  Ulrich Drepper & Ahmed Sanaullah, Redhat Research     |
| 15:55           | **Break**                                                                                            |                                                        |
|                 | **Session 2**                                                                                        | **Run time management**            |
| 16:10           | The OmpSs@FPGA framework: developing heterogeneous applications fast and efficiently on FPGA-based clusters | Juan Miguel De Haro Ruiz, BSC, Spain             |
| 16:45           | (talk 2.2)                                                                                           |                                                        |
| 17:20           | (talk 2.3)                                                                                           |                                                        |
| 17:55           | Closing                                                                                              | *The Organizers*                                       |

## Registration

The workshop requires a registration, please register [here](https://fpl.org/registration/).

More details about FPL 2022 can be found [here](https://fpl.org).


## Talks

### Session 1: Design time compilation


#### Creating reusable MLIR abstractions for heterogeneous systems

by ***Karl F. A. Friebel, TUD, Germany***

**Abstract:**
MLIR is an LLVM framework for creating reusable compiler abstractions, centered around an extensible IR. Directed at current and future users of MLIR, this talk is about our experiences with MLIR for heterogeneous systems, which receive less attention in the upstream ecosystem. The talk provides insights into concrete design hurdles tool developers face, including those related to MLIR’s rapid evolution. For heterogeneous and reconfigurable systems, additional challenges make it particularly hard to create composable and reusable tool flows on the basis of MLIR. Through our current dialect stack for high-performance reconfigurable systems, we show how to cope with that complexity in MLIR, providing practical DevOps guidelines.


#### Automatic Partitioning, Compilation, Deployment & Debugging of CNNs on Cloud FPGAs

by ***Burkhard Ringlein, IBM Europe, Switzerland***

**Abstract:** FPGAs promise to accelerate ML and AI models while also being energy-efficient. However, nowadays DNN-to-FPGA tool chains are cumbersome to use, are limited to specific use cases and devices, and do mostly not support model parallelism using multiple devices. In this talk I will analyze the problems of the state of the art and propose with operation set architectures a concept to overcome these shortcomings. I will also present a prototype implementation, called DOSA, that enables a one-command partitioning, implementation and deployment of DNNs on multiple FPGAs as well as it's debugging features.

(Speaker Bio see below)


####  Building a practical and developer friendly FPGA toolchain

by ***Ulrich Drepper & Ahmed Sanaullah, Redhat Research***

**Abstract:** Modern FPGA tooling is currently decades behind CPU tooling in terms of development and deployment support for workloads. A prerequisite for productivity on FPGAs is not just hardware expertise, but substantial amounts of it - thus making it inaccessible to a majority of developers, especially software developers. How do we bridge this massive gap between CPU support and FPGA support? Through leveraging the power of open source, machine learning and the tried and tested techniques of CPU tooling of course. In this talk, we give an overview of our ongoing projects aimed at building a practical and developer friendly FPGA toolchain. These projects include High Level Synthesis, Hardware Operating Systems, Place and Route, programming and runtime support, RTL simulation, and on-chip debugging.

**Speaker Bios:**
Ulrich Drepper is a Distinguished Engineer at Red Hat, working as part of the Red Hat Research team and concentrating on developing new technologies for high-performance computing (and machine learning specifically), mostly in collaboration with university groups. His main interests are in the areas of low-level technologies like machine and processor architectures, programming language, compilers, high-performance and low-latency computing. In addition he is interested in using statistics and machine learning for performance analysis of programs and security of application and OS environments.

Ahmed Sanaullah is a Senior Data Scientist at Red Hat, working as part of the Red Hat Research team. His current focus is on building open source tooling for Field Programmable Gate Arrays that enables developers to easily and efficiently create custom hardware solutions, regardless of prior hardware development expertise. He received his PhD in Computer Engineering from Boston University in 2019, where he was given the Outstanding CE Dissertation Award for his research on High Level Synthesis and Hardware Operating Systems.


#### The OmpSs@FPGA framework: developing heterogeneous applications fast and efficiently on FPGA-based clusters

by ***Juan Miguel De Haro Ruiz, BSC, Spain***

**Abstract:** t.b.a.

**Speaker Bio:**

Juan Miguel de Haro Ruiz received his BS degree in Informatics Engineering in 2018 and MS degree specialized in High Performance Computing in 2020 from Universitat Politècnica de Catalunya (UPC). He is a Ph.D. student at the Computer Architecture Department of UPC. He also works with the OmpSs@FPGA team and in the Designing RISC-V-based Accelerators for next generation Computers (DRAC) project at the Barcelona Supercomputing Center (BSC). In the OmpSs@FPGA framework, his work is focused on the hardware runtimes and accelerators implemented on the FPGA, as well as the communication between FPGAs.



### Session 2: Run time management

(Details will be available soon).


## Organizers

#### Christian Pilato, Politecnico di Milano, Italy

Christian Pilato is an Assistant Professor at Politecnico di Milano. He was a Post-doc Research Scientist at Columbia University (2013-2016) and USI (2016-2018). He was also a Visiting Researcher at NYU, TU Delft, and Chalmers University of Technology. He has a Ph.D. in Information Technology from Politecnico di Milano (2011). His research interests focus on the design, optimization, and prototyping of heterogeneous system-on-chip architectures and reconfigurable systems, with emphasis on memory and security aspects. Starting from October 2020, he is the Scientific Coordinator of the H2020 EVEREST project. He served as program chair of EUC 2014 and will be the program chair of ICCD 2022. He is also serving in the program committees of many conferences on EDA, CAD, embedded systems, and reconfigurable architectures (DAC, ICCAD, DATE, CASES, ASPDAC, FPL, ICCD, etc.) He is a Senior Member of IEEE and ACM, and a Member of HiPEAC.

#### Jeronimo Castrillon, Technische Universität Dresden, Germany

Jeronimo Castrillon is a professor in the Department of Computer Science at the TU Dresden, where he is also affiliated with the Center for Advancing Electronics Dresden (CfAED). He is the head of the Chair for Compiler Construction, with research focus on methodologies, languages, tools and algorithms for programming complex computing systems. He received the Electronics Engineering degree from the Pontificia Bolivariana University in Colombia in 2004, his masters degree from the ALaRI Institute in Switzerland in 2006 and his Ph.D. degree (Dr.-Ing.) with honors from the RWTH Aachen University in Germany in 2013. In 2014, Prof. Castrillon co-founded Silexica GmbH/Inc, a company that provides programming tools for embedded heterogenous architectures, now with Xilinx/AMD.

#### Chris Kachris, inaccel, Greece

Chris Kachris the founder and CEO of InAccel that helps companies speedup their applications using hardware accelerators (FPGAs) in the cloud or on-prem. Inaccel, using a unique FPGA orchestrator, allows scalable deployment of FPGA clusters. Chris holds a Ph.D. from Delft University of Technology. He has published more than 70 papers in international journals and conferences with more than 1800 citations. He has over 15 years of experience on FPGAs and he is the editor of the book Hardware Accelerators in Data Centers.

#### Christoph Hagleitner, IBM Research Europe, Switzerland

Christoph Hagleitner leads the cloudFPGA project at the IBM Research Europe Lab (ZRL) in Ruschlikon, Switzerland. He obtained a Ph.D. degree for a thesis on CMOS-integrated Microsensors from ETH, Zurich, Switzerland in 2002. In 2003 he joined IBM Research to work on the system architecture of a novel probe-storage device (“millipede”-project). In 2008, he started to build up a new research group in the area of accelerator technologies. The team initially focused on integrated accelerator cores and gradually expanded its research to heterogeneous computing systems and their applications.

#### Dionysios Diamantopoulos, IBM Research Europe, Switzerland

Dionysios Diamantopoulos is a Research Scientist in the Cloud & AI Systems Research department of IBM Research Europe. Dionysios holds a D.Eng. from CEID/University of Patras (2009) and a PhD from ECE/Technical University of Athens (2015). His research is disseminated in one book chapter and more than 30 publications in international conferences and journals. He is the co-inventor of four filed patents and one pending (USPTO). His research interests lie in the system-level specialization of heterogeneous platforms for the hybrid cloud era. He is a member of HiPEAC, IEEE, OpenPOWER and Technical Chamber of Greece.

#### Burkhard Ringlein, IBM Research Europe, Switzerland

Burkhard Ringlein is a Predoctoral Researcher in the Cloud & AI Systems Research department of the IBM Research Zurich Laboratory and pursues his PhD in cooperation with the Department of Computer Science, Computer Architecture of the Friedrich-Alexander University Erlangen-Nürnberg, Germany. As part of the cloudFPGA project, he is focusing on Distributed Reconfigurable Architectures in the context of High-Performance-Computing and AI Acceleration. 

#### Christian Plessl, Paderborn Center for Parallel Computing, Germany

Christian Plessl is Professor for Computer Science of Paderborn University and director of the Paderborn Center for Parallel Computing (PC²). His research is focussed on reconfigurable architectures, compilation and runtime systems and applications. Leveraging the longstanding expertise in FPGA acceleration at Paderborn University, PC² has for the first time deployed FPGAs in an HPC production system (Noctua) in 2018. This installation serves as a development platform for porting HPC codes and libraries to FPGAs.



## Contact

[Christian Pilato](https://pilato.faculty.polimi.it)

[Jeronimo Castrillon](https://cfaed.tu-dresden.de/ccc-staff-castrillon)

[Burkhard Ringlein](https://researcher.watson.ibm.com/researcher/view.php?person=zurich-NGL)




