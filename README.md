# CS232: Computer Organizations
[Pace University](http://www.pace.edu)

Course Staff
* Instructor: [Dr. Jun Yuan](http://csis.pace.edu/~jyuan2/)
* Teaching Assistant: [Ms. Iris Nguyen](mailto:nn61181n@pace.edu)

**The content of this course changes as technology evolves**, to keep up to date with changes [follow me on GitHub](https://github.com/jyuan2pace/CS232S21).

* Section 20102. Spring 2021
* Lecture: Monday & Wednesday, 3:30 PM, [Lecture Zoom Link](https://pace.zoom.us/j/6313313504?pwd=bUJtV3NUUlBiZVNKTThTRHBoMi84Zz09) 
* Recitation: Friday, 2:00 PM, [Recitation Zoom Link](https://pace.zoom.us/j/99718900621?pwd=QXM2VE5QYmY4YkVPN1RNNG5mWnp6Zz09) 
* Make an appointment with course staff: [Scheduling Jun's office hours](https://slotted.co/junsofficehours2021s) or [Scheduling Iris's office hours](https://slotted.co/irisofficehour2021s)

# Course Description

This course facilitates the development of a deep understanding of the hardware environment of computing devices and the interface it provides to the associated software. Students need to understand computer organization to develop software artifacts that can achieve high performance through their awareness of concurrency, consistency, parallelism, and latency. They will acquire an understanding and appreciation of a computer system’s characteristics, performance, interactions, and functional components as well as the challenge of harnessing parallelism to sustain performance improvements. In selecting a system to use, students will be able to understand the tradeoff among various components, such as CPU clock speed, cycles per instruction, memory size, average memory access time, pipelining, vector processing, and multiprocessors, and multicomputers.

# Textbook

* [**Required**] [DIS] Dive into Systems https://diveintosystems.org/
* [**Recommended**] [CSAPP] Computer Systems: A Programmer's Perspective (2nd Edition) (ISBN-10: 0136108040)
* [**Recommended**] [CPABG] C Programming: Absolute Beginner's Guide, 3rd ed., Aug 2013, (ISBN 978-0789751980)
* [**Recommended**] [TECS] The Elements of Computing Systems: Building a Modern Computer from First Principles (ISBN:9780262640688)

# Objectives

* Demonstrate how to convert numerical data from one format to another.
* Discuss the many equivalent representations of computer functionality, including logical expressions and gates, and use mathematical expressions to describe the functions of simple combinational and sequential circuits.
* Design the basic building blocks of a computer: arithmetic-logic unit (gate-level), registers (gate-level), central processing unit (register transfer-level), and memory (register transfer-level).
* Write and analyze Assembly language program segments.
* Explain why instruction set architecture and stored program concepts are important design principles.
* Describe and show the relative utility of how negative integers are stored in sign-magnitude and two's-complement representations.
* Explain how fixed-and floating-point number representations affect accuracy and precision.
* Understand the basic concepts of interrupts/exceptions and explain how interrupts are used to implement I/O control and data transfers.
* Describe instruction-level and data-level parallelisms, and pipeline hazards and how they are managed.
* Explain how instructions are represented at both the machine and the Assembly language levels.
* Identify and discuss the main types of memory technology (e.g., SRAM, DRAM, flash, and magnetic disk) and their relative costs and performance.
* Analyze and describe how the use of memory hierarchy (e.g., cache, main memory, and virtual memory) is used to reduce effective memory latency.
* Understand how a program’s locality of reference property supports memory hierarchy design.

# Syllabus
This syllabus presents the expected class schedule, due dates, and reading assignments. [Check current syllabus](https://docs.google.com/document/d/1ewasRZJzhbFVL1rA_OBn9k0KxcrCHMNX3U_9yh4rO6E/edit?usp=sharing). Check this page often for the most up-to-date schedule.

# Live Schedule
Week|Content|Recording|Reading|Recitation|Deadline
---|---|---|---|---|---
[Week 1](https://kami.app/mft48ZLYCHKN)<br>First class on 01/25/2021 | **Week 1: Course Intro and Logistics** <ul><li>Part 1.1: Course Overview<li>Part 1.2: Admin and Logistics <li>Part 1.3: Intro to binaries <li>Part 1.4: 2's complements <li>Part 1.5: Number systems and number conversion</ul> |<ul><li>[1-1 Course Overview & Logistics](https://pace.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=2db6effe-25a1-49cd-b0a1-acbc00061b19) <li>[1-2 Intro to binaries and number systems](https://pace.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=081f3834-634f-4311-8631-acbd017877cc) <li>[1-3 Recitation](https://pace.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=3709bc2c-5355-4d08-baec-acbf014bb3ee)</ul>|<ul> <li> [Syllabus](https://docs.google.com/document/d/1ewasRZJzhbFVL1rA_OBn9k0KxcrCHMNX3U_9yh4rO6E/edit?usp=sharing) <li>[Chapter 4 through 4.4.1](https://diveintosystems.org/singlepage/#_binary_and_data_representation) </ul>| [Problems](https://docs.google.com/document/d/1hlvTQsoCmB3ErDjWcwicJHDQbfr0NtH8hGALLUAmzP4/edit?usp=sharing) | None
[Week 2](https://kami.app/cgYx9c4wGJht)<br>Week of 02/01/2021 | **Week 2: Toward C** <ul><li>	Part 2.1: IO and Compilation <li>Part 2.2: C types and Declaration <li>Part 2.3: Conditionals and Loops<li>Part 2.4: Functions <li>Part 2.5: Arrays and strings</ul> |<ul><li>[2-1. Wrapping up hex and moving to C](https://pace.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=60346ef7-08f6-4e1d-800a-acc30001fa62) <li> [2-2. C vs Java, Part 1](https://pace.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=b99b7ced-f269-4a76-900c-acc5000b1948) <li> [2-3. Recitation](https://pace.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=b7cbfa2f-1cbb-4fa8-9bc9-acc601521a15) </ul>|<ul> <li>[Chapter 1 through 1.6](https://diveintosystems.org/singlepage/#_by_the_c_by_the_c_by_the_beautiful_c) <li>[Chapter 3.1 gdb](https://diveintosystems.org/singlepage/#_debugging_with_gdb)</ul>|[C Exercises](https://docs.google.com/document/d/1yEP5bcozTSk26ptMx6wmn90KUhoCmDtMcVNuHHp0ZzM/edit?usp=sharing)  | <ul><li>Assignment#1 due 02/06/2021 <li> [Assignment#2](https://docs.google.com/document/d/1hpqOXL2VkUTMShf0ccZCpknYUOlQipPwySXDXFNAGmw/edit?usp=sharing) is out </ul>
# Hands-out



