# Chapter 1: Introduction
Representing HMEC, I've tried to place the lecture material in context, focusing on Hawaii. Many of the figures are selected from a 2020 [Hawaii State Energy Office report](https://energy.hawaii.gov/wp-content/uploads/2020/11/HSEO_FactsAndFigures-2020.pdf) and like all material presented herein, the aim is to illuminate the landscape for educational purposes. It is by no means meant to be comprehensive. That being said, let's start with the driving motivation and take a look at **Hawaii's dependency on petroleum**: 

```{figure} ./images/Hawaii_dependence.png
---
scale: 75%
align: center
---
Dependence of states on petroleum for their energy needs, 2018
```
```{figure} ./images/Hawaii_sources.png
---
scale: 50%
align: left
---
Hawaii ENERGY by source, 2018
```
```{figure} ./images/Hawaii_petroleum_use.png
---
scale: 50%
align: right
---
Hawaii petroleum use by sector, 2018
```

```{note}
1 BTU = 0.000293 kWh
```

```{figure} ./images/Hawaii_cost_per_kWh.png
---
scale: 100%
align: center
---
Hawaii's dependence on petroleum.
```

## Introduction
```{figure} ./images/earth_from_space.jpg
---
scale: 5%
align: right
---
Earth from space.
```
* Ocean wave energy as a sustainable energy source
    * Where does the energy come from?
* "Benefits to society?" Phrased slightly different..."What are the problems with fossil fuels?"
    * Anthropogenic climate change
    * Finite resource
        * Who owns the resource? 
        * Rate of consumption
```{figure} ./images/energy_profile.png
---
scale: 40%
align: right
---
[Energy Networks Australia](https://www.energynetworks.com.au/news/energy-insider/should-solar-and-wind-pair-up-to-power-our-future/)
```
* Enhances national energy self-sufficiency and reduces reliance on imports
* Increases energy diversity
    * Why is diversity important?
    * New sectors for innovation and employment
* Land usage (debatable)

## The Concept of a Successful Product Innovation
* Elements for business potential

```{figure} ./images/product_innovation.png
---
scale: 70%
align: right
---
Three key elements of successful product design innovation.
```

* Gotta start somewhere...
    * Public funding and market incentives
        * EMEC 2016: over 250 developers
        * US following lead...can see in US DOE investment profile

