---
layout: page
title: "Astronomy"
permalink: /astronomy/
---

I am thankful to have had several opportunities to do super cool research in astronomy during my undergraduate career. What follows is a summary of each of those projects.

### Radio Instrumentation

<img src="https://abulatek.github.io/resources/feed_horn_perspective.png" width="265" align="right" style="padding: 15px;" alt="UWBR feed horn" />
- The [Green Bank Telescope](https://greenbankobservatory.org/science/telescopes/gbt/) is involved in [NANOGrav](http://nanograv.org/)'s search for gravitational waves, propagating disturbances in spacetime, by acting as a **stopwatch for pulsars**.
- Pulsars are rapidly-rotating neutron stars that emit regular radio pulses. GWs passing between the Earth and the pulsar will change their apparent pulse period.
- Green Bank Observatory is designing an **ultra-wideband (6:1)** radio receiver that can make simultaneous wideband observations of pulsars to precisely measure their signal timing. I calculated the predicted efficiency of the receiver and modeled a component of the cryogenic dewar.
- Fabrication of the receiver has begun and scientific commissioning of the system is expected to begin in late 2020 or early 2021.
  - I presented a [poster](https://abulatek.github.io/resources/GBO_poster.pdf) on this work at AAS 235.
  - Here's a [video](https://www.youtube.com/watch?v=Zfygjjy-36U) featuring me talking a little about my summer.

### Infrared Instrumentation

<img src="https://abulatek.github.io/resources/IPC_relation.png" height="275" align="right" style="padding: 15px;" alt="IPC relationship" />
- The [Near-Earth Object Camera](https://uanews.arizona.edu/story/uarizona-looks-toward-work-nasa-s-potential-asteroidhunting-space-telescope) (also known as NEO Surveyor) spacecraft is designed to find, track, and characterize **potentially hazardous asteroids** (large and close to the Earth). The University of Rochester is contributing to the NEOCam project by characterizing prototypes of the high sensitivity 16-megapixel cameras that will fly on NEOCam.
- During the summer of 2018, I participated in the Physics REU at UR. I worked in the infrared detector group with Dr. Judy Pipher, Craig McMurtry, and their graduate students. I wrote an algorithm to correct for an image-blurring effect that plagues long-wavelength (~10-micron) IR detectors called **interpixel capacitance (IPC)**.
- IPC spreads signal from one pixel to its neighbors via capacitance between the pixels. It has been shown to be **signal-dependent**: the more signal deposited onto a pixel, the less signal gets spread to nearby pixels. So, to correct for IPC effectively, we must measure the relationship between signal spread and signal strength.
  - I presented a [poster](https://abulatek.github.io/resources/UR_poster.pdf) on this work at AAS 233.
  - I wrote an [Astrobites](https://astrobites.org/2018/11/05/ur-interpixel-capacitance/) post about the project.

### Galaxies

#### IC 3877

<img src="https://abulatek.github.io/resources/IC3877.png" height="250" align="right" style="padding: 15px;" alt="IC3877 images"/>
- In the spring of 2018, my Observational Astronomy course at Macalester analyzed 21 cm data from the VLA on KDG 215. In the data cube, another HI source was present off-axis and offset in velocity space from KDG 215. It was IC 3877, a large spiral galaxy that had previously been imaged for SDSS, but never in HI. I ended up imaging IC 3877 for a few reasons. Firstly, I only had experience with small dwarf galaxies, and wanted to see how a large spiral would look in the radio. Secondly, I was interested in seeing if an off-axis primary beam correction could recover the total HI flux measured by a single-dish observation.
- Doing this imaging work was worth it, as the images were **beautiful**. I calculated an HI flux integral of 32.3 Jy km/s, compared to the ALFALFA result of 32.2 Jy km/s. Within the error for the VLA (10%), these integrals are the same (John Cannon, personal correspondence).

#### KDG 215, UGC 11411, and UGC 8245

- The final images of KDG 215 can be found in [this paper](https://iopscience.iop.org/article/10.3847/2041-8213/aada48) (arXiv version [here](https://arxiv.org/abs/1808.07108)).
- My second semester at Macalester, I worked in a research group with several students imaging two other dwarf galaxies. That work can be found [here](https://iopscience.iop.org/article/10.3847/2041-8213/aa8ea0) (arXiv version [here](https://arxiv.org/abs/1709.10161)).
  - Our work was featured by [AAS Nova](https://aasnova.org/2017/10/11/exploring-our-low-mass-neighbors/).
  - Some of the first-year researchers in the group who got REU positions were [featured on the Macalester website](https://www.macalester.edu/news/2017/08/first-year-firecrackers/), and interviews with each of us are included.

### Circumstellar Disks

<img src="https://abulatek.github.io/resources/DMTau_bw.png" height="275" align="right" style="padding: 15px;" alt="DM Tau image"/>
- During summer 2017, I took part in the KNAC REU at Wesleyan University working with Dr. Kevin Flaherty (now at Williams College). I used data from ALMA to **image the dust structure** of three circumstellar disks. For the disks around V4046 Sgr, MWC 480, and DM Tau, we were able to resolve down to spatial scales of 18, 29, and 25 AU respectively.
- We used **MCMC modeling** to determine the dust-to-gas ratios in the rings in each of the disk as well as disk radii. This modeling work was preliminary, but allowed me to get familiar with MCMC techniques.

<p align="center">
  <img src="https://abulatek.github.io/resources/disk_stats.png" height="150" style="padding: 15px;" alt="Disk statistics" />
  (Note: figures not to scale and are only meant to illustrate the relative size of each ring.)
</p>

## References

1. Mainzer, A., Bauer, J., Grav, T., et al. (2011). Preliminary Results From NEOWISE: An Enhancement to the Wide-field Infrared Survey Explorer for Solar System Science. The Astrophysical Journal, 731(1), 53. doi: 10.1088/0004-637x/731/1/53
2. University Communications. (2018, February 19). UArizona Looks Toward Work on NASA's Potential Asteroid-Hunting Space Telescope. Retrieved from https://uanews.arizona.edu/story/uarizona-looks-toward-work-nasa-s-potential-asteroidhunting-space-telescope.
3. Bralts-Kelly, L., Bulatek, A. M., Chinski, S., Ford, R. N., Gilbonio, H. E., Helmel, G., ... Denn, G. (2017). First Characterization of the Neutral ISM in Two Local Volume Dwarf Galaxies. The Astrophysical Journal, 848(1). doi: 10.3847/2041-8213/aa8ea0
4. Cannon, J. M., Shen, Z., McQuinn, K. B. W., Bartz, J., Bralts-Kelly, L., Bulatek, A. M., ... Salzer, J. J. (2018). Delayed Stellar Mass Assembly in the Low Surface Brightness Dwarf Galaxy KDG 215. The Astrophysical Journal, 864(1). doi: 10.3847/2041-8213/aada48
