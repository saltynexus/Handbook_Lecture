# Chapter 8: Power Take-Off Systems for WECs
Let's start with some (informal) definitions...
* Power Take-Off...**PTO**...you'll see it a lot
    *  convert absorbed wave energy
    *  when referring to the PTO, it's important to understand the end product (e.g. mechanical or electrical)
* Energy - capacity to do work (fundamental)...comes in many forms (kinetic, potential, etc.)
* Work - amount of energy transferred when a force acts on an object over a distance
* Power - rate at which energy is transferred. In other words the rate at which the work is done

A simple mechanical model for a WEC...
```{figure} ./images/oscillator.png
---
scale: 80%
align: center
---
Damped oscillator 
```
From an engineering perspective, the study of WEC systems largely involves the study of vibrations and control theory with depth in hydrodynamics and mechanics. This is why the research is largely carried out by ocean and mechanical engineers. That being said, there are many facets to WEC systems, in which engineering is only one of them.

* General force concepts you need to know...
    1. inertia
    2. damping
    3. restoring
    4. excitation
* Of these, damping is of the form which gives absorption
    * What happens if there is no damping?
```{figure} ./images/damping.png
---
scale: 80%
align: center
---
Different forms of damping
```

## Introduction
Start with the big picture...how do we get from A to B?
* "wave-to-wire" -> there is a constant flow/transfer of energy
    * waves power is captured/manipulated by device geometry
        * e.g. wave force acting on a body causes it to move
    * mechanical-mechanical conversion
        * e.g. linear body motion converted to shaft rotation
    * mechanical-electrical conversion
        * e.g. rotary generator

* PTO systems impact the efficiency, cost, and structural dynamics of WECs.
    * Directly affects the LCOE
    * Represent 20-30% of the CapEx
    * Reliability and maintenance (OpEx)

```{figure} ./images/lcoe_factors.png
---
scale: 80%
align: center
---
Different forms of damping
```

* Designing efficient PTO systems is a major challenge **due to variability in wave energy and harsh marine environments**.  
    * True for any ocean system...look at wave spectrum
    * Unconventional goal...resonance is a good thing
    * Impedance
* PTO is where most research is focused today
    * Efficiency vs Cost

## Types of PTO Systems Overview
* PTOs just as diverse as WEC bodies
* Main categories include
    *  air turbines
    *  hydraulic systems
    *  hydro turbines
    *  direct mechanical drives
    *  direct electrical drives

```{figure} ./images/pto_types.png
---
scale: 80%
align: center
---
Different types of PTO systems
```

* Others not mentioned include advanced materials and/or properties
    * Electroactive polymers
    * Triboelectric
    * Piezoelectric
    
## Air Turbines
* Air turbines are used primarily in Oscillating Water Column (OWC) devices.
    * Examples of self-rectifying air turbines include Wells, Impulse, and Denniss-Auld turbines.
        * Wells turbines are simple but not self-starting
        * Impulse turbines are more efficient but require more maintenance
    * Reaction type - lift
    * Floating and fixed bottom

```{figure} ./images/air_turbine.png
---
scale: 80%
align: center
---
Schematic of air turbine concept
```

The video clip below showcases the Halona PTO bench test apparatus at the University of Hawaii at Manoa. The large piston emulates the free surface in the air chamber, oscillating back and forth to drive an impulse turbine.
<video controls muted="true" loop="true" width="600" style="display: block; margin: 0 auto;">
    <source src="../_static/videos/Halona_bench.mp4" type="video/mp4">
</video>

## Hydraulic PTO Systems
* Common in point absorbers and attenuators
    * Linear vs rotational
* Translate mechanical energy into fluid motion
    * Drives a hydraulic motor connected to an electrical generator
* Well-suited for handling high loads at low speeds
* Complex and prone to maintenance issues

```{figure} ./images/hydraulic_system.png
---
scale: 80%
align: center
---
Schematic of hydraulic PTO
```

## Hydro Turbines
* Similar to use of hydraulic motor, but different working principle
    * Impulse vs Reaction
* Mature and highly efficient, with efficiencies exceeding 90%
    * Head vs flow

```{figure} ./images/head_flow.png
---
scale: 100%
align: center
---
Turbine designs for various flow regimes
```

```{figure} ./images/wave_dragon.png
---
scale: 100%
align: center
---
Kaplan turbine application in Wave Dragon
```

The video clip below showcases the HAWSEC PTO bench test apparatus at the University of Hawaii at Manoa. An electric actuator oscillates back and forth to drive a closed circuit hydraulic system connected to a Pelton turbine.
<video controls muted="true" loop="true" width="600" style="display: block; margin: 0 auto;">
    <source src="../_static/videos/HAWSEC_bench.mp4" type="video/mp4">
</video>

## Direct Mechanical Drive Systems
* Mechanical systems directly couple the motion of a WEC to an electrical generator
* Examples include systems with pulleys, cables, and gearboxes
* Fewer energy conversions mean higher efficiency
* Significant wear due to repeated load cycles
    * Needs more proof of concept...remember, waves different than wind 

```{figure} ./images/direct_mechanical.png
---
scale: 100%
align: center
---
Direct mechanical drive
```

## Direct Electrical Drive Systems
* Similar to "Direct Mechanical Drive Systems" but no intermediate mechanical transfer
* Mostly developed in the field of power electronics
    * All conversions and smoothing done electrically
* Challenges include designing the structure to maintain fine tolerances between moving components.

```{figure} ./images/direct_electrical.png
---
scale: 100%
align: center
---
Direct electrical drive
```

## Control Strategies for PTO Systems
* Although designed to overlap with the wave spectrum, the device response spectrum is not a perfect overlap
    * Can target average, but spectrum itself is dynamic
        * Timescales?

```{figure} ./images/wave_spectrum.png
---
scale: 100%
align: center
---
Spectra comparison
```

* Control strategies can be implemented to manipulate the response
    * Recall the forces...inertia and restoring
    * Damping coefficient (F/V)
    * What's the trade off here?
    * Passive vs Active

```{figure} ./images/damping_coeff.png
---
scale: 100%
align: center
---
Examples of different damping coefficients.
```

* Latching Control: Holds the WEC in place during zero velocity and releases it to maximize energy absorption.
* Reactive Control: Actively adjusts the system's stiffness and damping to respond to wave frequencies.
* Both strategies require advanced prediction algorithms and responsive PTO systems.

## Summary and Conclusions
* PTO systems are a critical element in the success of WECs.
    * Need to understand the trade offs
* The choice of PTO system affects efficiency, cost, and reliability, directly influencing the economic viability of wave energy.
* Continued research and development in PTO systems and control strategies are needed to lower costs and improve performance.
