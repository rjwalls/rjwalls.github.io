---
layout: default_minimal_2col
title: Home
notitle: true
---

### News

**Students!**: I am currently looking for motivated and qualified students. If
you are a WPI student, please send me an email or stop by. If you are outside
of WPI, I invite you to apply and then contact me.

### About Me

I am an assistant professor in the Department of Computer Science at [Worcester
Polytechnic
Institute](https://www.wpi.edu/academics/departments/computer-science) and a
proud member of [The Cake Lab](https://cake-lab.github.io/). My current
interests focus on systems security and performance and my projects often lie
at the intersection of software and hardware. Checkout our lab's [project
page](https://cake-lab.github.io/projects/) to learn more about some of my
current research projects.    In the Fall of 2016, I brought in security
researchers from around to the area to participate in [New England Security
Day](https://web.cs.wpi.edu/~rjwalls/nesd/).

Previously, I was a postdoctoral scholar in Department of Electrical
Engineering and Computer Science at The Pennsylvania State University working
with [Prof.  Patrick McDaniel](http://www.patrickmcdaniel.org/).  Before that,
I attended the School of Computer Science at the [University of
Massachusetts](http://www.cs.umass.edu/) advised by [Prof. Brian
Levine](http://people.cs.umass.edu/~brian/). My research at UMass focused on
providing law enforcement with novel techniques for investigating crimes. You
can find my thoughts on the difference between forensics and security
[here](http://forensics.umass.edu/publications.php?q=Walls:2011a).

### Current Projects

I've had the opportunity to work on a number of interesting research projects
during my career. Checkout [The Cake Lab's](https://cake-lab.github.io/)
website for the most up to date information about my work. 

#### Capr-DL: Confidential and Private Deep Learning 

Providing users with control over their personal data, while still allowing
them to benefit from the utility of deep learning, is one of the key challenges
of contemporary computer science. Our work on the Capr-DL project is focused on
performing deep learning operations directly on a personal device, with a
trusted framework, allowing both users to retain control over their private
data and companies to retain control over their proprietary models. 

#### RIPCORD: Model Execution Caching 

The RIPCORD project proposes a new infrastructure for improving the performance
of deep learning model serving.  Our work explores the promise of  model
execution caching as a means for improving the performance of cloud-based deep
inference serving. Model execution caching requires a CDN-like shared
infrastructure designed for workloads that see requests for a large and diverse
set of models.  That is, a workload where the aggregate volume of requests is
high but no single model is popular enough to merit a dedicated server. 

#### Embedded Systems Security

Embedded systems form the core of critical infrastructure, perform auxiliary
processing on mobile phones, and permeate homes as smart devices. Yet, embedded
software security lags behind traditional desktop security. While myriad
defenses exist for general-purpose systems (e.g., desktops and servers),
embedded systems present several unique challenges for software security such
as greater hardware diversity, limited resources (e.g. memory and power), and
lack of support for common abstractions like virtual memory.

Our work in this area includes defenses for protecting embedded software from
control-flow hijacking attacks
([Recfish](http://drops.dagstuhl.de/opus/volltexte/2019/10739/) and
[Silhouette](https://arxiv.org/abs/1910.12157)); FPGA architectures that
balance the throughput and resource requirements of AES
([Drab-Locus](https://arxiv.org/abs/1911.04378)); and techniques for generating
secure random numbers ([Erhard-RNG](https://arxiv.org/abs/1903.09365)). 


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
byte streams. Read more about it [here][decode]. 

[Liftr](https://github.com/umass-forensics/Liftr-forensics) incorporates
investigator feedback and relevance graphs to improve the results of inference
engines like DEC0DE. [Paper here][liftr].

[Yapr](https://github.com/rjwalls/YaffsParser) parses the Yaffs File System
commonly found on (older) Android phones.  Yapr even has limited ability to
reconstruct past versions of a file by leverage expired pages of flash memory.

[Filtr](https://github.com/rjwalls/Filtr) implements the concept of block hash
filtering using bloom filters. In short, Filtr will remove an repeated blocks
of data in a raw byte stream. For flash-based devices, such as phones, Filtr
often removes 50-90% of the raw data, saving precious time by limited the
amount of data that needs to be examines. Read more about block hash filtering
[here][decode]. 

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

#### Improving the Process

Like all computer scientists, I am constantly on the lookout for tools or
methods that will help me be more efficient in my work. Here are a few
repositories that you may find helpful.
 
[Latex Paper Template.](https://github.com/rjwalls/paper-template) Tired of wasting half an hour setting up your paper
   directory every time you start a new project? Try my paper template instead.

[Slidify Tutorial.](https://github.com/rjwalls/SlidifyTest) I am a big fan of
presentations, R, and Markdown---Slidify beautifully combines all three. Check
out my simple Slidify tutorial [here](http://rjwalls.github.io/SlidifyTest).


### Selected Publications

{% include pubs.html %}
