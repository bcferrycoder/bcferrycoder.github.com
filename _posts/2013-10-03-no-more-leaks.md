---
layout: post
title: "No More Leaks"
description: ""
category: 
tags: []
---
{% include JB/setup %}

The JavaOne melting pot brings together smart diverse people from
around the globe to discover and discuss the latest in the
ever-advancing Java ecosystem. People like Nikita Salnikov-Tarnovski,
founder of Plumbr, an exciting startup from Estonia. 

Nikita and his team have created a tool which I believe should be
categoried as "essential" for cloud developers that build apps based
on the JVM.


Plumbr provides a hosted leak-detection service for Java applications,
and after a short test spin I now categorize it as "indispensible" for
any Java developer in the cloud.

Plumbr offers a real-time cloud-based leak detection service
(I'm guessing it's called LDaaS). What distinguishes plumbr from all of the
solutions mentioned above is its incredibly low barrier to entry. All
the above solutions require some amount of effort (learning
languages/frameworks, installing/configuring/understanding tools,
etc). Plumbr requires next to nothing.

I'll walk through the steps here. Please try this at home.

1. Download and extract plumbr, cd plumbr

2. create a stackato.yml file like this:

# stackato.yml for plumbr
name: plumbr-clinic




3. 


Signup is trivial: just enter email, password, name.
then 

After signup



Goal: wire plumbr into my existing Java application

Steps:

1. deploy application for baseline

2. download plumbr.eu/download  and expand

3. cd plumbr

4. cat <<EOF > stackato.yml
# stackato.yml for 
name:

Now let's take a Java app and deploy it with 






's innovations are in the field of leak detections,
in their case in the form of notifying you if you application is
leaking.



Plumbr.eu who offers an innovative leak detection system worth
exploring by any developer building cloud applications in Java.

This blog describes Plumbr, and shows how to quickly enable Plumbr
memory leak detection in any Stackato-deployed Java application.

<img width="100" src="http://i.imgur.com/qLwLi7j.jpg">

First let's talk about leaks. While some leaks might be considered
benign, or even benevolant, memory leaks in cloud software are
generally something well worth avoiding. Memory leaks are:

**unpredictable**, often showing up at the worst possible time.

**evasive**, difficult to track down, just as difficult to reproduce.

**costly**, responsible for countless hours of wasted productivity,
lost revenue, and decreased morale.

**damaging** to reputation, brand, inter-team and intra-team
  relationships

**dangerous**: the right leak at the right time and place can sink a
ship or a company.


We are fortunate that memory leaks, like most chronic problems in the
world of software engineering, have attracted the attention of The
People Who Fix Things, who over the years have generously
given us many ingeneous tools and practices to help combat leaks.
These include:


* Static code analysers
  [Klocwork](http://www.klocwork.com/landing/memory-leaks/index-v2.php?gclid=CP_ysJS5-bkCFUfZQgodex0ATQ)

* Coding conventions and practices

* Platform Capabilities

* Language Features and Constructs

* Frameworks and Libraries

* Monitoring Tools, Instrumentation Libraries

* Developer tools

* Testing tools

* Log aggregators


These  prevent, diagnoze, and fix threatening
memory leaks.

Plumbr is a tool that 



Note: plumbr finds all leaks, but some 

this will will help identify memory leaks that don't need
fixing. Example: low traffic site (say internal app, mission critical,
but maximum traffic is 1000 hits a day. With plumbr and JMeter you
discover a leak manifests itself after 50 million hits. Should you fix
it now? Maybe, but consider prioritizing other leaks, since you have
over 140 years to fix this one.

What did Nikita mean: No False Positives?

mention supports PRIVATE CLOUD
