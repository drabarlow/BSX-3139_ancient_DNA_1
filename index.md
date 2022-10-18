---
title       : "Ancient DNA: methods and solutions"
subtitle    : "BSX-3139 Molecular Ecology and Evolution"
author      : Dr Axel Barlow
job         : "email: a.barlow.@bangor.ac.uk"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : LA_Full_colour_reversed.svg
biglogo     : A1_FullColour.svg
assets      : {assets: ../../assets}
license     : by-nc-sa
github:
  user: drabarlow
  repo: BSX-3139_ancient_DNA_1
  branch: "gh-pages"
---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Ancient DNA

- Why study ancient DNA?
- A brief history of the field
- Propoerties of ancient DNA, challenges and solutions

--- &twocol

## Ancient DNA is just old DNA

*** =left

- Bones
- Teeth
- Permafrost carcasses/"mummies"
- Museum specimens
- Sediments
- Dental calculus
- Coprolites

*** =right

<img src="./assets/img/kudarensis.png" alt="plot of chunk unnamed-chunk-1" width="80%" style="display: block; margin: auto;" />

<img src="./assets/img/big_bone.jpg" alt="plot of chunk unnamed-chunk-2" width="80%" style="display: block; margin: auto;" />

--- bg:white

## Why study ancient DNA?

<img src="./assets/img/time_mach.svg" alt="plot of chunk unnamed-chunk-3" width="80%" style="display: block; margin: auto;" />

--- .segue .dark 

## A brief history

--- 

## The field is < 40 years old

<embed src="./assets/img/Higuchi_1984_Quagga.pdf" title="plot of chunk unnamed-chunk-4" width="100%" height="500" type="application/pdf" />

--- 

## There have been some spectacular failures

<embed src="./assets/img/Paabo_1985_mummy.pdf" title="plot of chunk unnamed-chunk-5" width="100%" height="500" type="application/pdf" />

--- 

## Sorry dinosaur fans...

<embed src="./assets/img/Cano_1993_weevil.pdf" title="plot of chunk unnamed-chunk-6" width="100%" height="500" type="application/pdf" />

--- 

## Sorry dinosaur fans...

<embed src="./assets/img/Woodward_1994_dino.pdf" title="plot of chunk unnamed-chunk-7" width="100%" height="500" type="application/pdf" />

--- 

## First Pleistocene DNA

<img src="./assets/img/woolly-mammoth-2722882.png" alt="plot of chunk unnamed-chunk-8" width="55%" style="display: block; margin: auto;" />

--- 

## First Pleistocene DNA

<embed src="./assets/img/Hagelberg_1994_mammoth.pdf" title="plot of chunk unnamed-chunk-9" width="100%" height="500" type="application/pdf" />

--- 

## First Pleistocene mitochondrial genome

<embed src="./assets/img/Krause_2005_mammoth.pdf" title="plot of chunk unnamed-chunk-10" width="100%" height="500" type="application/pdf" />

--- 

## First palaeogenome

<embed src="./assets/img/miller_2008_mammoth.pdf" title="plot of chunk unnamed-chunk-11" width="100%" height="500" type="application/pdf" />

--- 

## The present

<embed src="./assets/img/bergstrom_2022_wolves.pdf" title="plot of chunk unnamed-chunk-12" width="100%" height="500" type="application/pdf" />

--- .segue .dark 

## Properties of ancient DNA

---

## Properties of ancient DNA

- Present in trace amounts
- Fragmentation
- High rates of sequencing error
- Contamination

**These are temporal processes**

<img src="./assets/img/hourglass.jpg" alt="plot of chunk unnamed-chunk-13" width="40%" style="display: block; margin: auto 0 auto auto;" />

--- 

## Timeline of ancient DNA

<img src="./assets/img/timeline.svg" alt="plot of chunk unnamed-chunk-14" width="100%" style="display: block; margin: auto auto auto 0;" />

--- .segue .dark 

## Ancient DNA is present in trace amounts

---

## Trace amounts

- Ancient samples *typically* contain very small quantities of DNA
- Lab methods optimised for low DNA input
- Sensitive to contamination by modern DNA

<img src="./assets/img/toy.svg" alt="plot of chunk unnamed-chunk-15" width="70%" style="display: block; margin: auto;" />

--- bg:white

## The ratio is key

<img src="assets/fig/unnamed-chunk-16-1.png" alt="plot of chunk unnamed-chunk-16" width="100%" style="display: block; margin: auto;" />

--- bg:white

## The ratio is key

<img src="assets/fig/unnamed-chunk-17-1.png" alt="plot of chunk unnamed-chunk-17" width="100%" style="display: block; margin: auto;" />

---

## PCR lab is especially dangerous

<img src="./assets/img/pcr.png" alt="plot of chunk unnamed-chunk-18" width="100%" style="display: block; margin: auto;" />

