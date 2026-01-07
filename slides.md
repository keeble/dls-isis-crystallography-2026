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

## What to say? 

- 10 mins per beamline
- Focus on capabilities and the science it can enable
- Aim to identify collaboration and areas for common development

---

## What is I15-1?
- I15-1 is a high-energy, high-flux, powder diffractometer
- Primarily designed for total scattering and PDF studies
- Built to use an unused side portion of the I15 source profile

---

<style scoped>
  img[alt~='masked'] {
    right: -340px;
    mask-position: 45%, 0%;
  }
</style>

![masked w:1100](./assets/i15-1.png)
### Typical Experiments
- Samples in glass capillaries
- 440 positions on the table
- Hot (1050 K) and cold (90 K)
readily available
- Expose sample for ~10 minutes
- Everything pretty scriptable
&nbsp;

---

liquid flow

---

gas flow


---

drix


---

other setups

---

bags? 


---

mention the collab with SANDALS and the previous deal with POLARIS

---


## List of things
Normal markdown rules apply:

It helps us keep track of: 
- things
- other things
- those things over there
- and more! :o: :smiley: :white_check_mark:

---
- some things need a reference†
- and sometimes you need maths inline $x=y^2$ or in a block:
$$\begin{aligned}\mathbf{Q} &= \mathbf{k}_f - \mathbf{k}_i \\
Q &= \vert\mathbf{Q}\vert\end{aligned} $$

 <!-- _footer: †Keeble et. al Appl. Phys. Lett. 102, 092903 (2013) --> 

---

### and some things need to be in a table

Fruit | Colour | Amount | Cost
-----|------|:-----:|------:
Banana &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  | Yellow | 4 | £1.00
Apple | Red | 2 | £0.60
Orange | Orange &nbsp; &nbsp; &nbsp; | 10 | £2.50
Coconut | Brown | 1 | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; £1.50

---

<style scoped>
  p { text-align: center; }
</style>
...and sometimes
you want to temporarily
modify something

---
 fitting long lines to page width
#### <!--fit--> https://www.diamond.ac.uk/Instruments/Crystallography/I19/Manual/EH1.html
