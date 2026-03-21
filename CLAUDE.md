# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **USB train throttle controller** hardware project for train simulation games. It is a prototype physical product consisting of CNC-milled aluminum enclosure parts and a custom PCB. There is no software code in this repository.

## Tools Required

- **SolidWorks** — for 3D mechanical CAD files (`.SLDPRT`, `.SLDASM`)
- **KiCad** — for PCB schematic and layout files (`.kicad_sch`, `.kicad_pcb`, `.kicad_pro`)

## Repository Structure

| Directory | Contents |
|-----------|----------|
| `Solidworks/Project5/` | **Current** mechanical assembly (ASF05-10-00); `.SLDPRT`/`.SLDASM` source files in `Prt/`, engineering drawings (PDF/DXF) in `Drw/` |
| `PCB/ThrottleControllerMain/` | **Current** KiCad PCB project |
| `Archive/` | Previous revisions: ASF02, ASF03, ASF04; delivery ZIP packages; older Hall sensor board |
| `Athula Kumara PCB/`, `Vertical PCB/`, `StephenG PCB/` | Alternative/earlier PCB iterations by contractors |
| `Drawings/` | Engineering drawing deliveries |

## Part Numbering Convention

`ASF0X-10-YY` — where `X` is the major revision number (currently 5) and `YY` is the sub-part number within the assembly. The top-level assembly is `ASF0X-10-00`.

## Fabrication Notes

- Machined parts are CNC-milled from **6061 aluminum**, debarred, no finish/as-machined
- PCB manufacturing via **PCBWay** (Gerber files exported from KiCad)
- Off-the-shelf hardware (screws, bearings, standoffs, neodymium magnets, rubber grip) is not fabricated
- Part `ASF0X-10-05` (black plastic rubber grip) is never fabricated — source externally
