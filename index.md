---
layout: default_minimal_2col
title: Home
notitle: true
---

### News

**Reviewing papers**: I've joined the program committee for the [2016 IEEE
International Conference on Network Protocols](http://icnp2016.comp.nus.edu.sg/).

**Going to Oakland**: Our paper "Domain-Z: 28 Registrations Later" was accepted
to the [IEEE Symposium on Security and
Privacy](http://www.ieee-security.org/TC/SP2016/).

### About Me

I am a postdoctoral scholar in Department of Electrical Engineering and
Computer Science at The Pennsylvania State University working with [Prof.
Patrick McDaniel](http://www.patrickmcdaniel.org/).  My research focuses on
large-scale systems security.

Previously, I attended the School of Computer Science at the [University of
Massachusetts](http://www.cs.umass.edu/) advised by [Prof. Brian
Levine](http://people.cs.umass.edu/~brian/). My research there focused on
advancing digital forensics by providing law enforcement with novel techniques
for investigating crimes. My past work includes an inference-based approach for
mobile phone triage and an in-depth analysis of contraband on peer-to-peer
networks. You can find my view on the difference between forensics and security
[here](http://forensics.umass.edu/publications.php?q=Walls:2011a).

I studied at [The University of Texas at Arlington](http://www.cse.uta.edu/)
under the direction of [Prof. Matthew Wright](http://isec.uta.edu/mwright/).
While there I focused on network security and was awarded the CSE Outstanding
Master’s thesis award for my work on the design and detection of covert timing
channels.

While at UMass, I was admitted to Ph.D candidacy with distinction and awarded
the department's Outstanding Synthesis Project award. I am also honored to have
received the 2011 Yahoo Key Scientific Challenges award in the Security &
Privacy category.

### Projects

I've had the opportunity to work on a number of interesting research projects
during my career. Here is a summary of some of my efforts. 

#### Web Security and Privacy 

Online advertising is one of those little annoyances that we all have to deal
with. "Not so!" Said the plethora of ad blocking extensions promising to
improve your browser experience. Not only do they block ads, they also claim to
help preserve your privacy and protect  you against the growing trend of
malicious advertisements. In our [IMC 2015 work][imc] my co-authors and I take
a closer look at the most popular ad blocking software. We find that ad
blockers are not quite what they appear to be.

[imc]: http://rjwalls.github.io/papers/walls15_imc.pdf

If you are in the market for a practical privacy solution, take a look at our
browser extension [Milk][milk]. Milk implements the concept of *functional
privacy*: give the users as much privacy as possible without breaking desired
functionality. The extension does this by putting cookies in separate silos and
restricting which sites have access to those cookies.  Read more about
[functional privacy here][funpriv].

[milk]:https://github.com/rjwalls/Milk
[funpriv]:http://forensics.umass.edu/pubs/walls.hotsec12.pdf
 

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

Perhaps the most  ambitious projects I am involved in is the 10-year
Cyber-Security Collaborative Research Alliance ([CSec CRA][cra]) with the Army
Research Laboratory, Penn State, Carnegie Mellon, UC Riverside, UC Davis, and
Indiana University. Our mandate is to develop a new science of security. As
part of this effort, I've worked on the foundation for representing of
operational and environmental knowledge. (See my work on ontologies
[here][ontology1]). Our goal to reason about both current and
future states to make optimal security decisions. 

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

[Taskr.](https://github.com/rjwalls/Taskr) This simple command line utility
helps manage how you spend your time. 



### Publications

{% include pubs.html %}
