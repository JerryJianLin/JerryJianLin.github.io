---
layout: archive
title: "Research about metal-insulator-semiconductor tunnel diodes (MIS TDs)"
permalink: /teaching/
author_profile: true
---

* First part of this page introduces some basics of **_MIS TDs_**.
* Second part describes my research works about **_"Trench Structure MIS TDs"_**.

---

## 1. Basics of MIS TDs
---
### What is MIS TD? <br/>

<p style="text-align:center;"><img src='/images/MOS_MIS_v2.svg' width='600'></p>

  * The device structure of MIS TDs is similar to it of metal-oxide-semiconductor (MOS) capacitors.
  * Except that MIS TDs have very thin oxide thickness (d<sub>ox</sub>).
  * d<sub>ox</sub> is thinner than 4 nm.
  * Very thin d<sub>ox</sub> allows MIS TDs to have apparent direct tunneling currents. 
<br/>
<br/>

<p style="text-align:center;"><img src='/images/MIS_IV_v2.svg' width='500'></p>

  * MIS TDs usually have diode-like _I-V_ curves (see the above figure).
  * For MIS(p) device [p-type silicon substrate]:
    * V<sub>G</sub> < 0: forward bias region.
    * V<sub>G</sub> > 0: reverse bias region.



## 2. My research: Trench Structure MIS TDs (Trench MIS TDs) 
---
* In 2019, with the aim to utilize MIS TDs as **memory devices**, I proposed a new device structure for MIS TDs.
* I called it <b>_"Trench structure MIS TD (Trench MIS TD)"_</b>. [see the following figure] <br/>
<br/>
<br/>
<p style="text-align:center;"><img src='/images/TrenchMIS_v2.svg' width='500'></p>
<b>Fig.</b> Control group (left): conventional planar structure MIS TDs (Planar MIS TDs). Experimental group (right): proposed trench structure MIS TDs (Trench MIS TDs).<br/>
<br/>
<br/>

### Brief Summary of Trench MIS TDs Research


* **Trench structure offers more traps** 
  * **enhance memory properties (e.g., current window) of Trench MIS TDs.** 
  * [_Conference: IEDMS 2020_](http://JerryJianLin.github.io/publication/2020-10-16-IEDMS)
* **Trench structure changes the electric field in the oxide layer of MIS TDs** 
  * **strengthen the transient current behavior of Trench MIS TDs.**
  * **Trench MIS TDs can be utilized as volatile memory devices.**  
  * [_Journal: IEEE-TED, 2021_](http://JerryJianLin.github.io/publication/2021-07-16-IEEE-TED)
* **Magnitude of the transient currents in Trench MIS TDs is dependent on oxide thickness.**
  * **magnitude of the transient current is positively related to excess electron density.**
  * **excess electron density is dependent on oxide thickness.**
  * [_Conference: IEDMS 2021_ (Best Paper Award)](http://JerryJianLin.github.io/publication/2021-11-19-IEDMS)
<br/>
<br/>

* The following chronologically lists my research details (1 journal and 2 conference papers) about Trench MIS TDs.  
<br/>
<br/>

{% include base_path %}

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