* Business side: economic viability
    * Capital expenditure (CapEx) 
        * "investments" e.g. new printer
    * Operational expenditure (OpEx)
        * "day-to-day" e.g. printer paper
    * "Levelized  Cost Of Electricity" (LCOE) ($/kWh)
        * See Wikipedia page [here](https://en.wikipedia.org/wiki/Levelized_cost_of_electricity)
        * What does the energy landscape look like?

```{figure} https://upload.wikimedia.org/wikipedia/commons/4/48/Electricity_costs_in_dollars_according_to_data_from_Lazard.png
:name: definitions
:align: center
:width: 100%

Source: Mir-445511 via Wikimedia Commons [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) 
```

* Where is wave energy?
    *  [NREL](https://www.nrel.gov/docs/fy22osti/82375.pdf) survey indicates mean $0.57/kWh in 2020
        *  Very small sample
        *  Presumably leaders in industry who were happy to answer
    *  Realistically, closer to an order of magnitude difference (see 2015 [OES report](https://www.ocean-energy-systems.org/publications/articles/document/why-wave-energy-/))
        * **This is the hurdle!** (Look back at Venn diagram)
            * Technology development is active, but commercialization is still challenging
            * Need for economic viability through reduced CapEx/OpEx and proven power production
            * High costs of WEC development due to harsh offshore conditions
            * Importance of a strong track record for attracting investors

* What is the potential for wave energy in Hawaii...

```{figure} ./images/Hawaii_wave_potential.png
---
scale: 100%
align: center
---
Annual wave energy resource compared with 1990 demand. [2002 Feasibility of Developing Wave Power as a Renewable Energy Resource for Hawaii](https://energy.hawaii.gov/wp-content/uploads/2011/10/Feasibility-of-Developing-Wave-Power-as-a-Renewable-Energy-Resource-for-Hawaii.pdf)
```

```{figure} ./images/Hawaii_electricity_sources.png
---
scale: 90%
align: center
---
Hawaii electricity production by source, 2019 
```

```{note}
Much of what is discussed herein is with respect to the utility scale. However, it is important to acknowledge the scalablity of these technologies. At the smaller scale lies "Blue Economy" applications, which includes aquaculture, desalination, instrumentation, unmanned vechicles, disaster relief, micro grids, or really, powering anything not utility scale.
```

## Overview of a Wave Energy Converter (WEC)
* Emphasize the acronym...**WEC**...you'll see it a lot!!!
* Most WECs are defined by 4 subsystems
    1. Hydrodynamic capturer: absorbs wave energy.
    2. Power take-off (PTO): converts wave energy into electricity.
    3. Reaction: anchors WEC and supports other subsystems.
    4. Control and instrumentation: automates and monitors the WEC.

```{figure} ./images/flap_aqwa_marine.png
---
scale: 100%
align: center
---
Oyster 800 submerged ﬂap WEC 
```

* Designs are VASTLY diverse
    * Why can't we all just agree on something?
    * Will see more in later chapters

<video controls muted="true" loop="true" width="600" style="display: block; margin: 0 auto;">
    <source src="../_static/videos/fred_olsen.mp4" type="video/mp4">
</video>
The video above showcases the Fred Olsen and Azura WECs deployed off Kaneohe Bay Marine Cops Base Hawaii (MCBH).

## Metocean Parameters Affecting WECs
* Wave regimes: deep vs shallow
    * Scale dependent (relative depth)
* Largest variability is associated with wave period
* Energy proportional to square of wave height
    * Steeper waves tend to result in better performance
    * However, want to stay out of breaking waves
* We established wind as primary forcing mechanism in very beginning
    * Examples of optimal regions: Southern Hemisphere, North Atlantic, West Coasts.
    * Let's look at a global animation of the wave field

<video controls muted="true" loop="true" width="800" style="display: block; margin: 0 auto;">
    <source src="../_static/videos/global_waves.mp4" type="video/mp4">
</video>


* Other parameters?
    * Think "propagation"
    * Local vs global
    
```{figure} ./images/Hawaii_bathymetry.png
---
scale: 100%
align: center
---
Hawaii digital elevation model (DEM) A.K.A "bathymetry"
```

## Essential Features of WEC
* WEC survivability in extreme ocean conditions.
    * Extreme loads
    * Fatigue cycles
    * Corrosive environment
* Low LCOE
    * Minimum maintenance.
        * Costs for ship, crew, fuel, etc. add up quick (think OpEx).
    * Smooth power and high capacity factor (see section below).
* Scalability: target is several megawatt
* Environmentally friendly

There are some technical metrics we can introduce here as well...

* Capture Width Ratio (CWR)
 
$$
CWR = \frac{P_{absorbed}}{P_{wave} \times \text{Width}} 
$$ (CWR)

in which it is clear that a higher CWR will reduce the LCOE because the device is absorbing a higher percentage of incident energy. It should also be pointed out that $P_{absorbed}$ doesn't necessarily include the full wave-to-wire power transfer, so it's important to understand how $P_{absorbed}$ is defined.

* Theoretical limit for (hydrodynamic?) CWR...
    * (anti-) symmetric $= 50\%$ (e.g. heave point and pitching flap)
    * non-symmetric $\approx 100\%$ (e.g. Salter's Duck)
* Typical (hydrodynamic?) CWR values...
    * Floating overtopping $\approx 17\%$
    * Oscillating water column $\approx 29\%$
    * Point absorber $\approx 16\%$
    * Bottom fixed pitching flap $\approx 37\%$

Other metrics to be noted...

* Max-to-Mean Ratio
    * Influences engineering design
    * Can be reduced with multiple PTOs
        * Can you explain why?
    * Lower means smoother power and more uniform design

* Weight-to-Power Ratio
    * Gives indication of amount of material relative to power rating

```{warning}
Care should be taken when comparing metrics, as they often ignore nuance.
```

**A good wave absorber must be a good wave-maker**
  
## WEC Economics 
* Annual Energy Production (AEP)
    * Total energy produced over a one year period

$$
&AEP = \text{Annual Average Power Production} \times 8760 \text{hrs/yr} \\
&AEP = P_{wave} \times \text{Width} \times \epsilon \times \%_{duty} \times 8760 \text{hrs/yr}
$$ (AEP)

in which $P_{wave}$ is the incident wave power per unit width, $\epsilon$ is the wave-to-wire efficiency of the device, and $\%_{duty}$ is the annual duty cycle expressed as a percentage.

```{note}
Most of these variables are dependent on the wave conditions. Therefore, the AEP is often determined through element-wise matrix multiplication then integrated.
```

* Capacity Factor
    * The National Renewable Energy Laboratory (NREL) defines this as "the ratio of the actual time-averaged power generation to the maximum possible power generation of a particular power plant."

$$
\text{Capacity Factor} =  \frac{\text{Annual Average Power Production}}{\text{Rated Power Capacity}} 
$$ (CF)

in which the "Annual Average Power Production" can be estimated from {eq}`AEP` above and the "Rated Power Capacity" (for most intents and purposes, same as "installed power capacity") is "the maximum power than can be generated over a sustained time frame, say one or more hours, without damaging or overheating the equipment" (see Chap. 5).

```{note}
The "Rated Power Capacity" is often determined by the generator performance specifications. 
```

* Economically speaking: many small WECs $\neq$ one large WEC
    * There are many benefits to a larger system
        * What constitutes a "large system"?
* AEP is more meaningful than "Rated/Installed Power Capacity"...don't let the media fool you!!!
* Proximity is another factor to consider

## Power Take-Off Systems
* Slow oscillations with high forces to fast rotation (electric generator).
* PTO efficiency is crucial for overall system performance.
* Most efficient when restricted to one degree of freedom (DOF).
    * Generally less complex and easier to optimize.
* Different PTO systems (hydraulic, mechanical, direct drive).
    * Need to temporarily store/smooth energy.
    * Handle short term power overload.
    * Handle system faults and control losses. 
* Advanced control strategies can enhance power production but increase system wear.

## Summary, Future Outlook, and Conclusions
* Wave energy has a strong potential as part of the future renewable energy mix.
* Ongoing technological improvements needed to reduce costs and increase reliability.
* Opportunities for innovation in scaling, durability, and maintenance.
* Ocean wave energy has significant long-term potential.
* Success depends on innovation, economic viability, and optimal deployment.
* WEC technology continues to evolve, with many challenges ahead.
