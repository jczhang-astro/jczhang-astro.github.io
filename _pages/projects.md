---
layout: page
title: Research
permalink: /projects/
description: Time-domain populations, accreting compact objects, and stellar environments in nearby galaxies.
nav: true
nav_order: 2
---

## RESEARCH OVERVIEW

I study accreting compact objects and X-ray-source populations in nearby galaxies. My goal is to build a **time-domain population framework** that combines short- and long-timescale variability, spectral behavior, local stellar environments, and rare accretion phenomena. Nearby galaxies provide known-distance laboratories in which individual systems can be studied within well-characterized stellar populations and galactic environments.

My research addresses three connected questions:

- How do stellar environments shape X-ray-binary demographics and the distribution of accretion states?
- Which accretion regimes do X-ray binaries beyond the Milky Way occupy, as revealed by their spectral and timing variability?
- How do the incidence and variability properties of different X-ray-binary populations depend on stellar age, metallicity, star-formation history, and dynamical environment?

I work primarily with archival observations from **Chandra**, **XMM-Newton**, **Swift**, and **NuSTAR**, combining time-series analysis, X-ray spectroscopy, and multiwavelength imaging. This approach links compact-object variability to resolved stellar populations, star clusters, ionized gas, and the broader interstellar environment.

## RESEARCH THEMES

### 1. Time-domain populations of extragalactic X-ray binaries

Decades of Galactic X-ray astronomy have established a detailed view of Milky Way X-ray binaries and compact-object accretion. For nearby galaxies, early Chandra and XMM-Newton surveys established population-level X-ray luminosity functions, but luminosity alone cannot describe the full diversity of accretion states or their evolution. Timing information provides the missing dimension.

I conducted a systematic Chandra search for periodic and aperiodic variability among X-ray sources in **M31, M81, and Centaurus A**, using approximately two decades of archival observations. The resulting sample includes coherent periods, short-term flares and dips, aperiodic variability, and long-term luminosity changes {% cite zhang2026variability %}. I am extending this foundation toward comparative population analyses that connect variability and accretion state with stellar age, metallicity, star-formation history, and dynamical environment.

<figure class="research-figure research-figure--compact">
  <a href="{{ '/assets/research/zhang2026-fig1.webp' | relative_url }}">
    <img src="{{ '/assets/research/zhang2026-fig1.webp' | relative_url }}" alt="Stacked Chandra HRC image of the M31 bulge with seven periodic X-ray sources marked" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>The M31 foundation of the survey.</strong> A stacked Chandra HRC image of the central 15 × 15 arcmin<sup>2</sup> of M31, with the seven periodic sources identified by the systematic search marked in yellow.</figcaption>
</figure>

The analysis combines:

- uniform source detection and extraction across multiple epochs;
- period searches in photon-counting time series;
- Bayesian Blocks searches for flares, dips, and state changes;
- long-term luminosity, spectral, and rms-flux measurements.

<div class="research-figure-grid">
  <figure class="research-figure">
    <a href="{{ '/assets/research/zhang2026-fig4-left.webp' | relative_url }}">
      <img src="{{ '/assets/research/zhang2026-fig4-left.webp' | relative_url }}" alt="Histogram of X-ray flare durations in M31, M81, and Centaurus A" loading="lazy" decoding="async">
    </a>
  </figure>
  <figure class="research-figure">
    <a href="{{ '/assets/research/zhang2026-fig4-right.webp' | relative_url }}">
      <img src="{{ '/assets/research/zhang2026-fig4-right.webp' | relative_url }}" alt="Histogram of X-ray flare peak luminosities in M31, M81, and Centaurus A" loading="lazy" decoding="async">
    </a>
  </figure>
</div>
<p class="research-figure-caption"><strong>Short-timescale flare populations.</strong> Distributions of flare duration and peak 0.5–8 keV luminosity in M31, M81, and Centaurus A. Bayesian Blocks provide a uniform definition of each flare interval across the three galaxies.</p>

<figure class="research-figure">
  <a href="{{ '/assets/research/zhang2026-fig5.webp' | relative_url }}">
    <img src="{{ '/assets/research/zhang2026-fig5.webp' | relative_url }}" alt="Comparison of extragalactic X-ray flare rates with Type I burst rates from MINBAR" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Flare recurrence.</strong> The rate distribution of recurrent flaring sources in this survey (orange dashed) compared with thermonuclear Type I burst rates from MINBAR (blue). Only sources with at least two events and a constrained recurrence rate are included.</figcaption>
</figure>

<figure class="research-figure research-figure--compact">
  <a href="{{ '/assets/research/zhang2026-fig6.webp' | relative_url }}">
    <img src="{{ '/assets/research/zhang2026-fig6.webp' | relative_url }}" alt="Long-term X-ray variability amplitude versus mean luminosity in M31, M81, and Centaurus A" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Population-level long-term variability.</strong> Variability amplitude versus mean X-ray luminosity for bulge sources in M31, M81, and Centaurus A. The galaxy-dependent linear scalings are consistent with an rms–flux relation and reveal differences in population variability.</figcaption>
</figure>

### 2. Periodic sources and ultra-compact binaries in M31

Using approximately 2 Ms of Chandra observations spanning 16 years, we performed a systematic search for periodic X-ray sources in the bulge of M31. We identified seven periodic systems, including four new discoveries, whose eclipses and dips constrain their orbital periods, accretion geometries, and binary configurations {% cite zhang2024periodic %}.

