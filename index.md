---
layout: default_minimal_2col
title: Home
notitle: true
---

### News

**Students!**: I am currently looking for motivated and qualified students. If
you are a WPI student, please send me an email or stop by. If you are outside
of WPI, I invite you to apply and then contact me. Use keyword fignewtons for a
more rapid response.

### About Me

I am an assistant professor in the Department of Computer Science at [Worcester
Polytechnic
Institute](https://www.wpi.edu/academics/departments/computer-science) and a
proud member of [The Cake Lab](https://cake.wpi.edu/) group. My current
interests focus on systems security and performance and my projects often lie
at the intersection of software and hardware. 

Previously, I was a postdoctoral scholar in Department of Electrical
Engineering and Computer Science at The Pennsylvania State University working
with [Prof.  Patrick McDaniel](http://www.patrickmcdaniel.org/).  Before that,
I attended the School of Computer Science at the [University of
Massachusetts](http://www.cs.umass.edu/) advised by [Prof. Brian
Levine](http://people.cs.umass.edu/~brian/).  

### News

 - 04/01/2022: Our work ["Holistic Control-Flow Protection on Real-Time Embedded Systems with Kage."](https://www.usenix.org/conference/usenixsecurity22/presentation/du) was selected to appear at the 31st USENIX Security Symposium. 

### Current Projects

I've had the opportunity to work on a number of interesting research projects
during my career. Checkout [The Cake Lab's](https://cake-lab.github.io/)
website for the most up to date information about my work. 

#### Embedded Systems Security

Embedded systems form the core of critical infrastructure, perform auxiliary
processing on mobile phones, and permeate homes as smart devices. Yet, embedded
software security lags behind traditional desktop security. While myriad
defenses exist for general-purpose systems (e.g., desktops and servers),
embedded systems present several unique challenges for software security such
as greater hardware diversity, limited resources (e.g. memory and power), and
lack of support for common abstractions like virtual memory. Our work in this
area includes defenses for protecting embedded software and RTOS kernels from
memory errors, such as [Kage
(USENIX'22)](https://www.usenix.org/conference/usenixsecurity22/presentation/du),
[Silhouette (USENIX'20)](https://arxiv.org/abs/1910.12157), and [Recfish
(ECRTS'19)](http://drops.dagstuhl.de/opus/volltexte/2019/10739/).

#### Secure Deep Learning 

ML models are valuable intellectual property due to the investment and
expertise required to gather training data and construct the model. To monetize
these models, companies often make them available as a service via APIs over
the web.  Further, the model owners often rely on others' hardware, such as
cloud providers or end-users, for model execution.  Our [CVPR'21
work](https://arxiv.org/abs/2011.14779) demonstrates the feasibility of
data-free model extraction attacks, i.e., a type of attack that does not
require knowledge of the underlying training dataset. In our [IC2E'21
study](https://arxiv.org/abs/2104.15109), we identify performance bottlenecks
that stymie current attempts to run models in trusted execution environments. 

#### GPU Performance 

The RIPCORD project proposes a new infrastructure for improving the performance
of deep learning model serving.  In our
[Performance'20](https://cake.wpi.edu/assets/papers/gilman20_performance.pdf)
and [Performance'21](https://arxiv.org/pdf/2110.00459.pdf) studies, we
considered the performance of current GPU concurrency mechanisms.  We examined
scheduling at the microarchitectural level and found that the lack of
fine-grained preemption mechanisms, robust task prioritization options, and
contention-aware thread block placement policies limits the effectiveness of
existing mechanisms.

### Past Projects

Below are some of the previous projects I have had the privilege to work on. 

#### Web Security and Privacy 

Domain names have become the Internet’s de facto root of trust. In practice,
they are also a root of insecurity as common security systems depend on the
unfounded assumption that domain ownership remains constant; this leaves users
vulnerable to exploitation when domain ownership changes. In our [Oakland
2016][oakland16] we find that many seemingly disparate security problems share
a root cause in residual domain trust abuse.

Online advertising is one of those little annoyances that we all have to deal
with. "Not so!" Said the plethora of ad blocking extensions promising to
improve your browser experience. Not only do they block ads, they also claim to
help preserve your privacy and protect  you against the growing trend of
malicious advertisements. In our [IMC 2015 work][imc] my co-authors and I take
a closer look at the most popular ad blocking software. We find that ad
blockers are not quite what they appear to be.

[imc]: http://rjwalls.github.io/papers/walls15_imc.pdf


#### Digital Forensics

Mobile phones contain evidence that is invaluable for criminal investigations.
However, commercially-available forensic tools must be hand-tailored to each
phone model. If no tools support the target phone, then extracting the phone's
information requires investigators to  examine the stored data byte by byte.
To address this problem,  I've developed general algorithms and techniques for
recovering information from phones even if the exact  storage format is unknown
or the data has been logically deleted. 

[DECODE](https://github.com/umass-forensics/DEC0DE-forensics) is an inference engine that extracts meaningful information from raw
byte streams. Read more about it [here][decode].  [Liftr](https://github.com/umass-forensics/Liftr-forensics) incorporates
investigator feedback and relevance graphs to improve the results of inference
engines like DEC0DE. [Paper here][liftr].

[decode]: http://forensics.umass.edu/pubs/Walls.usenixSecurity.2011.pdf
[liftr]:http://forensics.umass.edu/pubs/varma.spsm.2014.pdf

#### Science of Security

Perhaps the most  ambitious projects I've been involved with is the 10-year
Cyber-Security Collaborative Research Alliance with the Army Research
Laboratory, Penn State, Carnegie Mellon, UC Riverside, UC Davis, and Indiana
University. The project's mandate is to develop a new science of security. As
part of this effort, I've worked on the foundation for representing operational
and environmental knowledge---see my work on ontologies
[here][ontology1]---with the goal of reasoning about both current and future
states to make optimal security decisions. 

[cra]: http://cra.psu.edu/
[ontology1]: http://rjwalls.github.io/papers/oltramari14_stids.pdf

### Selected Publications

Below is a partial list of my recent publications.

{% include pubs.html %}
