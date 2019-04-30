---
title: General Guidance
layout: default
active: terminology
---

This section outlines the approach to adding new content to US Core.

---

<!-- TOC  the css styling for this is \pages\assets\css\project.css under 'markdown-toc'-->
**Contents**

* Do not remove this line (it will not be displayed)
{:toc}

---

<!-- end TOC -->

### Future of US Core

The US Core FHIR profiles are the base set of requirements for FHIR implementation in the US. All US Realm implementation guides **SHALL** use the US Core profiles or **SHALL** explicitly state why they are unable to use. Throughout the development of US Core, implementers, government, and clinical community have brought forward additional requirements for US Core. This section outlines the approach to growth, and is holding place for items that with additional profiling and testing will be added to US Core.

#### Growth Path of US Core

The US Core implementation Guide will grow following these steps:

{% include img.html img="US_Core_Growth_Path.jpg" caption="Figure 1: Growth Path of US Core" %}

1. Declare candidacy - this step can be completed by presenting to the US Realm Steering Committee through a Project Scope Statement. 
1. Get published - development a formal profile, implementation guide, or get requirements directly published in  FHIR Core. The initial publication could be an outside consortium, or vendor publication. 
1. Pilot - coordinate with 3 or more implementers an in-person or virtual connectathon. This is the time to identify issues with the new proposal.
1. Propose candidate for US Core to US Realm Steering Committee - receive formal approval from the US Realm SC to add.
1. Submit formal STU comment, or propose through a ballot

A new US Regulatory requirement may jump over some of these steps, however, regulators should be discouraged from skipping pilot testing. Without pilot testing it's difficult to understand how a change will affect real-world implementation.

In the January ballot of 2019 we tested this process with the FDA requesting US Core include all the component parts of UDI. In prior efforts, the FDA had successfully enhanced the base FHIR specification to include the UDI components, reaching step 3. In the summer of 2019 FDA plans to pilot test the new requirements with the Argonaut community which will the be incorporated in a fall 2019 STU update.

#### Future Requirements Under Considerations

**Pilot Testing**

The FDA formally submitted the UDI elements for testing in the Summer of 2019. The following profile will be followed:

(create new UDI component profile?)

**Candidates under consideration** 

The following items were submitted during a US Core ballot or STU comment. Additional requirements gathering is required before testing may occur on these items:
* [ServiceRequest] - The CDS hooks community, and other implementers are gathering requirements for the ServiceRequest Resource.


------------------------------------------------------------------------

{% include link-list.md %}