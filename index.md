---
layout: default_minimal_2col
title: Home
notitle: true
---

### About Me

I am an associate professor in the Department of Computer Science at
[Worcester Polytechnic
Institute](https://www.wpi.edu/academics/departments/computer-science) and the
Director of WPI's Cybersecurity Program. My work focuses on systems security
and performance, with an emphasis on the places where software, hardware, and
real-world constraints meet.

At WPI, my students and I are part of [The Cake Lab](https://cake.wpi.edu/).
We study how to make computing systems more secure, reliable, and predictable,
including embedded systems, firmware, GPUs, and shared computing
infrastructure.

Before joining WPI, I was a postdoctoral scholar at Penn State working with
[Prof. Patrick McDaniel](http://www.patrickmcdaniel.org/) and earned my Ph.D.
from the University of Massachusetts Amherst, where I was advised by [Prof.
Brian Levine](http://people.cs.umass.edu/~brian/).

### News

 - 05/01/2026: Congratulations to Vivek Jagadeesh, Charlie Engler, and Nick Golparvar for receiving WPI's Provost's MQP Award for their Major Qualifying Project. It was a pleasure to advise their work.
 - 05/01/2026: Congratulations to Daniel Reynolds for receiving the CS Ambassador Award.
 - 04/08/2026: Congratulations to Dr. Tongwei Ren for successfully defending his Ph.D. dissertation, "Securing Embedded System through Firmware Analysis and Transformations." It was a privilege to advise his doctoral work.
 - 12/04/2025: WPI launched a new [Bachelor of Science in Cybersecurity](https://www.wpi.edu/academics/study/cybersecurity-bs), an interdisciplinary program that brings together computer science, electrical and computer engineering, and hands-on security research.
 - 11/18/2025: Congratulations to Dr. Guin Gilman for successfully defending her Ph.D. dissertation, "Resource Scheduling for Concurrent Mixed-Priority Workloads on General Purpose GPUs." It was a privilege to advise her doctoral work.
 - 11/01/2025: Our paper ["'We just did not have that on the embedded system': Insights and Challenges for Securing Microcontroller Systems from the Embedded CTF Competitions"](https://dl.acm.org/doi/abs/10.1145/3719027.3765039) was published at ACM CCS 2025.
 - 08/13/2025: Our paper ["REVDECODE: Enhancing binary function matching with context-aware graph representations and relevance decoding"](https://www.usenix.org/conference/usenixsecurity25/presentation/ren) was published at USENIX Security 2025.

### Current Projects

I've had the opportunity to work on a number of interesting research projects
during my career. At WPI, my students and I are part of [The Cake
Lab](https://cake.wpi.edu/), where we work on systems security and
performance.

#### Securing Resource-Constrained Systems

Embedded and cyber-physical systems sit inside critical infrastructure,
vehicles, medical devices, industrial equipment, consumer electronics, and
smart devices. These systems often lack the abstractions and resources that
desktop and server defenses assume, such as virtual memory, abundant memory,
and flexible timing. My group studies how to provide stronger security
guarantees while respecting the constraints that make these platforms useful in
the first place.

This work includes defenses for embedded software and real-time systems, such
as [Kage](https://www.usenix.org/conference/usenixsecurity22/presentation/du)
(USENIX Security 2022),
[Silhouette](https://arxiv.org/abs/1910.12157) (USENIX Security 2020), and
[Recfish](http://drops.dagstuhl.de/opus/volltexte/2019/10739/) (ECRTS 2019).
More recently, our [embedded CTF
work](https://dl.acm.org/doi/abs/10.1145/3719027.3765039) (ACM CCS 2025)
studied what these competitions reveal about the practical challenges of
securing microcontroller systems.

#### Firmware and Binary Analysis

In many real systems, source code is unavailable. Instead, analysts must work
from firmware images or compiled binaries. My group develops techniques for
recovering useful program structure from binaries, comparing code across
firmware versions, and enabling security analysis or transformation when the
original source is unavailable.

Recent work includes
[REVDECODE](https://www.usenix.org/conference/usenixsecurity25/presentation/ren)
(USENIX Security 2025), which uses context-aware graph representations and
relevance decoding to improve binary function matching.

#### GPU Systems and Scheduling

GPUs are now shared infrastructure for machine learning, scientific computing,
cloud services, and other performance-critical applications. My group studies
how concurrent workloads interact on modern GPUs and how better scheduling can
improve performance, predictability, and isolation.

Recent work includes
[ReFINE](https://dl.acm.org/doi/abs/10.1145/3694906.3743331) (SPAA 2025), a
reactive and fine-grained scheduling framework for general-purpose GPUs. This
builds on earlier work studying GPU concurrency mechanisms under deep learning
workloads, including
[Performance 2020](https://cake.wpi.edu/assets/papers/gilman20_performance.pdf)
and [Performance 2021](https://arxiv.org/abs/2110.00459).

### Past Projects

Below are some of the previous projects I have had the privilege to work on. 

#### Secure Deep Learning

ML models are valuable intellectual property due to the investment and
expertise required to gather training data and construct the model. To
monetize these models, companies often make them available as a service through
APIs. At the same time, model owners often rely on hardware operated by cloud
providers or end users.

Our [Data-Free Model Extraction](https://arxiv.org/abs/2011.14779) work (CVPR
2021) demonstrated the feasibility of extracting models without knowledge of
the underlying training dataset. In our [trusted execution environment
study](https://arxiv.org/abs/2104.15109) (IC2E 2021), we identified
performance bottlenecks that complicate efforts to run models in trusted
execution environments.

#### Web Security and Privacy 

Domain names have become the Internet's de facto root of trust. In practice,
they are also a root of insecurity as common security systems depend on the
unfounded assumption that domain ownership remains constant; this leaves users
vulnerable to exploitation when domain ownership changes. In our
[Domain-Z](http://rjwalls.github.io/papers/domain-z-ieee.pdf) work (IEEE
Symposium on Security and Privacy 2016), we found that many seemingly
disparate security problems share a root cause in residual domain trust abuse.

In our [ad blocking study][imc] (IMC 2015), we studied the most popular ad
blocking software and examined the gap between how ad blockers are marketed
and how they behave in practice.

[imc]: http://rjwalls.github.io/papers/walls15_imc.pdf


#### Digital Forensics

Mobile phones can contain evidence that is invaluable for criminal
investigations, but forensic tools have often needed to be hand-tailored to
specific phone models. When no tool supports a target phone, investigators may
be forced to examine raw storage manually.

The [DEC0DE](https://github.com/umass-forensics/DEC0DE-forensics) project grew
out of our [mobile phone forensics work][decode] (USENIX Security 2011). It is
an inference engine that extracts meaningful information from raw byte streams.
[Liftr][liftr] (SPSM 2014) incorporates investigator feedback and relevance
graphs to improve the results of inference engines like DEC0DE.

[decode]: http://forensics.umass.edu/pubs/Walls.usenixSecurity.2011.pdf
[liftr]:http://forensics.umass.edu/pubs/varma.spsm.2014.pdf

#### Science of Security

One of the most ambitious projects I have been involved with was the 10-year
Cyber-Security Collaborative Research Alliance with the Army Research
Laboratory, Penn State, Carnegie Mellon, UC Riverside, UC Davis, and Indiana
University. The project's mandate was to develop a new science of security.

As part of this effort, I worked on foundations for representing operational
and environmental knowledge, including [work on ontologies][ontology1] (STIDS
2014), with the goal of reasoning about both current and future system states
to make better security decisions.

[ontology1]: http://rjwalls.github.io/papers/oltramari14_stids.pdf

### Selected Publications

Below is a partial list of my recent publications.

{% include pubs.html %}
