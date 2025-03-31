---
layout: ../../layouts/ProjectLayout.astro
title: "5-Stage Pipelined MIPS Datapath" 
description:  Implementation of a 32-bit 5 stage Pipelined MIPS Processor using RTL coding in Verilog
tags: ["Verilog", "MIPS32 architecture", "CPU Design"]
githubUrl: https://github.com/CougarBellinger/ECE369-Project
timestamp: 2024-12-9T02:39:03+00:00
featured: true
filename: pipelinedProcessor
---

# About
Repository to store ECE369 final project. This datapath was implemented using Verilog code, synthesized in Vivado, and ran on a xilinx FPGA board. We used hazard detection to delay the pipeline as well as forward dependant values. This datapath was designed to run a Sum of Absolute Differences (SAD) algorithm which determines the similarity of image blocks. The algorithm outputs the coordinates of the image block with closest similarity to the input block.

# Datapath:
[View Image](/datapath.png)

![Datapath](/datapath.png)


