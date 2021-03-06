---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---
Research at Yale:
==================
## Asynchronous System Services for GPUs and Formalizing Asynchronous Programming Model: In progress

The usecase for this work is Asynchronous system services for GPUs. Providing asynchronous support is as it is non-intuitive. With the complex GPU programming model, that is emphasized further. However GPUs will benefit from these direct access system service i.e. without going through a beefy CPU. The benefits will be increased system utilization byoverlapping operation latency with useful work and hence, improving performance and throughput. Asynchrony is the way to achieve these benefits.
1. Primarily focussing on identifying guarantees that a formal specification for the asynchronous programming model should provide.
1. Specifically working on identifying the correctness condition for asynchronous operations at the moment on a GPU.
1. Also identifying the changes GPU-CPU programming model would require in wake of providing asynchronous system calls for GPUs.
1. Working on identifying opportunities and performance benefits for reordering independent asynchronous and synchronous system calls across GPUs.

## Standalone Control Plane Abstractions for GPUs
Motivating the need for GPUs as standalone resources in disaggregated systems and how asynchrnous system services will benefit direct accelerator-accelerator communication without going through the CPU.

Projects at Yale:
======================
1. Implemented a Similarity Detection Tool to identify computational clones in cognitive brain models. 
1. Added support for asynchronous system calls in MCertiKOS - A verified layered Operating System :http://flint.cs.yale.edu/certikos/
1. Added support for asynchronous system IO in Theseus - A Rust based OS written to shift OS responsibilities to the compiler. : https://github.com/theseus-os/Theseus
1. Implemented a SAT Solver based on  Davis–Putnam–Logemann–Loveland Algorithm and Clause Learning Optimization.
1. Studied various robot system architectures and developed a predator-prey model based game based on Atlantis architecture.

Work done while at NVIDIA:
======================
<strong>
[Certain projects cannot be enlisted in detail because of the NDA act of Nvidia].</strong>

1. I had added MMA support in the compiler frontend as well for Ampere.
1. My most recent work prior to that (2017-) had been on adding  functional and performance support in the compiler backend for the newly added perf-critical deep learning features that accelerated deep learning computations in Turing. These were MMAs exposed in CUDA 10.0 and CUDA 10.1.
1. I explored the reuse and usage-improvement of the newly added hardware features such as the uniform register files for obtaining performance benefits. These are register files designed to hold values common across all threads in a warp. I was exploring more usage opportunities for these files that can benefit if the existing conservative candidate selection is relaxed. I was also exploring ways to relax the current stringent candidate selection such as no high latency converts should be needed or only cohesive read-write patterns are allowed.
1. I had also added most of the encoding support in Turing for which I was marked the Subject Matter Expert.
1. Additionally, I had redesigned a framework that enables the onset of the machine code generation of new instructions once released by architecture inside the compiler backend. I was marked Subject Matter Expert for this as well.


Older Projects
=================================================

## Opt - Gen : Compiler Optimizer Generator
  <strong> Institution : Indian Institute of Technology, Bombay, India </strong>   
  Short Description:  
    The project aimed in automatic generation of compiler optimizers given the local and global equations for Data Flow Analysis (DFA) and expected transformation.(E.g. Generate an optimizer using a modified live variable analysis for dead code elimination.)
    The existing version supported only Intra-procedural DFA and was inefficient in terms of performance.
    The developed solution improved the performance for Intra-procedural DFA by using an optimized method for the calculation method involved in DFA.
    Also, the developed solution provided support for Inter-procedural DFA entirely from scratch.
    It also included study and support of live pointer analysis.
    *Input Specification language: Opt-Gen included providing the equations for DFA calculations to the optimizer generator in a specific format. This format was the input specification language. The scanner and parser for file written in this language were custom-written and the output of these was further used in developing the generator.


## Cyclops: An objective image analysis algorithm

  <strong> Institution : Nvidia Graphics Pvt. Ltd, Pune, India </strong>   
  Short Description:  
    Existing image analysis techniques included subjective(human intervention) analysis and also suffer the limitation of inability to compare images which are rendered on different GPU architectures(due to difference in precision).
    Cyclops allows analysis of images rendered across different GPU architectures and is completely objective.
    It uses a human visual system(HVS) compliant color space to identify corruptions region wise and for complete image.
    It saves 336 human hours/employee/year for the organization.
    Preliminary learning was also induced in Cyclops to identify run to run variations in grass/hair etc to avoid marking them as corruptions without missing actual corruptions.
#### <strong>Note: </strong> An ISF (Invention Submission Form) was filed under NVIDIA Graphics Pvt. Ltd. and paper was submitted and reviewed at Nvidia Technical Conference-2015.

## Anti-aliasing validation solution
  <strong> Institution : Nvidia Graphics Pvt. Ltd, Pune, India </strong>   
  Short Description:  
  Developed a solution using edge-maps to differentiate between differently applied AA settings.

## No reference/  Reduced reference image analysis

  <strong> Institution : Nvidia Graphics Pvt. Ltd, Pune, India </strong>   
  Short Description:
  The project aimed at image analysis without a reference image. Detection of motion blur without reference image as an expected blur separately from gaussian blur(corruption) completed. Determination of sharpness of different parts of an image along with saliency map identification without a reference image was completed.

## Duplicate and missed frame identification

  <strong> Institution : Nvidia Graphics Pvt. Ltd, Pune, India </strong>   
  Short Description:  
  The solution identifies if any frame was missed or duplicated when grabbed from a stream/APIC.


## Parallelization of Scientific Software 

  <strong> Institution : Nvidia Graphics Pvt. Ltd, Pune, India </strong>   
  Short Description:  
The project aimed using data extracted from meteorological visualizations to aid in improving the accuracy of predictions using decision problem(Propositional Satisfiability(N-SAT) was used). A scalable SAT clause developer and eliminator was built.

