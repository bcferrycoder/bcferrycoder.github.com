---
layout: post
title: "Why I ran away from home"
description: ""
category: 
tags: []
---
{% include JB/setup %}
I've moved my home several times over my life - who hasn't - and everyplace
I've that I've called home has accummulated all sorts of stuff that I
don't want to lose but it's a hassle to keep organized. I'm thinking
about  things like letters and correspondence, photos, cd's, etc. 

Everytime I move I have to pack up all this stuff and transfer it to
the new place, or I have to pack it up and put it in storage.

Either way it often ends up sitting around around, not unpacked.


# Instructions

1. boot ubuntu
2. git clone https://github.com/bcferrycoder/jdw-bootstrap /home/jdw
3. sh /home/jdw/prepare-host.sh
4. cd /home/jdw; docker build -t jdw/jdw .
5. docker run -i -t -p 3000 jdw/jdw /bin/bash --login
6. cd /home/jdw; jekyll --serve --port 3000
7. http://host:3000