--- 

## Ancient DNA lab (clean lab)

- Geographically separated from modern lab
- Strict decontamination procedures (bleach, UV)
- Protective clothing
- Control of flow people and materials into lab (avoiding modern)
- Separated work areas for different procedures

---

## Smurfs

<img src="./assets/img/sina_lab.jpg" alt="plot of chunk unnamed-chunk-19" width="75%" style="display: block; margin: auto;" />

---

## Example lab layout

<img src="./assets/img/adna_lab.svg" alt="plot of chunk unnamed-chunk-20" width="85%" style="display: block; margin: auto;" />

--- bg:white

## DNA extraction

<img src="./assets/img/dabney_tstation.svg" alt="plot of chunk unnamed-chunk-21" width="65%" style="display: block; margin: auto;" />

--- .segue .dark 

## Ancient DNA is highly fragmented

--- &twocol bg:white

## Ancient DNA fragment length distribution

- DNA in ancient samples is highly fragmented
- The fragment lengths have a **skewed distribution**

*** =left

<img src="assets/fig/unnamed-chunk-22-1.png" alt="plot of chunk unnamed-chunk-22" width="100%" height="100%" style="display: block; margin: auto;" />
*** =right

<img src="./assets/img/kudarensis.png" alt="plot of chunk unnamed-chunk-23" width="100%" />

45 ka cave bear (*Ursus kudarensis*)

--- 

## DNA extraction

<embed src="./assets/img/Dabney et al. - 2013 - Complete mitochondrial genome sequence of a Middle.pdf" title="plot of chunk unnamed-chunk-24" width="100%" height="500" type="application/pdf" />

---

## PCR issues

<img src="./assets/img/pcr_issue.svg" alt="plot of chunk unnamed-chunk-25" width="%" style="display: block; margin: auto;" />

---

## Not a problem for NGS

<img src="./assets/img/library_molecule.svg" alt="plot of chunk unnamed-chunk-26" width="100%" style="display: block; margin: auto;" />

--- .segue .dark 

## Ancient DNA data has high error rates

--- &vcenter

## Typical ancient DNA molecule

<img src="./assets/img/sad_dna.svg" alt="plot of chunk unnamed-chunk-27" width="100%" style="display: block; margin: auto;" />

---

## Cytosine deamination

<img src="./assets/img/mapdam.svg" alt="plot of chunk unnamed-chunk-28" width="90%" style="display: block; margin: auto;" />

---

## Ancient DNA sequencing error

- **Cytosine deamination**
- Polymerase errors
- Other things we don't fully understand yet

### All these are sequenced with high quality, and amplified by the typically low coverage of ancient DNA data

---

## Error correction

<img src="./assets/img/consensify.svg" alt="plot of chunk unnamed-chunk-29" width="85%" style="display: block; margin: auto;" />

--- .segue .dark 

## Ancient DNA is highly contaminated

---

## First measurement of endogenous content

<embed src="./assets/img/Noonan et al. - 2005 - Genomic Sequencing of Pleistocene Cave Bears.pdf" title="plot of chunk unnamed-chunk-30" width="100%" height="500" type="application/pdf" />

---

## Contamination

- Around 1% endogenous content is considered typical
- Not really a problem for PCR (except humans)
- THE major problem for NGS

### Several methods exist for reducing the contaminant fraction

--- &vcenter

## DNA hybridisation capture*

<img src="./assets/img/hybr.svg" alt="plot of chunk unnamed-chunk-31" width="90%" />

### *Of course this only works if you know the sequence in advance

---

## Sample pretreatment

<img src="./assets/img/bleach.svg" alt="plot of chunk unnamed-chunk-32" width="90%" />

---

## Just sequence it (if you can afford it)

<img src="./assets/img/afford.svg" alt="plot of chunk unnamed-chunk-33" width="90%" />

--- &twocol

## Selecting the right sample

*** =left

<img src="./assets/img/petrous.png" alt="plot of chunk unnamed-chunk-34" width="100%" />

<img src="./assets/img/2048px-Temporal_bone_lateral5 (1).svg" alt="plot of chunk unnamed-chunk-35" width="50%" style="display: block; margin: auto;" />
*Anatomography CC BY-SA 2.1 JP*

*** =right

<img src="assets/fig/unnamed-chunk-36-1.png" alt="plot of chunk unnamed-chunk-36" width="100%" height="100%" style="display: block; margin: auto;" />

--- &vcenter

## Selecting the right sample

<img src="./assets/img/outermost_layer.png" alt="plot of chunk unnamed-chunk-37" width="60%" style="display: block; margin: auto;" />

---

## Suggested reading

<embed src="./assets/img/Orlando_2021.pdf" title="plot of chunk unnamed-chunk-38" width="100%" height="500" type="application/pdf" />

--- &thankyou

## Next time:

**Ancient DNA 2**
