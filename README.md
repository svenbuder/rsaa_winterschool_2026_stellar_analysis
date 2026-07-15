# Stellar spectroscopy with the WiFeS spectrograph ⭐

**How do we turn light collected by a telescope into information about a star?**

In this practical, you will work with observations from the **[WiFeS spectrograph](https://rsaa.anu.edu.au/observatories/instruments/wide-field-spectrograph-wifes)** at ANU's 2.3m telescope at Siding Spring Observatory.

We will follow the spectrum from the detector to a first scientific interpretation:

> **WiFeS integral-field data cube → extracted 1-dimensional spectrum → radial velocity → stellar properties → scientific figure**

<p align=center>
    <img src="https://github.com/svenbuder/rsaa_winterschool_2026_stellar_analysis/blob/main/figures/wifes_ifu_image.png" width="17%"/>
    <img src="https://github.com/svenbuder/rsaa_winterschool_2026_stellar_analysis/blob/main/figures/example_spectrum_teff.png" width="82%"/>
</p>

## Your mission

By the end of the session, you will have:

* explored how temperature, gravity, composition, and dust affect a stellar spectrum;
* extracted a one-dimensional spectrum from a WiFeS data cube;
* combined observations from the blue and red spectrograph arms;
* estimated the star’s radial velocity;
* compared the observation with synthetic stellar spectra; and
* produced a clear diagnostic figure communicating your result.

<p align=center>
    <img src="https://github.com/svenbuder/rsaa_winterschool_2026_stellar_analysis/blob/main/figures/06_alfCenA_rainbow.png" width="29%"/>
    <img src="https://github.com/svenbuder/rsaa_winterschool_2026_stellar_analysis/blob/main/figures/07_HD140283_rainbow.png" width="29%"/>
</p>

## Start here

1. Download the data from this repository (if you know how to use `git`, just clone it, otherwise use `<> Code` and `Download ZIP`)
2. Download the data from https://drive.google.com/drive/folders/19AmMxTvlQK_JP1CFvXofK1UrbfV-1OXV?usp=share_link into the `data/` directory.
3. Open [`stellar_spectroscopy.ipynb`](stellar_spectroscopy.ipynb). You need to have `python` and either `Jupyter` or `VSCode` installed to run the code
4. Work in pairs to work through the notebook from the beginning and work through the sections in order.
6. Discuss the **predictions** and **checkpoints** with your partner before moving on.
7. Make your own analysis choices—there is not always one uniquely correct answer.

The practical contains code to handle the routine steps. Your task is to decide **what to measure, how to measure it, and whether the result makes physical sense**.

## What matters most

This is not intended to be a production-quality stellar-analysis pipeline. Focus on:

* understanding what the spectrum is telling you;
* recognising how your choices affect the result;
* identifying where the models succeed or fail; and
* making plots that allow others to judge your conclusions.

You do not need to complete every optional challenge. A carefully interpreted result is more valuable than rushing through every cell.

**Be curious, compare ideas with the other groups, and ask questions whenever something in the spectrum surprises you.**
