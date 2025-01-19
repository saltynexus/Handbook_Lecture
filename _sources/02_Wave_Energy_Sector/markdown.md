# Chapter 2: The Wave Energy Sector
* Sparse at best in Hawaii, but high potential to adapt
    * Ship yards
    * Marine construction
    * Environmental permitting and planning
    * Universities
* Demand is there: [Hawai‘i CLEAN ENERGY INITIATIVE](https://energy.hawaii.gov/hawaii-clean-energy-initiative/)
    * "In 2023, Governor Josh Green, M.D. renewed Hawai‘i’s commitment to achieve the nation’s first-ever 100 percent renewable portfolio standards (RPS) by the year 2045."

## Introduction
* Why wave energy and why now?
    * environmental impact: climate change
    * fossil fuel depletion
        * what does this mean for the price of oil?
    * energy security
    * energy diversity
    * LOCAL job creation
        * Saw the potential...inter-island export?
* What are the local social issues?
* What does a solution look like for Hawaii?
    * CSI-WECs
    * Co-design
* Most of money is spent on materials and workmanship as opposed to handling the fuel
* Recall the challenge...techno-economic feasibility leaves wave energy still in R&D phase
    * Focus on optimization of structures, operations, controls, etc.
    * Still heavily dependent on political support.
* LCOE margin is less for island communities...
    * Hawaii has two options: 1) wait and buy or 2) build

## Global and Regional Estimates of Wave Energy Potential
* What waves are we talking about?
    * "sea states"
    * wave climate
* Wave energy as a vast resource...
    * about 3.5 TW global resource (theoretical)
        * extrapolating studies suggests 2/3 can be recovered
    * global average electrical power consumption in 2008: about 2 TW
    * key takeaway: wave energy alone has potential to meet global demand
        * realistically, it has the potential to diversify the portfolio (recap importance)

```{figure} ./images/global_power.png
---
scale: 80%
align: center
---
Annual gross wave power (theoretical)
```

* We can see the hot spots in the figure above
    * Northern and Southern oceans
    * West coasts (land perspective)
        * animation from Chapter 1 should have given clue why

