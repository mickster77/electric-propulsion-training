# Electric Propulsion Training Sources

This page is a resource for NAVSEA engineers looking to develop the requisite knowledge and skills to understand, manage, and maintain projects involving electric propulsion or adjacent equipment.  Commentary and opinions provided are mine.

## Recommended Reading/Consumption List
### [Walter Lewin's 8.02 (Electricity and Magnetism) Lectures](https://www.youtube.com/playlist?list=PLyQSN7X0ro2314mKyUiOILaOC2hk6Pc3j)
>Walter Lewin's 8.02 video lectures are a series of engaging and visually rich physics lectures that cover the fundamental principles of electromagnetism, taught by the charismatic and energetic physicist, Walter Lewin.  
<cite>-ChatGPT<cite>

These lectures comprise 8.02, MIT's E&M Physics course, usually taken by freshmen during their second semester.  You will find, if you are like most engineers, that there are many things you have forgotten, or mis-remembered in the years since collage.  Approach the material assuming you don't know it and revisit these lectures every few years.

 **Objectives:**
Maxwell's Equations, Arcs/Corona/Partial Discharge

### [A Student's Guide to Maxwells Equations](https://www.danfleisch.com/maxwell/)
>"A Student's Guide to Maxwell's Equations" by Dan Fleisch is a comprehensive textbook that covers the fundamental laws of electromagnetism, including the four Maxwell's equations and relationships between electric/magnetic fields, charges, and currents, with numerous examples, exercises and an accessible writing style for undergraduate students with varying backgrounds in physics.  
<cite>-ChatGPT<cite>

 
This book is a fantastic, concise, walk through Maxwell's four equations.  Read it, do all the problems.

  **Objectives:**
Maxwell's Equations


