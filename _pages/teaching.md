---
layout: archive
title: "Research about metal-insulator-semiconductor tunnel diodes (MIS TDs)"
permalink: /teaching/
author_profile: true
---

* In the first part of this page, I would introduce some background about the semiconductor devices, MIS TDs.
* Second part is my research works about "Trench Structure MIS TDs".

---

## 1. Basics of MIS TDs
---
### What is MIS TD? <br/>

<p style="text-align:center;"><img src='/images/MOS_MIS.svg' width='600'></p> <br/>

  * The device structure of MIS TDs is similar to it of metal-oxide-semiconductor (MOS) capacitors.
  * Except that MIS TDs have very thin oxide thickness (d<sub>ox</sub>).
  * d<sub>ox</sub> is thinner than 4 nm.
  * Very thin d<sub>ox</sub> allows MIS TDs to have apparent direct tunneling current. 

<p style="text-align:center;"><img src='/images/MIS_IV.svg' width='600'></p> <br/>

  * MIS TDs usually have diode-like _I-V_ curves (see the above figure).
  * For MIS(p) device [p-type silicon substrate]:
    * V<sub>G</sub> < 0: forward bias region.
    * V<sub>G</sub> > 0: reverse bias region.



## 2. My research: Trench Structure MIS TDs (Trench MIS TDs) 
---
* In 2019, with the aim to utilize MIS TDs as a new type of memory devices, I proposed a new device structure for MIS TDs.
* I called it <b>"Trench structure MIS TD (Trench MIS TD)"</b>. \[One can see the following figure\] <br/>
<br/>
<br/>
<p style="text-align:center;"><img src='/images/TrenchMIS.svg' width='600'></p> <br/>
<b>Fig.</b> Top views and schematic cross section views of traditional planar structure MIS TDs (Planar MIS TDs) and the proposed trench structure MIS TDs (Trench MIS TDs).<br/>

* The following is my research about Trench MIS TDs.  

{% include base_path %}

<!-- remove at 2021/11/27
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
