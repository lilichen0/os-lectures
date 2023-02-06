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

### Section 3: Historical evolution of the operating system

<br>
<br>

Ju Ren

<br>
<br>

Fall 2022

---
<style scoped>
{
  font-size: 29px
}
</style>
## Single User System

Single user systems (1945-1955)

- **Manual** wire/tape transfer for program entry
- The machine cost is much greater than the labor **cost**
- **OS = loader + libraries**
- Problem: **Low utilization** of expensive components

![bg right:45% 100%](./figs/history-single-user-system.png)

---
<style scoped>
{
  font-size: 29px
}
</style>
## Batch Processing System

Batch systems (1955-1965)

- **Tape/disk transfer** for program input
- Machine cost is greater than labor cost
- Operating System = loader + **program controller + output processor**
- Problem: Increased utilization compared to before

![bg right:45% 95%](./figs/history-batch-processing.png)

---
<style scoped>
{
  font-size: 29px
}
</style>
## Batch Processing System

**Batch processing** systems (1955-1965)

- Tape/disk transfer for program input
- Machine cost is greater than labor cost
- Operating system = loader + program controller + output processor
- Problem: Increased utilization compared to before

![bg right:45% 100%](./figs/history-batch-process-graph.png)

---

## Multi-programming System
<style scoped>
{
  font-size: 29px
}
</style>
**Multi-channel** programming system (1955-1980)

- multiple programs reside in **memory**
- Multiple programs use **CPU** in turns
- OS = loader + **program scheduling + memory management** + output management
- Evolution: Increased utilization compared to previous

![bg right:45% 100%](./figs/history-multiprogramming.png)

---
<style scoped>
{
  font-size: 29px
}
</style>
## Time-sharing System

Time-sharing system (1970-present)
- Multiple programs reside in memory
- Multiple programs use CPU time-sharing
- Operating system = loader + program scheduling + memory management + **interrupt handling** +...
- Evolution: Compared with the previous utilization rate, the interaction delay with the outside world is shortened

![bg right:45% 100%](./figs/history-timesharing.png)

---
## Multics OS

![](./figs/history-multics.png)

---
## Multics OS

![](./figs/multics-intro.png)

---
## Open UNIX

![bg 50%](./figs/unix-family.png)


---
## Linux Family

![bg 55%](./figs/linux-family.png)

---
## Personal Computer

Personal computer (1981- )
- Single user
- **Computer costs drop** so that CPU utilization is no longer a top concern
- Focus on **user interface and multimedia features**
- Operating system = loader + program scheduling + memory management + interrupt handling +...
- Evolution: **to the public**, old services and features don't exist, more and more security issues

![bg right:20% 100%](./figs/history-pc.png)

---
## MacOS Family

![bg 55%](./figs/macos-family.png)

---
## MacOS Family

![bg 55%](./figs/macos-family-history.png)

---
## Windows Family

![bg 70%](./figs/windows-family.png)

---
<style scoped>
{
  font-size: 28px
}
</style>
## Distributed Systems

**Distributed** System (1990- )
- Distributed multi-user
- Distributed system utilization is a concern
- The focus is on network/storage/compute efficiency
- OS = distributed (loader + program/OS scheduling + memory management)
- Evolution: to the public, towards **internet**, new challenges (unreliable/uncertain)

![bg right:45% 90%](./figs/history-ds.png)

---
## Android OS
- Cross-platform: supports Java applications
- Runtime: Android virtual machine
- Application framework: Simplifies application development


![bg right 90%](./figs/android-system-architecture.png)

---
<style scoped>
{
  font-size: 28px
}
</style>
## AIoT OS

AIoT system (2000- )
- Distributed **multi-device**
- Distributed system utilization/availability is a concern
- The focus is on network/storage/compute efficiency
- OS = distributed (program/OS scheduling + memory management + security/updates)
- Evolution: towards device, towards network, new challenges (unreliable/big data)


![bg right:45% 100%](./figs/history-aiot.png)

---
## Fuchsia OS

![bg 65%](./figs/fuchsia-os-intro.png)