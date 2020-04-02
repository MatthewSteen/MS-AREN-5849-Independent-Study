# A Review and Categorization of Grid-interactive Efficient Building Technologies

# Abstract

https://www.elsevier.com/journals/renewable-and-sustainable-energy-reviews/1364-0321/guide-for-authors

The electricity grid in the United States continues to experience rapid changes both on the supply and demand sides. On the supply side, its generation fuel mix is shifting away from coal and nuclear sources towards natural gas and renewable energy sources. At the same time, grid operators must balance an increasing supply of non-dispatchable and intermittently available sources such as wind and solar. On the demand side, an increasing share of demand is now met by distributed energy resources (DER) such as solar photovoltaics (PV), which are also supplying energy to the grid through net metering. These changes are driven by in large part by retiring less efficient fossil fuel-based generation sources, low natural gas prices, policies supporting renewable energy, and continued decline in renewable energy costs. At the same time, concerns about climate change have also begun to shift both supply-side and demand-side fuel sources away from fossil fuel-based sources to renewable energy sources. Utilities are committing to 100% renewable energy goals as municipalities adopt electrification policies for buildings in an effort to reduce carbon emissions.

Fundamentally, grid operators must balance electricity supply with demand. In order for the operators to have enough generation capacity in reserve to meet periods of peak demand, utilities need to build new generation capacity requiring often costly and long-term investments. To defer the construction of new generation capacity, utilities often implement programs that reduce, shed, or shift load through demand-side management, energy efficiency, or demand response programs. Buildings have the potential to offer grid services through implementation of demand-side management strategies by utilizing existing and new technologies that enhance electrical load flexibility. This presentation summarizes the current literature on grid-interactive efficient buildings (GEBs) that can provide grid services. In particular, the presentation provide categories and examples of measures and technologies that are suitable for GEBs according to the several criteria. These criteria include demand-side management strategies, potential to provide grid services, technology maturity, and ability to perform analysis in whole-building simulation software.

# 1. Introduction

Trend in sources of electricity generation, i.e. renewables increasing 

Trend in building electrification vs. other fuels

How the grid works - supply, demand

How do GEBs fit in to recent trends, needs

>TODO https://github.com/MatthewSteen/MS-CVEN-5849/pull/7#discussion_r389308168
>You may also start with a brief background section to introduce the topic and possibly overview the history (at least in the US) for the EE, DSM, DR, and GEB over the year and the main drivers for these programs.

# Methods and materials - Literature review

>TODO https://github.com/MatthewSteen/MS-CVEN-5849/pull/7#discussion_r389307939
>You may first list some relevant references related to GEB (or load flexbility), DSM, DR, and Grid services. It will be useful to also as part of the methods to provide a summary for the main takeaways and contributions of these references so you can start citing as you describe the various elements of GEBs.

[Grid-interactive Efficient Buildings Technical Report Series: Overview of Research Challenges and Gaps](https://www1.eere.energy.gov/buildings/pdfs/75470.pdf)

## Demand-Side Management

The DOE defines the following DSM strategies for buildings that can be implemented to manage load on the grid.

1. Efficiency 
2. Load Shed  
3. Load Shift
4. Modulate
5. Generate

Efficiency is a reduction in energy use while providing the same or improved level of energy service(s). Graphically **(it would be useful  to add graphs to illustrate each strategy.You may be more creative than the grapgs shown in DOE reports?!)**, efficiency is represented by a y-axis shift downward. Load shed is the ability of a building to reduce electricity use during a short period, which typically occurs during times of peak demand or emergencies and on short notice. Load shift is the ability to change the timing of electricity use, which is graphically represented by flattening the load curve. Modulation is the ability to balance real power supply with demand or the ability to balance reactive power draw with supply...
Generation is the ability to produce electricity for consumption on-site or to dispatch electricity to the grid in response to a signal from the grid operator. For the purposes of GEBs, the DOE identifies load shed, load shift, and modulation as demand flexibility strategies.

## Grid Services

Grid services provide value through avoided electricity system costs by supporting the generation, transmission, or distribution of electricity. The potential value of a DER can be quantified by estimating the avoided cost of acquiring the next least expensive energy resource that provides comparable grid services. Examples of current mature demand-side resources are energy efficiency and demand response. 

### Energy Efficiency

Energy efficiency improves grid reliability by decreasing peak demand and reducing strain on the T&D system. By reducing load, energy efficiency improves reliability on the supply side by increasing the system's reserve margin by offsetting generation that would otherwise be needed. Energy Efficiency also improves T&D reliability by increasing available capacity in both low-voltage and high-voltage systems. To defer costly T&D upgrades, some utilities have used geographically-targeted energy efficiency programs to reduce strain. **(you may list examples of these energy efficiency programs at least qualitatively the main measures considered in these programs).**

From the demand-side perspective, the value that demand reduction from energy efficiency provides is a function of the amount, timing, and location of the savings. From the supply-side perspective, the value of energy efficiency is a function of the system's characteristics such as the peak demand timing (seasonal, diurnal, etc.), load factor, and reserve margin. For example, load reductions that occur during times of peak demand are more valuable than reductions that occur during off-peak times. From the T&D perspective, an important energy efficiency benefit is reduced marginal line losses, which are higher during times of peak demand due to resistive losses that scale non-linearly (i.e. with the square of current according to Joule's first law). These marginal losses must be covered by a utility's generating reserve, which makes on-peak energy efficiency more valuable.  