### [Analysis of Electric Machinery and Drive Systems a.k.a. "Krause"](https://ieeexplore.ieee.org/book/5265638)
### Description:
>"Analysis of Electric Machinery and Drive Systems" by Paul C. Krause is a guide for electrical engineers and students that covers the fundamentals and advanced topics of electric machinery and drive systems, including magnetic circuits, transformers, AC machines, power electronics, and computer simulation, with clear explanations, illustrations, and practical examples to help build understanding.  
<cite>-ChatGPT<cite>

 
This book provides a solid introduction to electric machinery and the [DQ0 transform](https://en.wikipedia.org/wiki/Direct-quadrature-zero_transformation).  Work through the first chapter in detail, doing the math alongside and ahead of the author.  This will give help fully internalize the approach of equivalent circuit representations for motors and transformers.  Do the same for chapter 3.  

  **Objectives:**
DQ0 Transforms, Equivalent Circuit Models, Power Conversion, Motor Theory/Design, Generator Theory/Design

### [Design of Rotating Electrical Machines]((https://www.wiley.com/en-us/Design+of+Rotating+Electrical+Machines,+2nd+Edition-p-9781118581575))
>In one complete volume, this essential reference presents an in-depth overview of the theoretical principles and techniques of electrical machine design. This timely new edition offers up-to-date theory and guidelines for the design of electrical machines, taking into account recent advances in permanent magnet machines as well as synchronous reluctance machines.  
-<cite>Wiley</cite>

 
This book is relatively new.  It probably has the best illustrations of key concepts available in print.  It's description of flux leakage in chapter 4 is exceptional.

  **Objectives:**
Motor Theory/Design, Generator Theory/Design

### [Tutorial on Symmetrical Components](https://cdn.selinc.com/assets/Literature/Publications/White%20Papers/LWP0010-01_TutorialSymmetrical-Pt1_AR_20130422.pdf) and [Answer Key](https://selinc.com/api/download/100688)
>Symmetrical components and the per-unit system are two of the most fundamental and necessary types of mathematics for relay engineers and technicians. We must practice these techniques in order to fully understand and feel comfortable with them. This white paper provides both theoretical and real-world examples with questions that can be used to gain experience with symmetrical components.  
<cite>-Amberg and Rangel</cite>

 
Symmetrical components are a fundamental tool for evaluating and understanding many subtle aspects of rotating machinery performance, its not just for relay engineers.  It changed Henke's life.

  **Objectives:**
Symmetrical Component Analysis


## Recommended Formal Course Work
&nbsp;  
### [Naval Post-graduate School - Electric Ships Power Systems]((https://www.nps.edu/documents/103424449/106895289/ECE_ElectricShips.pdf/8bdd8bef-bd3c-4293-84c3-dd6d4903939b?t=1457388522000))
>Provides a solid engineering foundation which covers the fundamental concepts in electrical power conversion and electromechanical power conversion at the advanced level. This coherent program is obtained by taking a 4-graduate-course sequence which provides a mixture of instruction and computer-based laboratories offering students the opportunity to study the behavior and performance of power systems in a virtual environment.
>
>The 4-graduate-course sequence is extracted from the current set of graduate courses required to complete the Solid State Microelectronics and Power Systems specialization track for the MSEE Degree offered by the ECE Department.
>
>The four-course sequence is composed of:
>
>EC3130 - Electrical Machine Theory (4-2)  
>EC4130- Advanced Electrical Machinery Systems (4-2)  
>EC3150- Solid State Power Conversion (3-2)  
>EC4150- Advanced Solid State Power Conversion (4-1)
>
><cite>-NPS</cite>

 
This certificate program provides a solid basis for understanding electric propulsion systems.  Key skills/knowledge that will be gained:
* Analysis methods for common converter topology
* Reference frame transformation for rotating equipment
* Control methods for systems with motors driven by power conversion equipment

At a minimum candidates should possess solid familiarity with Maxwell's equations prior to pursuing this program to maximize value.

  **Objectives:**
DQ0 Transforms, Equivalent Circuit Models, Power Conversion, Motor Theory/Design, PID Control

### [MIT - Design of Electric Motors, Generators, and Drive Systems](https://professional.mit.edu/course-catalog/design-electric-motors-generators-and-drive-systems)
>This course focuses on the analysis and design of electric motors, generators, and associated power electronic drive systems, placing special emphasis on the design of machines for electric drives, including traction drives, drive motors for automated manufacturing (robots), material handling and drive motors for automotive, aircraft and marine propulsion systems, and associated power electronic drives. Participants will gain extensive hands-on experience by participating in computer-based laboratory exercises in a MATLAB-compatible, open-source scientific analysis tool called Octave. Participants will also engage in a hardware build session using an Infineon “Programmable System on Chip” (PSoC) 5LP to control a machine in our instructional laboratories.
<cite>-MIT</cite>

 
This is a very fast paced course.  It is a good follow to the NPS certificate program or previous training on or experience with motor, drive, and control theory.  At a minimum candidates should possess solid familiarity with Maxwell's equations and the DQO transform prior to taking this course to maximize value.

Based on discussions with the lead professor, in recent years they have worked to make the remote option as close as possible to the in person option.  For the physical lab work they provide the equipment via mail to the attendee and labs are worked remotely and in person together in realtime.  Given this, this course should be offered to qualifying engineers liberally.

 **Objectives:**
Maxwell's Equations, Poynting, DQ0 Transforms, Equivalent Circuit Models, Power Conversion, Motor Theory/Design, PID Control

## Recommended Informal Course Work

### [Fundamentals of Project Planning and Management](https://www.coursera.org/learn/uva-darden-project-management)
>This is an introductory course on the key concepts of planning and executing projects. We will identify factors that lead to project success, and learn how to plan, analyze, and manage projects. Learners will be exposed to state-of-the-art methodologies and to considering the challenges of various types of projects.  
<cite>-Coursera</cite>

 
This course probably won't teach much to a five-year NAVSEA engineer that they won't have already learned the hard way.  In other words, it's an incredibly valuable course to a first or second year engineer.  Covers all the basics: earned value, CPI, SPI, and the triangle of doom.

 **Objectives:** 
Project Management

## Learning Objectives

These resources were selected to build specific set of knowledge and skills frequently come up when dealing with electric propulsion components and systems.

**Electrical (Theory):**
* Maxwell's Equations
* Poynting
* DQ0 Transforms
* Equivalent Circuit Models
* Symmetrical Component Analysis
* Power Conversion
* Motor Theory/Design
* Generator Theory/Design
* Arcs/Corona/Partial Discharge  
&nbsp;  

**Electrical (Practical)**
* Insulation
* Magnetic Bearings
* Ampacity  
&nbsp;  

**Mechanical**
* Rotor-dynamics
* Bearings
* Stress/Strain
* Fastener Mechanics  
&nbsp;  

**Mathematical/Abstract**
* Fourier Transforms
* Sampling Theory
* Resonance
* PID Control
* Advanced Control  
&nbsp;  

**Boring (But Necessary)**
* Project Management
* Standard Contract Types