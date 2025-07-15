# Welcome to OpenZebra

**Accessible Tools for Zebrafish Larvae Fixation, Stimulation, and Tracking**

OpenZebra is a growing collection of open-source tools developed by members of the [Biomicrosystems (Jung) Lab](https://jung.lab.uic.edu/) at UIC to support accessible, reproducible, and affordable research using zebrafish and zebrafish larvae. This site serves as a central hub for all OpenZebra projects — including device designs, software repositories, experimental protocols, and instructional resources.

## Why Zebrafish Larvae?

Zebrafish larvae offer a rare balance in neuroscience research: they’re genetically tractable, optically transparent, and small enough to study entire neural circuits in vivo. But working with them — especially at early developmental stages — often comes with technical and logistical challenges. Many commercial systems are expensive, overengineered, or difficult to adapt to new experiments. What began as a few isolated tools to help with my own experiments has since become a broader effort to make zebrafish research more modular, adaptable, and accessible.

## Purpose of This Site

The goal of this site is to lower the barrier to entry for zebrafish-based neuroscience by sharing practical tools that are easy to build, modify, and understand. The projects here are documented (if applicable) with:

- Links to GitHub repositories
- Assembly instructions and CAD files
- Example use cases and data
- Teaching and outreach adaptations when available

I’ve tried to design these tools with the mindset that science should be both rigorous and approachable — not hidden behind proprietary walls or unnecessarily complex infrastructure. If you're a student, educator, researcher, or enthusiast, I hope you find something here that helps you move forward.

# Projects

## Agarose Stamping Method

**Standardized Immobilization for Zebrafish Larvae**

The agarose stamping method involves 3d-printable, reusable mold that creates patterned micro-wells in agarose gel for consistent and high-throughput immobilization of zebrafish larvae. It was developed to streamline the tedious and variable process of manually embedding larvae for imaging, stimulation, or behavior experiments. By changing the workflow from: agarose preparation -> larva alignment -> larva embedding -> post processing into: agarose stamp device preparation -> larva placement, the agarose stamping method improves reproducibility, reduces handling time, and is easy to teach or scale.

Links: [Repository / CAD Files](https://jjutoy2.github.io/Agarose-Stamping-Device/) • [Protocol Document 🚧] • [Preprint 🚧]

## Zebrafish Larvae Interface (ZLI)

**A Modular Platform for Real-Time Stimulation and Tracking**

ZLI is a flexible, modular, open-source platform for conducting sensorimotor experiments in zebrafish larvae. It supports real-time tracking, stimulus delivery (e.g., optokinetic), and — when desired — closed-loop control. The system is designed for modular use: tracking and stimulation can operate independently or in tandem, allowing researchers to adapt it to a variety of behavioral or neurophysiological paradigms. The platform is optimized for use with the agarose stamping method, which provides stable and reproducible animal positioning for high-quality data collection.
Links: [Repository / Codebase /Example Data](https://github.com/JJutoy2/Zebrafish-Larva-Interface/) • [Hardware Guide🚧] • [Manuscript](https://doi.org/10.3389/fnins.2025.1593930)