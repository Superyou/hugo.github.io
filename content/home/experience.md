---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: The Control Flow Integrity on RISC-V ISA
    company: Alibaba Group U.S.
    company_url: ''
    company_logo: alibabagroup-icon
    location: Sunnyvale, CA
    date_start: '2022-05-16'
    date_end: '2022-08-19'
    description: |2-
        Responsibilities include:
        * Qemu profiling on a branch landing scheme
        * Proposed two extension on branch landing scheme
        * Designed a workflow to evaluate the proposed extension

  - title: The Reversible Coherence Protocol
    company: University Southern California
    company_url: ''
    company_logo:  usc-7
    location: Los Angeles, CA
    date_start: '2018-09-01'
    date_end: '2021-11-01'
    description: |2-
        * Supervised by Xuehai Qian, Purdue University
        * Analyzed resent defense strategy like InvisiSpec and CleanupSpec;
        * Designed a buffer-based Undo approach to mitigate the transient speculation flaw.
        * Extended the current memory coherence protocol to support the merging and purging requests in our design.

  - title: GPU Power Virus Projec
    company: University Southern California
    company_url: ''
    company_logo:  usc-8
    location: Los Angeles, CA
    date_start: '2018-04-01'
    date_end: '2018-11-01'
    description: |2-
        * Supervised by Zhibin Yu and Xuehai Qian
        * Used genetic algorithm to automatically generate extremely high power consumption.
        * Modified gpgpusim simulator to trace the access pattern for gpgpu simulations.
  
  - title: Implementation of BNN on different platforms
    company: Cornell University 
    company_url: ''
    company_logo:  cornell
    location: Ithaca, NY
    date_start: '2016-06-01'
    date_end: '2016-09-01'
    description: |2-
        * Supervised by Zhiru Zhang
        * Implemented both the hardcore and softcore of the BNN network on an FPGA hardware.
        * Coded for the interface to connect the Rocket chip softcore with the BNN accelerator.
        * Used High Level Synthesis tool Stratus to utilize limited resources to implement the project.
  
  - title: Vehicular behavior algorithm analysis |
    company: Tsinghua University 
    company_url: ''
    company_logo:  Tsinghua
    location: Beijing, China
    date_start: '2015-09-01'
    date_end: '2017-07-01'
    description: |2-
        * Supervised by Shouyi Yin
        * Used deep learning algorithms to analyze human behavior while driving a vehicle.
        * Used the deep learning platform “tensorflow” to solve traditional problems, e.g. MNIST classification.
        * Investigated the mechanism behind deep learning algorithms.


design:
  columns: '2'
---