* Recent 32-year hindcast for Hawaii [Medina et. al., 2019 PNNL-29370](https://tethys-engineering.pnnl.gov/publications/high-resolution-regional-wave-hindcast-hawaii)
    * Recall metric: max-to-mean
    * Take look at spatial distributions...

```{figure} ./images/hawaii_power.png
---
scale: 60%
align: center
---
Annual
```

```{figure} ./images/hawaii_power_january.png
---
scale: 80%
align: center
---
January 
```

* Observations
    * Annual averages appear to be on par with previous studies
    * Northern coasts experience greatest power
        * Look at example...
     
$$
\text{Deep Water Wave Power} = \frac{\rho g^2}{64\pi}H^2 T
$$

For the sake of argument, assume a wave height of 10ft with a period of 15s in deep water. Plugging in the values gives a wave power of about 735kW/m (nearly 1MW/m), which is off the chart in the figure above. 

```{figure} ./images/perspective.png
---
scale: 80%
align: center
---
Wave power in perspective.
```

Obviously this is a big wave, but it's not unheard of on the North Shore. On Jan 6th 2024, the [Waimea buoy](https://cdip.ucsd.edu/m/products/?stn=106p1) recorded a **significant** wave height of about 10ft with a **peak** period of 15s, which are statistical properties of a wave field. Of course this doesn't happen often, hence the averages are lower. I should also point out that the photo is a breaking wave, which is larger than the offshore height due to shoaling, but it helps to put things into perspective when we talk about wave power **per metere**. 

```{note}
Wave energy (and power) scales with the square of the wave height!
```

## Historical Development of Wave Energy Converters (WECs)
* Early attempts to harness wave energy date back to the 1800s.
* The modern era of wave energy research began in the 1970s, influenced by the oil crisis.
    * Stephen Salter: "Salter's Duck"...

```{figure} ./images/salters_duck.png
---
scale: 80%
align: center
---
Testing of asymetric body (yellow device) in wave flume.
```
 
* Current focus on commercial-scale WEC development
    * Strongest efforts in Europe
    * USA has been picking up pace

## Types of Wave Energy Converters
* Different ways to categorize, but in general categories are quite limited 
* For eample, three main types of WECs:
    1. Terminators: devices with large horizontal extensions parallel to wave propagation. 
    2. Attenuators: devices perpendicular to wave propagation
    3. Point Absorbers: devices with small extensions compared to the wavelength.

```{figure} ./images/waves_offshore.png
---
scale: 80%
align: center
---
Categorization of WECs
```
* Within these three categories, what are the main features?
* Other categorizations include
    * location
        * Onshore WECs: fixed to the coast (e.g., oscillating water columns).
        * Near-shore WECs: installed in shallow waters, often bottom-mounted.
        * Offshore WECs: floating devices in deep waters, where waves are not influenced by the seabed.
    * working principles, for example...

```{figure} ./images/OWC.png
---
scale: 60%
align: center
---
Oscillating Water Column (OWC)
```

```{figure} ./images/OWC2.png
---
scale: 80%
align: center
---
OWC principles
```

```{figure} ./images/Pelamis.png
---
scale: 80%
align: center
---
Pelamis attenuator
```

```{figure} ./images/Ceto_buoy.png
---
scale: 80%
align: center
---
Carnegie CETO buoy
```

```{figure} ./images/Langlee_flap.png
---
scale: 80%
align: center
---
Langlee dual pitching flap
```

```{figure} ./images/wave_dragon.png
---
scale: 80%
align: center
---
Wave Dragon overtopping
```

```{figure} ./images/Wavestar.png
---
scale: 80%
align: center
---
Wavestar multibody
```

```{note}
This is a **VERY** small subset of examples and there is no silver bullet in design. Alot is dependent upon location, resources, etc.
```

## Testing and Development of WEC Prototypes


```{figure} ./images/dev_diagram.png
---
scale: 80%
align: center
---
Conceptual develpment flow diagram
```

* Technology Readiness Level (TRL): metric used in development process
    * TRL 1-3: "stage 1: concept"
    * TRL 4: "stage 2: design"
    * TRL 5-6: "stage 3: systems"
    * TRL 7-8: "stage 4: device"
    * TRL 9: "stage 5: economics"

* In USA, we're largely in stages 3-4 range, with a few devices exploring commercial activity
    * Here in Hawaii, we're still largely in stages 1-2, with a few efforts pushing into stage 3
* Real-sea testing is crucial for proving the feasibility and durability of WECs
    * Devices are built/tuned to site characteristics
    * Europe is littered with test sites
    
```{figure} ./images/testsites_europe.png
---
scale: 80%
align: center
---
Distribution of wave energy test sites in Europe
```

* USA, hardly any test sites, BUT...
    * Hawaii hosts one of the few: [WETS](https://tethys.pnnl.gov/project-sites/us-navy-wave-energy-test-site-wets), with more hopefully to come online soon

```{figure} ./images/wets.png
---
scale: 80%
align: center
---
Hawaii Wave Energy Test Site (WETS)
```

The video highlight clip below showcases some of the WEC deployments at WETS, with emphasis on the [Azura](https://azurawave.com/) device. The site is still actively maintained by [HNEI's Ocean Energy group](https://www.hnei.hawaii.edu/research/ocean-energy/) under the supervision of the US Navy, with devices being tested from around the world.
<video controls muted="true" loop="true" width="600" style="display: block; margin: 0 auto;">
    <source src="../_static/videos/WETS_presentation.mp4" type="video/mp4">
</video>

## Summary, Future Outlook, and Conclusions
* Wave energy holds significant promise as part of the global renewable energy portfolio.
* International collaboration and policy support as key to advancing the wave energy sector.
* Challenges remain in terms of cost reduction and technical feasibility.
* Continued development of WECs through research, optimization, and scaling.
* With continued R&D, wave energy can play a critical role in a diversified, sustainable energy future.
* Hawaii Marine Energy Center (HMEC)






































