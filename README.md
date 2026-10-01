# 4-Blade Barrel-Type Cycloidal Rotor (Cyclorotor) UAV Propulsion Module

## Overview
An advanced mechanical propulsion and thrust-vectoring module designed for high-agility unmanned aerial vehicles (UAVs). This repository hosts the computer-aided design (CAD) models, kinematic layouts, mass budgets, and engineering documentation for a 4-blade barrel-type cyclorotor system capable of rapid 360-degree thrust vectoring.

## Design Baselines & Targets
* **Thrust Goal:** $\ge 12\text{ N}$ (Exceeding baseline requirement of $\ge 10\text{ N}$)
* **Thrust-to-Weight (T/W) Ratio:** $\ge 2.5$ minimum baseline requirement
* **Total Module Mass Target:** $\le 350\text{ g}$
* **Kinematics:** Eccentric cyclic pitch mechanism with an eccentricity parameter of $e = 5\text{ mm}$

## System Architecture & Mechanism
Traditional propellers rely on collective pitch or RPM changes, limiting rapid vectoring. This design implements a cycloidal rotor architecture where:
1. **Sinusoidal Blade Pitch Control:** An eccentric control ring ($e = 5\text{ mm}$) dynamically alters the pitch of each of the 4 blades continuously throughout a single rotation.
2. **Instant Vectoring:** Generates thrust vectoring forces instantly across a 360-degree envelope without tilting the entire motor housing.
3. **Lightweight Structural Rigidity:** Optimized mechanical linkages and carbon-spar structural layouts designed to maintain structural integrity under centrifugal and aerodynamic loads while keeping total mass under $350\text{ g}$.

## Repository Structure
* `/cad/` — Parametric Onshape assembly files, exported STEP models, and component parts.
* `/images/` — High-resolution renders of the full barrel assembly and linkage mechanisms.
* `/docs/` — Comprehensive engineering design proposal, mass budget spreadsheets, and kinematic calculation sheets.
* `/simulations/` — Multi-domain simulation parameters and structural/aerodynamic evaluation notes.

## Key Engineering Artifacts
* **CAD Models:** Fully constrained parametric assemblies built in Onshape.
* **Kinematic Equations:** Complete analytical derivation of the blade angle-of-attack cycle mapped to the $5\text{ mm}$ eccentric offset.