<figure class="research-figure">
  <a href="{{ '/assets/research/zhang2024-fig6.webp' | relative_url }}">
    <img src="{{ '/assets/research/zhang2024-fig6.webp' | relative_url }}" alt="X-ray luminosity versus orbital period for periodic low-mass X-ray binaries in M31 and the Milky Way" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>The periodic-source population in context.</strong> X-ray luminosity versus orbital period for the seven M31 bulge LMXBs (red circles), with crosses marking the four systems discovered in our Chandra search. Galactic ultra-compact, black-hole, and neutron-star LMXBs are shown for comparison; the dashed line marks the conventional 80-minute upper limit for ultra-compact systems.</figcaption>
</figure>

This work also led to the discovery and follow-up study of **M31 UCXB-1**. Its approximately 465-second modulation identifies it as an ultra-compact X-ray binary. Our subsequent study established it as the **first extragalactic ultra-compact X-ray binary** and a candidate **black hole-white dwarf system** {% cite ma2026ucxb %}. I am the first author of the systematic M31 timing study and a co-first author of the M31 UCXB-1 discovery paper.

<figure class="research-figure">
  <a href="{{ '/assets/research/ma2026-fig1.webp' | relative_url }}">
    <img src="{{ '/assets/research/ma2026-fig1.webp' | relative_url }}" alt="Phase-folded XMM-Newton light curve of M31 UCXB-1 and a schematic of its binary geometry" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>A 465.32-second orbital clock.</strong> The phase-folded XMM-Newton light curve shows a stable eclipse-like modulation. The schematic illustrates the interpretation in which the white-dwarf donor periodically obscures the accretion disk.</figcaption>
</figure>

<figure class="research-figure">
  <a href="{{ '/assets/research/ma2026-fig2.webp' | relative_url }}">
    <img src="{{ '/assets/research/ma2026-fig2.webp' | relative_url }}" alt="M31 UCXB-1 on the X-ray luminosity versus orbital period plane with model tracks for neutron-star and black-hole systems" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Testing the nature of the accretor.</strong> M31 UCXB-1 (red) on the 2–10 keV luminosity–orbital-period plane, compared with known ultra-compact binaries and theoretical neutron-star–white-dwarf and black-hole–white-dwarf bands. Its location is compatible with both classes, while the full timing and spectral evidence favors a black-hole accretor.</figcaption>
</figure>

M31 UCXB-1 demonstrates how systematic timing surveys can reveal rare compact binaries that are difficult to recognize from luminosity or time-integrated spectra alone.

<figure class="research-figure research-figure--graphical">
  <a href="{{ '/assets/research/ma2026-graphical-abstract.webp' | relative_url }}">
    <img src="{{ '/assets/research/ma2026-graphical-abstract.webp' | relative_url }}" alt="Graphical abstract showing a white dwarf transferring matter to a compact object in M31 UCXB-1" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>M31 UCXB-1 at a glance.</strong> A white dwarf fills its Roche lobe and transfers matter through an accretion disk onto a compact object, forming an exceptionally short-period extragalactic binary.</figcaption>
</figure>

### 3. M81F4 and extreme accretion

**M81F4** emerged from the broader timing survey as a persistently luminous X-ray source with recurrent minute-scale flares reaching super-Eddington luminosities. We carried out a systematic investigation with multi-mission archival X-ray data to characterize its long-term behavior and repeated flaring events.

The persistent and flare emission exhibit similarly hard X-ray spectra. The flares show neither spectral cooling nor an additional thermal component characteristic of classical thermonuclear X-ray bursts, strongly favoring an accretion-driven origin. Our preferred interpretation is a close binary containing a magnetized neutron star, fed through Roche-lobe overflow by an intermediate-mass donor, with the flares arising from instabilities at the disk-magnetosphere boundary.

M81F4 provides a rare observational benchmark for models of unstable accretion onto magnetized neutron stars at extreme mass-accretion rates. The manuscript, **“The Dancing Bonfire: An Unusual Persistent X-ray Source in M81 Exhibiting Recurrent Luminous Flares,” is submitted.**

### 4. Stellar environments, ionized gas, and feedback

Understanding X-ray-binary populations requires connecting compact sources with the environments in which they form and evolve. I study X-ray emission from star clusters in **M31 and M33**, and use high-resolution optical imaging to investigate ionized gas, emission-line sources, and associated resolved stellar populations.

During an academic visit to the **University of Washington**, I worked with **Dr. Benjamin F. Williams** on ionized gas and related stellar populations in M31 and M33. I also contributed to a multiwavelength study of the nuclear environment in M31 that combined observations with hydrodynamical simulations to revisit its ring-like gas structure {% cite li2025ring %}.

I am a co-investigator on the 2024 awarded **WHT/WEAVE** open-time program “How Do Stellar Feedback WEAVE into the ISM: the Unique Case of M31” (PI: Matthew Smith; 4.0 hr awarded). The program will map young star clusters and their surrounding H II regions in M31, using spatially resolved spectroscopy to examine ionized-gas kinematics and the transfer of energy and momentum from stellar feedback to the interstellar medium.

I also contribute to three **China Space Station Telescope (CSST)** early-science proposals involving joint MCI-IFS observations of M31 and M33 and joint IFS-MCI observations of the Virgo Cluster. These programs will connect resolved stellar populations and emission-line structures with the environments that shape compact-source populations.

For related results, see my [publications]({% link _pages/publications.md %}) and [academic CV]({% link _pages/cv.md %}).
