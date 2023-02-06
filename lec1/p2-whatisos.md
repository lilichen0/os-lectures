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


## Lecture 1: Operating System Overview
### Section 2: What is an Operating System

<br>
<br>

Ju Ren

<br>
<br>

Fall 2022

---

## The Definition of OS 

No accepted precise definition

   The operating system is a kind of system **software** that **manages hardware resources**, controls programs running, improves human-machine interface, and **provides support for application software**
 
<!--bg right 100%--> 
![bg right:48% w:600](./figs/os-position.png)

Cnnects the past and the future

---

## OS is a Control Program
- A system software
- Executes the program, **provides services to the program**
- Controls program execution process, **prevents errors**
- **Facilitates the user** to use the computer system

![bg right:48% w:600](./figs/os-position.png)

---
<style scoped>
{
  font-size: 32px
}
</style>
## OS is a Resource Management Program
- **Middle layer** between application and hardware
- **Manages** various hardware and software resources
- **Service** for accessing hardware and software resources
- **Resolves access violations** to ensure fair usage

![bg right:48% w:600](./figs/os-position.png)

---

## Software Classification in OS

- Shell - command line interface
- GUI – graphical user interface
- Kernel – the internals of OS

![bg right:45% w:600](./figs/sort-of-os.png)

---
## uCore/rCore Teaching OS Kernel

![w:700 ](./figs/ucorearch.png)


---
## Abstraction of OS Kernel

![w:700](./figs/os-abstract.png)


---
## Abstraction of OS Kernel

![w:700](./figs/run-app.png)

---
## Characteristics of OS Kernel

- **Concurrency**: There are multiple running programs in the computer system at the same time
- **Sharing**: "Simultaneous" access to mutual exclusion between programs to share various resources
- **Virtual**: Each program "owns" an entire computer
- **Asynchronous**: The completion time of the service is uncertain and may fail

---
## Your Understanding of OS Kernel

### The requirements of user/application for OS?

---
## Your Understanding of OS Kernel

### The requirements of user/application for OS?
- Efficient -- easy to use
- Powerful operating system services -- simple interface?
- Flexibility -- security ?


---
## Why Study This Course

- Can understand how the software and hardware behind the computer case work
- Can learn software and hardware infrastructure
- Can find and fix difficult bugs

<!-- 如果你花费大量时间来开发，维护并调试应用程序，你最终还是要知道大量操作系统的知识 -->