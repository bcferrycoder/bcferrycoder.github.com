---
layout: post
title: "Coming Soon: Convergence as a Service"
description: ""
category: 
tags: []
---
{% include JB/setup %}
---
layout: post
title: "Convergence as a Service"
description: ""
category: 
tags: []
---
> **ABSTRACT**
>
> Many/most cloud-based ***as a Service*** offerings naturally converge with Private PaaS.
> with its... provides a natural convergence point for many of these
> cloud-based service offerings

## Convergence as a Service

This is getting out of hand. Just over 10 ago SaaS made its debut,
followed by IaaS and then PaaS. Now, with the sheer momentum of "The
Cloud," we're being flooded by a spate of these four - and now
five - letter acronyms all ending with "aaS" and all meaning the same
thing: Something as a Service.

Here is a by-no-means-exhaustive list of these Somethings:

* Software  (SaaS)
* Infrastructure (IaaS)
* Platform (PaaS)
* Human Resources (HRaaS)
* Data (DaaS)
* Logging (sim.)
* Lawyer
* Email
* Mashups
* Desktop
* Malware
* Crimeware
* Security
* Integration
* Communication
* Testing
* Compliance

> SIDEBAR: Crimeware? As a service?  > Yes: This week it was uncovered
> that [Google Drive is being used to host
> malware]("http://www.computerworld.com/s/article/9233831/Malware_uses_Google_Docs_as_proxy_to_command_and_control_server?taxonomyId=86").
> This is a textbook example of **Crimeware as a Service**: malicious
> software stored in the cloud, and accessed with effecitively
> infinite bandwitdh (and securely, over SSL no less) , by infected
> hosts on demand, making it even more of a challenge to detect by
> network-layer security products.

These repeating "as a Service" acronyms are in blatent violation of
the DRY ([Don't Repeat
Yourself]("http://www.computerworld.com/s/article/9233831/Malware_uses_Google_Docs_as_proxy_to_command_and_control_server?taxonomyId=86"))
principle.  Also, overloading the first letter (eg: Security,
Software, Storage) seems to further expose the inadaquacy of those
last 3 letters.

### BaaS

Ban the aaScronym, I say.

Luckly the end of this invasion is in sight. Many/most/all of these
service types are converging.

And PaaS, specifically **Private PaaS**, is the natural convergence
point, as we'll see here, starting with IaaS.

### Infrastructure

By definition PaaS needs infrastructure, whether a Raspberry Pi or a
dozens of multi-acre data centers spanning the globe. Thus it only
makes sense the IaaS and PaaS will be a package deal, both public
PaaS/IaaS, and private offerings such as
[Stackato]("http://activestate.com/stackato").

IaaS offerings are used to deploy, monitor, meter, and scale
infrasucture assets required for PaaS. Infrastucture services,
offering many advantages and abundantly available in the cloud, drive
a hard bargain: Very high ROI but the cost is steep ("just
hand us all your data"). 

Instead, if the IaaS product suite is based on PaaS (as it should be), then two can be deployed together with single point of
managemetn, and full integration.

Why? IaaS is an heavy-duty enterprise application delivered to the
cloud. The IaaS developers benefit from PaaS as much or more than any
cloud developer does. So they **Better** be using a PaaS, or I need to
have a quick chat with them.

But I digress. The point is, build your IaaS platform on PaaS, then
bundle the two as the product.

This is the convergence of the two.


### Backups

Cloud-based backups: It makes sense to deliver backups as part of
IaaS. But moving BaaS up to the PaaS layer enables automated,
zero-config, disaster-proof backups that can be instantly integrated
with an entire application and service suite.

### Logging

LaaS - Logging as a Service. Most PaaS offerings already offer
extansive centralized logging systems and integrating world-class
logging products such as Splunk, graylog2, logyard, and loggly.

In addition to services and products, logging best practices,
antipattern avoindance techniques, and sample code instantly available
from AppStore.

PaaS is a natural delivery vehicle for a fully-fleshed-out,
enterprise-ready logging system with underlying services (mongodb,
analytics), distributed log integration, and code starting points.


SaaS: the ticket submission system, integrated with bugtrack,
available in PaaS App Store. This includes the Infrastructure, along
with backups, notifications, batch, and failover.

### Everything as a Service

I could go on and on (I will...trust me) with multiple examples
describing how a DataBase-aaS has already converged with PaaS (Scalr,
CF, Stackato), or how a comprehensive **Email as a Service** package
can bundled and instantly available within the firewall, and
integrated with your entire software ecosystem.

Or Security as a Service (there's that overloaded "S") emphatically
one of the more important offerings, is immediately enabled with
Private PaaS (all your data and IP behind the firewall, you own it for
all of time). As important, delivery of industry security best
practices in the form of templates and app skeltons

More to follow but I'll wrap this up.

### Enterprise as a Service  /  Enterprise in a Box

To summarize, any [capable Private PaaS
product]("http://activestate.com/stackato") is capable of delivering a
fully-stocked Enterprise Software Foundation including infrastructure,
scaling, security, and a plethora of cloud-based software tools
including bug trackers, project management and agile tools, wiki and
blog products, the list goes on and on.

All this, all at the click of a button. Everthing
integrated. And... all behind your firewall.

Own your data. Forever.

With

PaaS

