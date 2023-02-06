---
marp: true
theme: default
paginate: true
_paginate: false
header: ''
footer: ''
backgroundColor: white
---

<!-- theme: gaia -->
<!-- _class: lead -->

## Lecture 1 Operating System Overview
### Section 1 Course Overview & Teaching Arrangement

<br>
<br>

Ju Ren

<br>
<br>

Fall 2022

---

## Course Information

### Lecturer:
  - Ju Ren
  - Chen Yu

### Teaching assistant
  - Guan Haoyang, Tian Kaifu, Zhao Fangliang, He Kunpeng

---

## Class Information

### Time 
- Wednesday morning second session 09:50-12:15 (1-16 weeks)
### Place
- Fifth Teaching Building 5101

----

## Preliminary Knowledge

### Programming languages (Assembly, C, and Rust)
  - :( Not develop apps
  - :) Develop system programs

### Data structure
  - :) Just understand the basic data structure

---

## Preliminary Knowledge
### Principles of computer composition
  - :( Mr. Liu/Mr. Kang's RISC-V principle
  - :) Patterson's RISC-V Principles

### Compilation principle
  - :) It doesn't affect much if you haven't learned it
  - :( But you still need to know the high level language <–>RISC-V assembly language


---
<style scoped>
{
  font-size: 30px
}
</style>
#### Course reference
- [Course Slides](https://www.yuque.com/docs/share/4c39608f-3051-4445-96ca-f3c018cb96c7)
- Reference book
   * [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)
   - [In-depth understanding of computer systems](https://hansimov.gitbook.io/csapp/)
   - [RISC-V Reader Chinese version](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf)
#### Course practice: rCore tutorial book v3
- [Course practice reference book](https://learningos.github.io/rCore-Tutorial-Book-v3/)
- [Course practice code repository](https://github.com/rcore-os/rCore-Tutorial-v3)
- [API documentation for course practice code](https://github.com/rcore-os/rCore-Tutorial-v3#os-api-docs)

---

### Experiment Guide


#### uCore-RV-64

* Benchmark code repository ([lab](https://github.com/uCore-RV-64/uCore-RV-64-lab))
* Document repository ([doc](https://github.com/uCore-RV-64/uCore-RV-64-doc))
* Online document [entry](https://ucore-rv-64.github.io/uCore-RV-64-doc/index.html)
* Experimental reference answer repository ([answer](https://github.com/uCore-RV-64/uCore-RV-64-answer))
* Automatic test script repository ([test](https://github.com/uCore-RV-64/uCore-RV-64-test))
* Codespace development environment configuration script repository ([config](https://github.com/uCore-RV-64/uCore-RV-64-conf))

---

### Experiment Guide

#### rCore
- [Experimental documentation](https://github.com/LearningOS/rCore-Tutorial-Guide-2022S/)
- [API documentation](https://github.com/LearningOS/rCore-Tutorial-Guide-2022S/#os-api-docs-of-rcore-tutorial-code-2022s), [Experimental code](https:/ /github.com/LearningOS/rCore-Tutorial-Code-2022S)
- [Test cases](https://github.com/LearningOS/rCore-Tutorial-Test-2022S)

#### uCore and rCore experiments [Video] (https://www.yuque.com/docs/share/1b5b9260-8a80-4427-a612-78ec72b37e5f)

---

<style scoped>
{
  font-size: 32px
}
</style>


![bg right 100%](figs/ucorearch.png)
### OS Principles and Design Ideas

* Operating system structure
* Interrupts and system calls
* Memory management
* Process management
* Processor scheduling
* Synchronization mutex
* File system
* I/O subsystem



---
<style scoped>
{
  font-size: 32px
}
</style>
## Homework and Experiments

### Homework
   - Exercises

### Basic experiment
   - Design and implement operating system functions in Rust/C for RISC-V CPU
 
### Course design  
   - Big experiment

---
<style scoped>
{
  font-size: 30px
}
</style>

## Basic experiments
### Experiment 1: Basic support of the operating system
### Experiment 2: Address space
### Experiment 3: Process management and scheduling
### Experiment 4: File system and inter-process communication
### Experiment 5: Synchronizing mutex


---
<style scoped>
{
  font-size: 30px
}
</style>
## Curriculum Design (Big experiment)

### Various operating system related functions and extensions

- OS porting on various CPU platforms
   * RISC-V, x86-64, MIPS, ARM
- Driver development for various development boards
   * RaspBerry PI, U740, D1, etc.
   * GUI, driver, file system, network
- Perfection and improvement of the operating system kernel module
   * Kernel loadable modules, microkernels
   * Introduce asynchronous programming in the kernel

---
<style scoped>
{
  font-size: 30px
}
</style>
## Grade Evaluation

### Choice 1:
   - Complete experiment 1-5 on time: 30%
   - Midterm exam 30% + final exam 40% : 70%
### Choice 2:
   - Complete experiment 1-5 within four weeks (2022 spring experiment): 30%
   - Curriculum design (i.e., big experiment): 70%
     - Note: Students who choose the big experiment need to take the exam if they quit the course design later.

---
<style scoped>
{
  font-size: 30px
}
</style>
## Survey

[Course Selection Questionnaire for 2022 Fall Semester Operating System Course](http://oscourse2019.mikecrm.com/fPozIRL) (Access password: XxW21Ur1CF)

- Why do you want to take this course?
- How are you going to take this course?
- What are the learning requirements for your own courses?
- Are you willing to truthfully report whether you completed the experimental tasks independently?
- What knowledge and ability do you hope to acquire in the operating system class?
- Previous studies?