### Demand Response

In contrast to energy efficiency, which focusses on reducing energy consumption, demand response focusses on reducing peak power requirements through the timing of energy use. Demand response is also the most common form of demand flexibility currently in use in commercial and residential buildings. From the perspective of building owners, demand response can provide reduced utility costs by avoiding high peak demand charges and providing incentives for reducing demand during peak periods. From the perspective of the grid, demand response can provide increased reliability by reducing operating costs and deferring or avoiding capital upgrade costs. 

Demand response can be classified into two types, dispatchable and nondispatchable, depending on who initiates the response to a peak demand event. Dispatchable demand response is initiated by the utility, grid operator, or third-party aggregator to directly control building systems to reduce demand during a peak event. Nondispatchable demand response is initiated at the building in response to price signals. **Again some specific programs and strategies would be useful to list as examples.**

## Grid Services Potential

TODO

## Grid-Interactive Efficient Buildings

### Characteristics

The DOE defines a GEB as "an energy efficient building that uses smart technologies and on-site DERs to provide demand flexibility while co-optimizing for energy cost, grid services, and occupant needs and preferences, in a continuous and integrated way". DOE characterizes GEBs further as having four general characteristics.

1. Efficient
2. Connected
3. Smart
4. Flexible

First, GEBs reduce demand on the grid by using less energy through efficiency. Second, they are connected allowing two-way communication with the grid by sending and receiving signals to respond to time-dependent needs. Third, GEBs are smart by using sensors and controls that allow the co-optimization of cost functions from the perspective of the building owner, occupants, and grid through the use of analytics. Finally, they are flexible allowing loads to be shaped dynamically. These characteristics are facilitated by capabilities at the component level and system level where individual components can monitor and send information about their status and receive control commands to shed, shift, or modulate loads from the building's control system.

### Operational Strategies

TODO

## Technologies

Technologies that are suitable for GEBs are organized below by design discipline. Alternatively, these could be organized based on commonalities (if any) in the literature review.

### Architectural

