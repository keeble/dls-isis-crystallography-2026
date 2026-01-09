---
marp: true
paginate: true
size: 16:9
backgroundImage: url('./assets/default.png')
style: |
  @import url('./assets/diamond.css');
  img[alt~='masked'] {
    mask-image: url('./assets/dls-mask.png');
    mask-repeat: no-repeat;
    mask-size: contain;
    mask-position: 100%, 0%;
    position: absolute;
    width: 1200px;

    /* Place to right-bottom */
    right: 0px;
    top: 0px;
    }

---
<!-- _class: lower-heading -->
![bg](./assets/h1.png)

# I15-1 (XPDF)
Dean Keeble
DLS/ISIS Crystallography Meeting
January 2026

---
<style scoped>
table {
  border: none !important;
  border-color:  rgba(255, 255, 255, 1) !important;
  position: absolute;
  top: 55%;
  left: 50%;
  transform: translate(-50%, -50%);
}
h2 {
  position: absolute;
  top: 13%;
}
th, td, tr, tbody {
  background-color: rgba(255, 255, 255, 1) !important;
  border-color:  rgba(255, 255, 255, 1) !important;
}
p {
  text-align: center;
  }
</style>
## I15-1 Beamline Staff

|![h:250](./assets/dean.png) |![h:250](./assets/dan.png) |![h:250](./assets/anna.png) |![h:250](./assets/tobie.png) | ![h:250](./assets/finley.jpeg)
:-----:|:------:|:-----:|:------:|:------:
Dean Keeble | Dan Irving | Anna Herlihy | Tobias Bird | Finley Belcher

---

## What is I15-1?
- I15-1 is a high-energy, high-flux, powder diffractometer
- Primarily designed for total scattering and PDF studies
- Built to use an unused side portion of the I15 source profile

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;![h:180](./assets/optics-hutch.png)

---

### High Energy
We have 3 fixed energies, 40 keV, 65 keV, and 76 keV. At 76 keV: 
- can access a Q of ~28 Å<sup>-1</sup>
- 89% transmission through 10 mm of aluminium
### High Flux
We bend our monochromator crystal to increase the bandwidth (at the cost of reciprocal space resolution)

---

<style scoped>
  img[alt~='masked'] {
    right: -340px;
    mask-position: 45%, 0%;
  }
</style>

![masked w:1200](./assets/i15-1.png)
### Typical Experiments
- Samples in glass capillaries
- 440 positions on the table
- Hot (1050 K) and cold (90 K)
readily available
- Expose sample for ~10 minutes
- Everything pretty scriptable
&nbsp;

---

<style scoped>
  p { text-align: center; }
  img {border-radius: 20px }
</style>

![](./assets/capillaries.png)

---

![bg contain](./assets/gas.png)

---

![bg contain](./assets/drix.png)
<!-- _footer: Diaz-Lopez, et al. (2020)  J. Synchrotron Rad. 27, 1190.
 -->

---

&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; ![h:500](./assets/other_environments.png) ![h:500](./assets/installation.jpg)

---
### Previous/Current DLS/ISIS collaborations
- Previously we offered "free" room temperature data collections to the ISIS Crystallography group
- More recently we've had a lot of DM proposers include I15-1 on their proposals, and we're looking to widen this collaboration

---

<!-- _class: lower-heading -->
![bg](./assets/h2.png)

## Future Plans
#### New & newer Detectors, Diamond-II
---

## New Detector(s)

<style scoped>
table {
  border: none !important;
  border-color:  rgba(255, 255, 255, 1) !important;
  position: absolute;
  top: 55%;
  left: 50%;
  transform: translate(-50%, -50%);
}
h2 {
  position: absolute;
  top: 7%;
} td, tr, tbody {
  background-color: rgba(255, 255, 255, 1) !important;
  border-color:  rgba(255, 255, 255, 1) !important;
  color: var(--diamond-primary) !important;
}
p {
  text-align: center;
  }
</style>

 &nbsp;| model | sensor <br>thickness | pixel<br>size | frame<br>rate |  coverage
:-----:|:------|:-----|:------|:------|:---
![h:150](./assets/arc.jpg)| ARC CdTe| 1 mm | 75 um | 25 Hz | 109°
![h:150](./assets/eiger.webp) | Eiger 2X CdTe | 750 um | 55 um | 2.2 kHz | 17°

---

## Diamond-II 

- The Diamond-II upgrade will see a new software stack deployed at Diamond
- In 2026 I15-1 will start using this new stack
- Looking to introduce better interconnectivity of data and bespoke web interfaces

---
<!-- _class: lower-heading -->
![bg](./assets/h3.png)

# I15-1 (XPDF)
Dean Keeble
DLS/ISIS Crystallography Meeting
January 2026