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
<!-- page_number: true -->
<!-- _class: lead -->

## Lecture 1: Operating System Overview

### Section 4: Operating System Structure

<br>
<br>

Ju Ren

<br>
<br>

Fall 2022

---
<style scoped>
{
  font-size: 32px
}
</style>
## Simple Structure
MS-DOS: Application and OS mixed together (1981–1994)
- **Not split into modules**
- Written primarily in assembly language
- No security

![bg right:50% 100%](./figs/msdos.png)


---
<style scoped>
{
  font-size: 32px
}
</style>
## Monomer Hierarchy
Divide the monolithic OS into **multiple layers** (levels)
- Each layer builds on top of the lower layer
- The bottom layer (layer 0), is the hardware driver
- The highest layer (layer N) is the user interface
- Each layer uses only the functions and services of the lower layer

![bg right:45% 100%](./figs/multi-level-os-arch.png)


---
<style scoped>
{
  font-size: 32px
}
</style>
## Micro Kernel Structure (Micro Kernel)
- **Move kernel functions to user space as much as possible**
- Communication between user modules uses message 
- Benefits: flexible/safe...
- Cons: performance
- LPC: Local procedure call 
- HAL: Hardware abstraction layer 
![bg right:35% 100%](./figs/microkernel-arch.png)

---
<style scoped>
{
  font-size: 32px
}
</style>
## Exokernel
- Let the kernel allocate physical resources to multiple applications, and let each program decide what to do with those resources
- Programs can link to the operating system library (libOS), which achieves the OS abstraction
- **Separation of protection and control**
- Distributed shared memory(DSM)

![bg right:40% 100%](./figs/exokernel-arch.png)


---
<style scoped>
{
  font-size: 32px
}
</style>
## Virtual Machine Structure
The virtual machine manager converts a single machine interface into many virtual machines, each virtual machine is an effective copy of the original computer system and can execute all processor instructions

![bg right:45% 100%](./figs/vmm-arch.png)

---
## Virtual Machine Structure


![w:1000](./figs/vmm-arch-view2.png)

---
## Relationship Between Application Running and OS Abstraction + Architecture

![w:1100](./figs/os-env.png)