[Grid-interactive Efficient Buildings Technical Report Series: Windows and Opaque Envelope](https://www1.eere.energy.gov/buildings/pdfs/75387.pdf)

Architectural technologies that are suitable for GEBs include systems that separate the outdoor environment from the conditioned indoor environment (collectively the building envelope). These systems can be divided into the opaque envelope (floors, roofs, walls) and windows, and further categorized as having static, dynamic, or both properties that provide grid services through demand-side management strategies. Architectural technologies affect cooling, heating, and lighting energy end uses by decreasing assembly thermal transmittance (U-factor), decreasing or increasing solar heat gain through windows, or by allowing or blocking visible light to interior spaces.  

#### Static Systems

Static building envelope systems do not have dynamic or time-varying properties relying instead on inherent high performance properties that manage heat transfer, thermal bridging, and air flow (infiltration) through the system assembly. These properties can be a result of a single system component that contributes to the assembly's overall performance, such as a layer of insulation with high thermal resistance (R-value), or the result of multiple system components, such as reduced thermal bridging and air flow. Because static envelope systems do not have dynamic properties they are primarily an energy efficiency DSM strategy, although they can passively shift load by delaying peak cooling and heating loads compared to lower performing systems. In some cases, a high performance envelope (i.e., with high thermal resistance, for instance) can be detrimental to energy use by trapping heat and increasing cooling load. 

ADD EXAMPLES, CONSIDER INCLUDING RESILIENCY TERMS (PASSIVE SURVIVABILITY ETC)

#### Dynamic Systems

Window Systems

* Dynamic Glazing
* Automated Attachments
* Photovoltaic Glazing

Dynamic building envelope systems have properties that can be actively modified to decrease or increase their performance to achieve desired DSM strategies and grid services. Currently available dynamic envelope technologies include dynamic glazing and automated attachments. 

Dynamic glazing technologies include electrochromic glazing and thermochromic glazing that change tint (solar heat gain coefficient, SHGC) allowing more or less solar radiation into the building. Electrochromic glazing has more than one tint state (SHGC) compared to non-dynamic glazing, that can be changed by applying electric voltage to an electrochromic layer. Thermochromic glazing passively responds to temperature to change its SHGC. 

Automated attachments include exterior and interior devices that open or close to allow or block solar radiation into the building. Examples include interior devices such as blinds and shades, and exterior devices such as awnings or shutters. 

Photovoltaic glazing generates electricity the same way that traditional photovoltaic modules do, but are semi-transparent or transparent allowing some portion of visible light to pass through. Thus, PV glazing acts as part of an electricity generating system and a window system.

Opaque Systems

* Tunable Thermal Conductivity Materials
* Thermally Anisotropic Systems
* Thermal Storage
* Moisture Storage and Extraction
* Variable Radiative Technologies
* Building-Integrated Photovoltaics

Tunable thermal conductivity materials have thermophysical properties that can be dynamically adjusted to produce a desired thermal performance. For example, during cooling periods these materials would have high thermal transmittance (low R-value) when the outdoor temperature is lower than the indoor temperature to precool the building effectively acting like night flushing without the need for mechanical ventilation. Conversely, in the heating season these materials would have low thermal transmittance (high R-value) to minimize heat loss to the outdoors.**(In these descriptions of various technologies, you can list examples of technologies based on the technical literature/journals, that is Buildings and Energy, Applied Energy, etc.)**

Thermally anisotropic systems include components and assemblies with areas of high and low thermal conductivity that allows heat to be routed through the envelope to a heat sink such as a plumbing loop.

Thermal storage materials have variable heat capacity properties that allow them to release or store heat. They behave similarly to passive thermal mass, such as strategically adding materials with high heat capacity, but with less volume and weight. Phase change materials (PCMs) are a type of thermal storage material that passively charge and discharge. PCMs are currently available but are not widely used in buildings.

Moisture storage and extraction...

Variable radiative technologies include materials that can reject heat during the daytime or even in direct sun. Cool roofs are a well established strategy to reduce cooling loads in warm/hot climates that are not appropriate for colder climates because they do not decrease energy use. These strategies are currently passive, but if they could be dynamically controlled to change their radiative heat transfer properties they could provide additional grid services through expanded DSM functions.

Building-integrated photovoltaics, although part of a building's electrical system, refer to PV integrated into the opaque portions of the envelope. For example, wall cladding or roof shingles. 

### Electrical

[Grid-interactive Efficient Buildings Technical Report Series: Lighting and Electronics](https://www1.eere.energy.gov/buildings/pdfs/75475.pdf)

Electrical technologies that are suitable for GEBs include lighting systems, consumer electronics, and information technology (IT) equipment. 

#### Lighting

Currently, the use of lighting for grid services is low, with and estimated 4% of commercial buildings reporting demand responsive lighting in the 2012 CBECS (EIA 2012). Historically, lighting systems have not been used for demand response because they are not inherently capable of shifting their load and are generally considered a critical load in occupied spaces, i.e. for safety, productivity, and comfort so they cannot be completely turned off. The primary demand response strategy of dimming is restricted to a small range that will not compromise safety, productivity, and comfort of building occupants. Lighting is only valuable to the grid at the whole building level **(depending on the building type?!)** because the average power of a single lamp is small relative to other individual loads, therefore the commercial building sector is the most viable market for grid-responsive lighting systems. In addition to demand response, lighting systems can be used for demand-side management by reducing building peaks, which is typically accomplished by dimming to shed load. However, California's 2016 energy standard (Title 24) requires that all buildings greater than 10,000 ft2 must be capable of automatically reducing lighting power by 15% in response to a signal from the grid. 

The following lighting technologies are suitable for GEBs according to the DOE (DOE-3 2019).

1. Advanced Sensors and Controls
2. Hybrid Daylight SSL Systems
3. SSL Displays

Advanced sensors and controls improve the ability of connected lighting systems to adjust their power-consuming features such as light levels and spectrum, sensors, or network interfaces through embedded control algorithms. These technologies would enable lighting systems to interact with the grid and other building-level sensors and controllers to reduce loads and provide the grid with contingency reserves and frequency regulation. The market for these technologies is expected to grow significantly in the commercial building sector, with one estimate predicting 35% penetration by 2035 (Penning et. al. 2017)

Hybrid daylight SSL systems collect and redistribute daylighting to enhance their ability to provide light to spaces. These technologies include devices that concentrate daylight through the use of mirrored lenses, beam splitters that filter nonvisible light, and light guiding and diffusing systems that redistribute light to the building (e.g. fiber optic cables). These systems are connected by photosensors and controllers that automatically modulate electric lighting in real-time. Hybrid daylight SSL systems primarily provide the grid with efficiency, but can also provide load shedding and modulation. These systems have been available for many years, but have been adopted slowly by the market due to the high cost of fiber optic cable, low light transfer efficiency, and installation difficulty.

SSL displays are connected lighting displays that use electric lighting to replace natural light from from windows and skylights. These systems mimic the direct and diffuse light from the sun and can increase a building's envelope performance if their thermal performance is better compared to the windows and skylights that they replace. SSL displays can provide some demand response capabilities, mainly by shedding load during peak periods through modulating light output and other energy consuming components. The market for this technology is currently small because of limited application (spaces without windows or skylights), high costs, and customer preference for windows.

Beyond grid services, these lighting technologies have additional benefits such as energy performance, human health, and resilience.

#### Equipment

Electronic equipment including consumer electronics and IT equipment technologies have the potential to provide grid services. These energy using devices are a subset of MELs, which represent electrical loads other than those related to core building functions such as lightnig, HVAC, and SWH (Sofos 2016). Historically, energy efficiency has focused on non-MELs loads because they have made up the largest proportion of energy use. However, as the efficiency of these end uses has improved, the proportion of energy use by MELs has increased in total energy use and percent of total (EIA 2019). 

Current demand response programs tend to focus on HVAC systems in commercial buildings or large industrial equipment not electronics, which are more typically the target of demand side management programs that prescriptively improve efficiency. Additionally, electronic equipment does not typically include technologies that allow for automated demand response. Additionally, electronic can have significant variation in their energy use profiles unlike other building loads, which limits their ability to provide demand-side management strategies.

The primary market for grid-interactive electronics is large commercial office buildings and industrial data centers where a significant portion of the building's energy use is attributed to this end use.

The DOE classifies electronics into the following categories (DOE-3 2019).

1. Continuous-Operation Electronics
2. Battery-Powered Electronics
3. Electronic Displays

Continuous-operation electronics include stationary equipment that more or less operate continuously and require a constant power supply. Examples include network equipment, stationary (desktop) computers, servers, and AV equipment. This type of electronic equipment generally uses the same amount of energy but some devices can operate in low power modes. This category of electronics has the highest relative potential to provide grid services because the equipment is constantly connected to a power supply and often operating continuously. Energy efficiency improvements offer the greatest opportunity for demand-side management by integrating low power, standby, deep sleep, or power scaling modes. Staging the operation of this equipment also has the potential to reduce building peak demand. Additional grid services could include load shedding and modulation of grid-responsive servers in data centers and offices.

Battery-powered electronics include equipment with an internal rechargeable battery that require a power supply to periodically recharge. Examples include portable (laptop) computers, UPS, and miscellaneous electronics such as mobile phones. The energy use of this type of equipment ranges from cycling in the case of a laptop computer to always on in the case of a UPS. This type of equipment has moderate relative potential to provide grid services because many of these devices are portable (disconnected from the grid), do not operate continuously, and generally are a smaller portion of total building loads. Additionally, these devices are usually already energy efficient because they are designed to maximize battery life further limiting their potential. However, grid-responsive power supplies for these devices could provide load shifting to benefit the grid and building peak demand, especially UPS battery backups because they are usually always on and require more power than other devices in this category.

Electronic displays include monitors that are used for signage (e.g. flight information display systems), computers, and televisions, which can range from low power mode to always on. This category of electronics has low relative potential to provide grid services because they generally represent a very small portion of overall energy use in a building. However, there are opportunities for additional energy efficiency through dimming, automatic brightness control, occupancy control, and emerging technologies such as OLEDs and quantum dots.

### Mechanical

[Grid-interactive Efficient Buildings Technical Report Series: HVAC, Water Heating, Appliances and Refrigeration](https://www1.eere.energy.gov/buildings/pdfs/75473.pdf)

TODO - add qualitative potential to provide grid services for each considered technology

Mechanical systems comprise the heating, ventilating, air conditioning, and refrigeration (HVACR) systems in buildings, which often make up a large portion of energy use in commercial buildings. 

The DOE has identified the following HVACR strategies.

1. Smart Thermostats (not considered here) **As we discussed, include all potential suitable technologies for any building type.**
2. Separate Sensible and Latent Space Conditioning
3. Liquid Desiccant Thermal Energy Storage
4. Advanced Controls for HVAC Equipment with Embedded Thermostats (not considered here)
5. Hybrid Evaporative Precooling for AC
6. Dual-Fuel HVAC Systems (not considered here)

Traditional heating and air conditioning systems couple sensible (temperature) and latent (moisture) control into the same component, e.g. a vapor-compression (direct expansion, DX) cooling system. These systems often have enlarged evaporators, operate at a lower temperature, or extend the operating cycle to remove moisture from the air stream, which can overcool the supply air resulting in the need to reheat the air before it is delivered to the space. Overcooling and reheating consequently increase energy and demand during the cooling season. Decoupled sensible and latent air conditioning systems using liquid or solid desiccants, membrane dehumidifiers, and other technologies can remove moisture from the air without changing its temperature. Independently controlling sensible and latent cooling stages could provide grid flexibility by shifting from less efficient sensible cooling to more efficient latent cooling during peak periods. **Again try to provide specific quantative potential benefits based on any reported technical studies for this as well as any other described technology...**

Liquid desiccant thermal energy storage (TES) use a chemical that absorb moisture from indoor air and then rejects it to the outdoors through a heating cycle known as regeneration. This type of TES stores energy chemically and does not require insulated storage tanks because liquid desiccants can be stored at ambient temperatures. The efficiency of these systems is not driven by round-trip efficiency losses as with other energy storage technologies (thermal, battery, etc.), rather it is a function of the heating needed for the regeneration process. Solar thermal coupled with this technology can be an effective way to regenerate the liquid desiccant without the need for additional energy input because peak solar radiation and latent cooling often occur coincidentally during the day.

Hybrid evaporative precooling for AC combines evaporative cooling with vapor-compression cooling to increase efficiency in dry climates by shifting cooling from the high intensity vapor-compression cycle to a lower intensity evaporative process, thus reducing peak cooling demand. Evaporative modules can be packaged with vapor-compression systems or added to existing systems during a retrofit. 

The DOE has also identified the following "cross-cutting" technologies that provide demand flexibility across more than one HVACR end use. 

1. Thermal Energy Storage
2. Modulating Capacity Vapor Compression
3. Non-Vapor-Compression Materials and Systems

Thermal energy storage ranges from passive systems that use additional thermal mass or insulation in a building's envelope to active systems that rely on phase change to store and release energy in an optimized sequence. These systems can be used for cooling-only, heating-only, or both cooling and heating. Active TES systems cool or heat materials to store energy during low cost periods so that it can be used during high cost periods with less energy input. The round-trip efficiency of these systems is typically around 80% because of thermal losses to the surroundings (Guess 2018; Energy Storage Association 2019). 

Modulating capacity vapor compression systems can be used in ACs, heat pumps, HPWHs, and heat pump dryers to more precisely control temperatures compared to systems that cycle all the way on/off. 

Non-vapor-compression materials and systems include several space cooling and refrigeration technologies that use specialized materials or alternative systems designs rather than the traditional VC cycle. These include solid-state NVC (define?) technologies such as thermoelectric, magnetocaloric, and electrocaloric systems that produce useful temperature differences when the solid-state material is activated by electrical input. Other technologies include membrane, thermoelastic, Stirling, liquid desiccant, and thermoacoustic systems that use electrical or thermal input to change the property (e.g. phase) of a material (e.g. working fluid) to pump heat. These technologies could offer grid benefits by modulating capacity, separating sensible and latent cooling, and thermal storage.

### Plumbing



# Results

Categorize measures and technologies that are suitable for GEBs.

* Bassed on design discipline
  * Architectural
  * Electrical
  * Mechanical
  * Plumbing
* Based on literature review

# Discussion

TODO

# Conclusions

TODO
