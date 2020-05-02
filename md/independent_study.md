# A Review and Categorization of Grid-interactive Efficient Building Technologies for Building Performance Simulation

# 1. Introduction

In the United States, the electricity grid continues to experience rapid changes both on the supply and demand sides. On the supply side, its generation fuel mix is shifting away from coal and nuclear sources towards natural gas and renewable energy sources. At the same time, grid operators must balance an increasing supply of non-dispatchable and intermittently available sources such as wind and solar, which are projected to be the fastest growing electricity resource through 2050 (EIA, 2020). On the demand side, an increasing share of demand is now met by distributed energy resources (DER) such as solar photovoltaics (PV), both of which are also supplying energy to the grid through net metering. These changes are driven mostly by retiring less efficient fossil fuel-based generation sources, low natural gas prices, policies supporting renewable energy, and continued decline in renewable energy costs. At the same time, concerns about climate change have also begun to shift both supply-side and demand-side fuel sources away from fossil fuel-based sources to renewable energy sources. Utilities are committing to 100% renewable energy goals as municipalities adopt electrification policies for buildings in an effort to reduce carbon emissions.

Fundamentally, grid operators must balance electricity supply with demand. In order for the operators to have enough generation capacity in reserve to meet periods of high peak demands, utilities need to build new generation capacity requiring costly and long-term investments. To defer the construction of new generation capacity, utilities often implement programs that reduce, shed, or shift load through demand-side management, energy efficiency, or demand response programs. Buildings, which collectively consumed 63% of delivered electricity in the U.S. in 2019 (15% residential, 12% commercial, 35% industrial, EIA 2020), have the potential to offer grid services through implementation of demand-side management strategies that enhance electrical load flexibility. Grid-interactive efficient buildings (GEBs) that use existing and new technologies to provide demand flexibility have recently emerged as a way to balance the grid's supply and demand and a source of value through avoided electricity system costs (DOE, 2019a).

This report reviews and summarizes the current literature on technologies suitable for GEB applications. No comprehensive reviews for such technologies have been reported in the current body of literature. The presented review attempts to categorize the GEB technologies according to several criteria. These criteria include demand-side management strategies, potential to provide grid services, technology maturity, and ability to perform analysis and evaluation in whole-building simulation software. The report is organized into four main sections. Section 2 provides background about how buildings interact with the electrical grid through demand-side management, grid services , and demand response. Section 3 summarizes the literature review followed by the Results, Discussion, and Conclusions in Sections 4 and 5. 

# 2. Background

The U.S. DOE defines a GEB as an energy efficient building that uses smart technologies and on-site DERs to provide demand flexibility while co-optimizing for energy cost, grid services, and occupant needs and preferences, in a continuous and integrated way (DOE, 2019a). Specifically, the DOE characterizes GEBs further as having four general characteristics:

- Efficient
- Connected
- Smart
- Flexible

First, GEBs reduce demand on the grid by using less energy through efficiency. Second, they are well connected to allow two-way communication with the grid by sending and receiving signals in order to respond to time-dependent needs. Third, GEBs are smart by integrating sensors and controls that allow for the co-optimization of cost functions from the perspective of the building owner, occupants, and grid through the use of analytics. Finally, they are flexible so their energy loads can be shaped dynamically to meet any grid services and/or signals. These characteristics are facilitated by capabilities at the component level and system level where individual components can monitor and send information about their status and receive control commands to shed, shift, or modulate loads from the building's control system.

## 2.1 Demand-Side Management

The DOE defines the following demand-side management (DSM) strategies for buildings that can be implemented to manage load on the grid.

1. Efficiency
2. Load Shed
3. Load Shift
4. Modulate
5. Generate

Efficiency is a reduction in energy use while providing the same or improved level of energy service(s). Graphically **(it would be useful  to add graphs to illustrate each strategy.You may be more creative than the grapgs shown in DOE reports?!)**, efficiency is represented by a y-axis shift downward. Load shed is the ability of a building to reduce electricity use during a short period, which typically occurs during times of peak demand or emergencies and on short notice. Load shift is the ability to change the timing of electricity use, which is graphically represented by flattening the load curve. Modulation is the ability to balance real power supply with demand or the ability to balance reactive power draw with supply...TODO
Generation is the ability to produce electricity for consumption on-site or to dispatch electricity to the grid in response to a signal from the grid operator. For the purposes of GEBs, the DOE identifies load shed, load shift, and modulation as demand flexibility strategies (DOE, 2019a). 

### Energy Efficiency

Energy efficiency improves grid reliability by decreasing peak demand and reducing strain on the transmission and distribution (T&D) system. By reducing load, energy efficiency improves reliability on the supply side by increasing the system's reserve margin by offsetting generation that would otherwise be needed. Energy Efficiency also improves T&D reliability by increasing available capacity in both low-voltage and high-voltage systems. To defer costly T&D upgrades, some utilities have used geographically-targeted energy efficiency programs to reduce strain. **(you may list examples of these energy efficiency programs at least qualitatively the main measures considered in these programs).**

From the demand-side perspective, the value that demand reduction due to energy efficiency provides is a function of the amount, timing, and location of the savings. From the supply-side perspective, the value of energy efficiency is a function of the system's characteristics such as the peak demand timing (such as seasonal and diurnal on-peak periods), load factor, and reserve margin. For example, load reductions that occur during times of on-peak demand are more valuable than reductions that occur during off-peak times. From the T&D perspective, an important energy efficiency benefit is reduced marginal line losses, which are higher during times of peak demand due to resistive losses that scale non-linearly (i.e. vary with the square of current according to Joule's first law). These marginal losses must be covered by a utility's generating reserve, which makes on-peak energy efficiency more valuable.  

### Demand Response

In contrast to energy efficiency, which focusses on reducing energy consumption, demand response aims at lowering peak power requirements through the timing of energy use. Demand response is also the most common form of demand flexibility currently in use in commercial and residential buildings. From the perspective of building owners, demand response can provide reduced utility costs by avoiding high peak demand charges and providing incentives for reducing demand during peak periods. From the perspective of the grid, demand response can provide increased reliability by reducing operating costs and deferring or avoiding capital upgrade costs. 

Demand response can be classified into two types, dispatchable and nondispatchable, depending on who initiates the response to a peak demand event. Dispatchable demand response is initiated by the utility, grid operator, or third-party aggregator in order to directly control building systems to reduce demand during a peak event. Nondispatchable demand response is initiated at the building in response to price signals. **Again some specific programs and strategies would be useful to list as examples.**

## 2.2 Grid Services

Grid services provide value through avoided electricity system costs by supporting the generation, transmission, or distribution of electricity. The potential value of a DER can be quantified by estimating the avoided cost of acquiring the next least expensive energy resource that provides comparable grid services. Examples of current mature demand-side resources are energy efficiency and demand response. 

## Grid Services Potential

TODO

### Operational Strategies

TODO

# 3. Literature Review

This section reviews the current reported literature on the benefits of GEBs and the technologies that are suitable for GEB applications. The technologies are organized from a building design perspective according to design disciplines. Each technology is described briefly in the context of its ability to contribute to DSM strategies and thus provide services to the grid and ultimately be suitable for GEBs. 

## 3.1 Architectural

Architectural technologies that are suitable for GEBs include systems that separate the outdoor environment from the conditioned indoor environment (collectively, they are specific to the building envelope). These systems can be divided into the opaque envelope (floors, roofs, walls) and windows, and further categorized as having static, dynamic, or both properties that provide grid services through demand-side management strategies. Architectural technologies affect cooling, heating, and lighting energy end uses by decreasing assembly thermal transmittance (U-factor), decreasing or increasing solar heat gain through windows, or by allowing or blocking visible light to interior spaces.

### 3.1.1 Static Systems

Static building envelope systems do not have dynamic or time-varying properties relying instead on inherent high performance properties that manage heat transfer, thermal bridging, and air flow (infiltration) through the system assembly. These properties can be a result of a single system component that contributes to the assembly's overall performance, such as a layer of insulation with high thermal resistance (R-value), or the result of multiple system components, such as reduced thermal bridging and air flow. Because static envelope systems do not have dynamic properties they are primarily an energy efficiency strategy, although they can passively shift load by delaying peak cooling and heating loads compared to lower performing systems. In some cases, a high performance envelope (i.e., with high thermal resistance, for instance) can be detrimental to energy use by trapping heat and increasing cooling load. Static architectural systems are generally not suitable for GEBs because they don't have dynamic properties enabling them to interact with the grid.

### 3.1.2 Dynamic Systems

Dynamic building envelope systems have properties that can be actively modified to decrease or increase their performance to achieve desired DSM strategies and grid services. These technologies can be categorized as either opaque or window systems and include the following technologies (DOE, 2019b).

Opaque Systems

- Tunable Thermal Conductivity Materials
- Thermally Anisotropic Systems
- Thermal Storage
- Moisture Storage and Extraction
- Variable Radiative Technologies
- Building-Integrated Photovoltaics

Window Systems

- Dynamic Glazing
- Automated Attachments
- Photovoltaic Glazing

Tunable thermal conductivity materials have thermophysical properties that can be dynamically adjusted to produce a desired thermal performance. For example, during cooling periods these materials would have high thermal transmittance (low R-value) when the outdoor temperature is lower than the indoor temperature to precool the building effectively acting like night flushing without the need for mechanical ventilation. Conversely, in the heating season these materials would have low thermal transmittance (high R-value) to minimize heat loss to the outdoors. Several tunable insulation technologies have been reported in the literature (Cui, 2019) and include dynamic insulation materials and adaptive insulation systems. In particular, dynamic insulation materials have been found to reduce annual cooling and heating energy use and cost in commercial buildings by an average of 17% (Shekar, 2017) and by up to 42% in residential buildings (Park, 2015; Menyhart, 2017; Rupp, 2019; Dehwah, 2020). 

Thermally anisotropic systems include components and assemblies with areas of high and low thermal conductivity that allows heat to be routed through the envelope to a heat sink such as a plumbing loop. Biswas et. al (2019) reported experimental results that showed these systems can achieve cooling and heating load reductions of 86% and 63% compared to a baseline wall assembly with traditional cavity insulation, and numerical simulation results showed cooling energy savings of 11% in cooling-dominated climates and heating energy savings of 21% in heating-dominated climates.

Thermal storage materials have variable heat capacity properties that allow them to release or store heat. They behave similarly to passive thermal mass, such as strategically adding materials with high heat capacity, but with less volume and weight. Phase change materials (PCMs) are a type of thermal storage material that passively charge and discharge. PCMs are currently available but are not widely used in buildings. However, PCMs have high potential to offer grid services and have been shown to reduce heating energy use by up to 63% in experimental studies (Nghana, 2016).

Moisture storage and extraction systems use materials that can extract moisture from the indoors, store it, and then reject it to the outdoors. In humid climates and buildings with high internal latent loads (e.g. natatoriums), moisture control is a significant portion of the cooling load which drives peak electrical demand. 

Variable radiative technologies include materials that can reject heat during the daytime or even in direct sun. Cool roofs are a well established strategy to reduce cooling loads in warm/hot climates that are not appropriate for colder climates because they do not decrease energy use. These strategies are currently passive, but if they could be dynamically controlled to change their radiative heat transfer properties they could provide additional grid services through expanded DSM functions. A recently developed metamaterial showed noontime radiative cooling of 93 Watts per square meter under direct sun (Zhai, 2016).

Building-integrated photovoltaics, although part of a building's electrical system, refer to PV integrated into the opaque portions of the envelope. For example, wall cladding or roof shingles. Sehar et. al. (2016) found that PV alone could reduce a building's demand during a demand response event by 16.8%.

Dynamic glazing technologies include electrochromic glazing and thermochromic glazing that change tint (solar heat gain coefficient, SHGC) allowing more or less solar radiation into the building. Electrochromic glazing has more than one tint state (SHGC) compared to non-dynamic glazing, that can be changed by applying electric voltage to an electrochromic layer. Thermochromic glazing passively responds to temperature to change its SHGC. For commercial buildings located in the northern hemisphere, electrochromic glazing is estimated to reduce peak demand by 20-30% for east, south, and west thermal zones with an estimated primary energy savings of 10-20% (LBNL, 2004). 

Automated attachments include exterior and interior devices that open or close to allow or block solar radiation into the building. Examples include interior devices such as blinds and shades, and exterior devices such as awnings or shutters. Tzempelikos et. al. (2013) found that interior shades controlled with a fixed incident solar radiation setpoint reduced cooling loads by 15-33% depending on the building's window-to-wall ratio. 

Photovoltaic glazing generates electricity using the same mechanisms that traditional photovoltaic modules, but are semi-transparent or transparent allowing some portion of visible light to pass through. Thus, PV glazing integrates an electricity generating system and a window system. An optimized PV insulating glass unit has shown to provide 10.7% energy savings when compared to a traditional low-e IGU in whole-building energy simulations (Wang, 2016). 

## 3.2 Electrical

Electrical technologies that are suitable for GEBs include lighting systems, consumer electronics, and information technology (IT) equipment. 

### 3.2.1 Lighting

Currently, the use of lighting for grid services is low, and estimated to represent 4% of commercial buildings reported demand responsive lighting in the 2012 CBECS (EIA 2012). Historically, lighting systems have not been used for demand response because they are not inherently capable of shifting their load. Moreover, lighting is generally considered a critical load for occupied spaces, i.e. for safety, productivity, and comfort so it cannot be completely turned off. The primary demand response strategy of dimming lighting is restricted to a small range that will not compromise safety, productivity, and comfort of building occupants. Lighting is only valuable to the grid at the aggregate whole-building level because the average power of a single lamp is small relative to other individual loads, therefore the commercial building sector is the most viable market for grid-responsive lighting systems. In addition to demand response, lighting systems can be used for DSM by reducing building peaks, which is typically accomplished by dimming to shed load. However, California's 2016 energy standard (Title 24) requires that all buildings greater than 929 m2 (10,000 ft2) must be capable of automatically reducing lighting power by 15% in response to a signal from the grid. 

The following lighting technologies are suitable for GEBs (DOE 2019c).

- Hybrid Daylight SSL Systems
- SSL Displays

Hybrid daylight SSL systems collect and redistribute daylighting to enhance their ability to provide light to spaces. These technologies include devices that concentrate daylight through the use of mirrored lenses, beam splitters that filter nonvisible light, and light guiding and diffusing systems that redistribute light to the building (e.g. fiber optic cables). These systems are connected by photosensors and controllers that automatically modulate electric lighting in real-time. Hybrid daylight SSL systems primarily provide the grid with efficiency, but can also provide load shedding and modulation. These systems have been available for many years, but have been adopted slowly by the market due to the high cost of fiber optic cable, low light transfer efficiency, and installation difficulty. Mayhoub et. al. (2012) found that hybrid solar lighting saved 33% of electricity compared to a base case. 

SSL displays are connected lighting displays that use electric lighting to replace natural light harvested from windows and skylights. These systems mimic the direct and diffuse light from the sun and can increase a building's envelope performance if their thermal performance is better compared to the windows and skylights that they replace. SSL displays can provide some demand response capabilities, mainly by shedding load during peak periods through modulating light output and other energy consuming components. The market for this technology is currently small because of limited applications (i.e. only for spaces without windows or skylights), high costs, and customer preference for windows. 

### 3.2.2 Equipment

Electronic equipment including consumer electronics and IT equipment technologies have the potential to provide grid services. These devices are a subset of miscellaneous electric loads (MELs), which represent electrical loads other than those related to core building functions such as lighting, HVAC, SWH (Sofos 2016). Historically, energy efficiency has focused on non-MELs loads because they have made up the largest proportion of energy use. However, as the efficiency of these end uses has improved, the proportion of energy use by MELs has increased in total energy use and percent of total (EIA 2019). 

Current demand response programs tend to focus on HVAC systems service commercial buildings or large industrial equipment not electronics, which are more typically the target of demand side management programs that prescriptively improve energy efficiency. Additionally, electronic equipment does not typically include technologies that allow for automated demand response. Moreover, electronic can have significant variation in their energy use profiles unlike other building loads, which limits their ability to provide DSM strategies.

The primary market for grid-interactive electronics is large commercial office buildings and industrial data centers where a significant portion of the building's energy use is attributed to this end use.

The following electrical equipment technologies are suitable for GEBs (DOE, 2019c).

- Continuous-Operation Electronics
- Battery-Powered Electronics
- Electronic Displays
- Modulating, Advanced Clothes Dryers (electric)

Continuous-operation electronics include stationary equipment that generally operate continuously and require a constant power supply. Examples of continuous-operation electronics include network equipment, stationary (desktop) computers, servers, and AV equipment. This type of electronic equipment generally uses constant amount of energy but some devices can operate in low power modes. This category of electronics has the highest relative potential to provide grid services because the equipment is constantly connected to a power supply and often operating continuously. Energy efficiency improvements offer the greatest DSM opportunities by integrating low power, standby, deep sleep, or power scaling modes. Staging the operation of this equipment also has the potential to reduce building peak demands. Additional grid services could include load shedding and modulation of grid-responsive servers in data centers and offices.

Battery-powered electronics include equipment with an internal rechargeable storage unit that requires a power supply to periodically recharge. Examples of battery-powered electronics include portable (laptop) computers, UPS, and miscellaneous electronics such as mobile phones. The energy use of this type of equipment ranges from cycling in the case of a laptop computer to always on in the case of a UPS. This type of equipment has moderate relative potential to provide grid services because these devices are generally portable (disconnected from the grid), do not operate continuously, and generally are a smaller portion of total building loads. Additionally, these devices are usually energy efficient because they are designed to maximize battery life further limiting their potential. However, grid-responsive power supplies for these devices could provide load shifting to benefit the grid and building peak demand, especially UPS battery backups because they are usually always on and require more power than other devices in this category.

Electronic displays include monitors that are used for signage (e.g. flight information display systems), computers, and televisions, which can operate at different modes including off (sleep), low power, and always on. This category of electronics has low relative potential for grid services because they generally represent a very small portion of overall energy use in a building. However, there are opportunities for additional energy efficiency through dimming, automatic brightness control, occupancy control, and emerging technologies such as OLEDs and quantum dots.

Appliances are an additional category of electric equipment that can provide grid services. For this review, natural gas appliances are discussed in the Plumbing section. Similar to consumer electronics and IT equipment, appliances are heterogeneous in load profiles and operation schedules. For example, some appliances operate relatively continuously (refrigerators) while others have finite cycles (dishwashers and clothes dryers). Appliances that operate continuously are more likely to benefit the grid by modulating their load. Appliances with finite cycles are most suitable for load shifting because their load can be easily rescheduled to avoid peak periods. These types of appliances have traditionally been targets for DR programs. For clothes dryers, technologies that allow for modulating or staging the heating cycle and delayed start options could be used to provide grid services for energy efficiency and load shifting respectively. Moreover, heat pump clothes dryers offer additional efficiency improvements over traditional electric resistance heating and can also be modulated when they incorporate variable speed compressors. Modulating the heating element allows the moisture removal rate to more closely match the heat input rate, which reduces over drying and improves energy efficiency. Longer cycle times with lower temperature drying allows for better energy efficiency along with load shifting and some load shedding. The highest grid service potential is modulation because electric resistance appliances can respond very quickly (i.e. within seconds) without damage.

## 3.3 Mechanical

Mechanical systems comprise the heating, ventilating, air conditioning (HVAC), and refrigeration (HVACR) systems used to maintain thermal comfort and indoor air quality in buildings. These systems often make up a large portion of energy use in commercial buildings. The following HVACR technologies are suitable for GEBs (DOE, 2019d).

- Separate Sensible and Latent Space Conditioning
- Liquid Desiccant Thermal Energy Storage
- Hybrid Evaporative Precooling for AC
- Dual-Fuel HVAC Systems
- Thermal Energy Storage
- Modulating Capacity Vapor Compression
- Non-Vapor-Compression Materials and Systems

Traditional heating and air conditioning systems couple sensible (temperature) and latent (moisture) control into the same component, e.g. a vapor-compression (direct expansion or DX) cooling system. These systems often have enlarged evaporators, operate at a lower temperature, or extend the operating cycle to remove moisture from the air stream, which can overcool the supply air below temperatures that are typical or comfortable resulting in the need to reheat the air before it is delivered to the space. Overcooling and reheating consequently increase energy use and demand during the cooling season. Decoupled sensible and latent air conditioning systems using liquid or solid desiccants, membrane dehumidifiers, and other technologies can remove moisture from the air without changing its temperature. Independently controlling sensible and latent cooling stages could provide grid flexibility by shifting from less efficient sensible cooling to more efficient latent cooling during peak periods. Decoupled sensible and latent space conditioning has high potential to provide grid services by primarily benefiting energy efficiency, but it can also provide load shedding and shifting opportunities (DOE, 2019d). Research evaluating this technology in packaged terminal air conditioners suggests that efficiency savings of 30% (Alabdulkarem, 2015). Moreover, Kim et. al. (2013, 2014) found that liquid desiccant systems incorporated with evaporatively-cooled DOAS saved from 51% to 68% of annual energy use compared to traditional VAV systems.

Liquid desiccant thermal energy storage (TES) use a chemical that absorb moisture from indoor air and then rejects it to the outdoors through a heating cycle known as regeneration. This type of TES stores energy chemically and does not require insulated storage tanks because liquid desiccants can be stored at ambient temperatures. The efficiency of these systems is not driven by round-trip efficiency losses as with other energy storage technologies (including thermal and electrical systems), but it is rather a function of the heating needed for the regeneration process. Solar thermal coupled with this technology can be an effective way to regenerate the liquid desiccant without the need for additional energy input because peak solar radiation and latent cooling often occur coincidentally during the day. This technology has high potential to provide grid services (DOE, 2019d) by providing load shifting during periods of high demand. Load shed and efficiency have less potential because the desiccant will always need to be recharged at a later time. Efficiency can be improved by using renewable energy to regenerate the desiccant.

Hybrid evaporative precooling for air conditioning (AC) combines evaporative cooling with vapor-compression cooling to increase AC energy efficiency in dry climates by shifting cooling from the high energy intensity vapor-compression cycle to a lower energy intensity evaporative process, thus reducing peak cooling demand. Evaporative modules can be packaged with vapor-compression systems or added to existing systems during a retrofit. This technology has low potential to provide grid services, primarily through efficiency by improving the cooling system's COP. Delfani et. al. (2010) found cooling load savings up to 75% and annual energy savings of 55% for indirect systems that pre-cool air for traditional mechanical cooling in Iran.

Dual-fuel HVAC systems temporarily switch fuels during heating or cooling to provide value to the grid through curtailment. Specifically, grid value is provided when the lower cost fuel is primarily used throughout the year and the more expensive fuel is only used during limited grid events. For example, in regions that experience electric peaks during winter due to the prevalence of electric heating, a heat pump system that switches from electric heat pump heating to natural gas heating during a peak event to shift demand to the natural gas grid. Similarly, absorption cooling, which uses a heat source to provide cooling, can also be used to shift cooling fuel from electricity to natural gas using gas-absorption cooling. Currently, the low cost of natural gas makes using it for electric curtailment infeasible. However, in areas where costly delivered fuel is used for heating (e.g. fuel oil or propane), using it to curtail electric heating can be more cost-effective, especially since the delivered fuel and electricity markets are not interactive unlike the natural gas and electricity markets which are often related. This technology has low potential to provide grid services by shedding load because the switch opportunities are infrequent, mostly during winter peak periods, and are most applicable when to switching from heat pump heating to natural gas or delivered fuel heating. Low natural gas prices are a significant hindrance to the adoption of dual-fuel HVAC systems (DOE, 2019d).

Thermal energy storage (TES) ranges from passive systems that use additional thermal mass or insulation within a building's envelope to active systems that rely on phase change media to store and release energy in an optimized sequence. These systems can be used for cooling-only, heating-only, or both cooling and heating. Active TES systems cool or heat materials to store energy during low cost periods so that it can be used during high cost periods with less energy input. The round-trip efficiency of these systems is typically 80% because of thermal losses to the surroundings (Guess 2018; Energy Storage Association 2019). This technology has high potential to provide grid services primarily through daily load shifting to reduce demand charges. Load shedding is possible when the shift in energy use allows equipment to operate at a higher efficiency, e.g. higher EER at night.

Modulating capacity vapor compression systems can be used in ACs, heat pumps, HPWHs, and heat pump dryers to more precisely control temperatures compared to systems that cycle all the way on and off. This technology has medium potential to provide grid services. It primarily offers energy efficiency improvements as well as thermal comfort, but it can provide load shifting by precooling or preheating the building prior to a peak period thus shifting the load forward allowing the building's thermal inertia to carry it through the peak period. Additionally, a combination of load shifting and shedding could be provided by changing setpoint temperatures without precooling or preheating during a peak period, which sheds load and shifts it to a later time when the setpoints return to their original states. This technology could also provide modulation services by providing frequency regulation and voltage support (through power factor control using power electronics for VSDs). 

Non-vapor-compression (NVC) materials and systems include several space cooling and refrigeration technologies that use specialized materials or alternative systems designs rather than the traditional vapor-compression cycle. These include solid-state NVC technologies such as thermoelectric, magnetocaloric, and electrocaloric systems that produce useful temperature differences when the solid-state material is activated by electrical input. Other technologies include membrane, thermoelastic, Stirling, liquid desiccant, and thermoacoustic systems that use electrical or thermal input to change the property (e.g. phase) of a material (e.g. working fluid) to pump heat. These technologies could offer grid benefits by modulating capacity, separating sensible and latent cooling, and thermal storage. This technology has high potential to offer grid services primarily through energy efficiency and load shifting. However, load shedding and modulation are possible with variable capacity control. Cheon et. al. (2019) indicated that a thermoelectric heat pump in a DOAS increased energy use by 23% compared to a reference system while Lim et. al. (2018) found that a thermoelectric radiant system with a DOAS reduced annual energy consumption by 41% compared to a traditional VAV system.

## 3.4 Plumbing

Plumbing systems suitable for GEBs primarily include SWH. However, plumbing systems also include piping networks for delivering energy resources such as natural gas. Water heaters generally fall into two categories; storage and tankless. Tankless water heaters have limited potential to provide grid services because they are designed to operate on-demand and thus are not able to shift or shed load. In contrast, storage water heaters are well suited for GEBs because TES is inherently part of their fundamental operation, which allows them to decouple power demand from energy consumption and provide load shifting away from peak periods. The following plumbing technologies have been identified to be suitable for GEBs (DOE, 2019d).

- Dual-Fuel Water Heater
- Modulating, Advanced Clothes Dryers (gas)
- Building-Scale CHP

Dual-fuel water heaters can temporarily switch fuels to provide value to the grid through curtailment. Like dual-fuel HVAC systems, these systems provide grid value when the lower cost fuel is mostly used  throughout the year and the more expensive fuel is only used during limited periods. Markets or regions that use electricity and delivered fuels have the highest potential for these systems because delivered fuel costs are generally higher than electricity. Generally, this technology has low potential to provide grid services because it can only provide load shedding opportunities in limited viable markets due to the low cost of natural gas compared to electricity and regional differences in delivered fuel use. Given financial incentives this technology can provide load shedding for infrequent emergencies, but the electric grid will not benefit if natural gas costs less. Park et. al. (2014) reported energy cost savings of 4% in one market for a hybrid heat pump gas-fired water heater.

Similar to electrical appliances, natural gas appliances can offer grid services suitable for GEBs. Specifically, clothes dryers that use natural gas could incorporate modulating or staged heating to improve efficiency, use a delayed start to shift load, or used connected technology to provide load shedding. 

Combined heat and power (CHP), which combines electricity production with waste heat capture and use, can provide grid flexibility by serving on-site electric loads or exporting electricity to the grid while also serving on-site thermal loads (heating directly or cooling through absorption technology). These systems are often used by large buildings and campuses to reduce operating costs by avoiding high consumption and demand charges of grid-tied electricity. Combined heat and power systems can also be used with TES to shift loads to off-peak periods. Operators of these systems can also adjust their dispatch schedule to take advantage of day-ahead and real-time electricity pricing in some markets as well as participate in capacity, energy, and DR markets. This technology has high GEB potential through energy efficiency by producing electricity on-site and avoiding losses, load shedding if able to increase production during a grid event, and load shifting when combined with TES.

## 3.5 Controls

A key part of GEBs are the control systems that connect the discrete systems within a building and allow for "smart" operation through sensors, actuators, and controllers. Advanced control systems have the potential to reduce site energy consumption by 29% in commercial buildings through the use of high performance sequences of operation, occupancy-based optimization, and automated fault detection and diagnostics (Fernandez et. al., 2017). Additionally, advanced control systems can reduce by 10-20% peak demands of commercial buildings (Kiliccote et. al., 2016). CHECK

Control systems cross multiple building systems and applications. The following controls technologies are suitable for GEBs (DOE, 2019d).

- Advanced Sensors and Controls (lighting)
- Smart Thermostats
- Advanced Controls for HVAC Equipment with Embedded Thermostats
- Water Heaters with Smart Connected Controls (electric and gas)
- Advanced Dishwasher/Clothes Washer Controls
- Advanced Residential Refrigerator/Freezer Controls
- Advanced Controls for Commercial Refrigeration

Advanced sensors and controls improve the ability of connected lighting systems to adjust their power-consuming features such as light levels and spectrum, sensors, or network interfaces through embedded control algorithms. These technologies would enable lighting systems to interact with the grid and other building-level sensors and controllers to reduce loads and provide the grid with contingency reserves and frequency regulation. The market for these technologies is expected to grow significantly in the commercial building sector, with one estimate predicting 35% penetration by 2035 (Penning et. al. 2017)

In addition to sensing the zone conditions and controlling the attached HVAC system, smart thermostats are connected to the internet, contain advanced control algorithms, and can connect to home automation systems. These features allow smart thermostats to perform more advanced controls for relatively simple HVAC systems. Smart thermostats are best suited for residential buildings and small commercial buildings where they can serve as a less complicated alternative to SHEMS and BAS. Wang et. al. (2020) estimated that smart occupancy-driven thermostats could save between 11-34% of energy use.

Advanced controls for HVAC equipment with embedded thermostats (HVAC-ET) include HVAC equipment with internal built-in sensors and control algorithms rather than external wall-mounted thermostats. Embedded thermostats are included in window ACs, portable ACs, PTACs, PTHPs, and MSHPs where Wi-Fi is used to communicate directly with grid operators or utilities for demand response programs. These controls allow the compressor to be temporarily turned off or the setpoint to be changed with user overrides.

Smart water heaters include internal or external controls that take advantage of the equipment's inherent TES capability. Preheating the tank during off-peak periods allows for water draws with reduced or no power use during on-peak periods, shifting the water heater's load to benefit the grid without the loss of functionality to the consumer. Load shedding can be accomplished by turning the water heater off for emergency curtailment. Frequency regulation is also possible with water heaters that use electric resistance heating (solely or HPWH) and that allow direct utility control for the fast response time required for frequency regulation. However, frequency regulation may reduce the life of VC equipment. Pourmousavi et. al found that controlling electric water heaters with time-of-use (customer) and balancing reserve (utility) signals reduced on-peak energy use by 95% (Pourmousavi, 2014).

Clothes washers and dishwashers with advanced controls to delay or schedule their discrete cycles could shift loads to off-peak periods but require consideration of user preferences. For example, leaving wet clothes in a washing machine too long could cause concerns, but combined clothes washer-dryer appliances is one technology that could alleviate concerns. This technology has medium potential to provide load shifting. Finn et. al. found peak time load reduction between 28-70% for residential dishwashers under a control algorithm to optimize cost, wind generation, and carbon emissions (Finn, 2013). Perez et. al. (2016) indicated that smart scheduling of washing machines and clothes dryers through model predictive control reduced peak electric demand by 5%. 

Residential refrigerator and freezer controls can provide load shifting for the electric grid through low operation mode, defrost cycle delay, and freezer precooling. Low operation mode works by shutting off the compressor and anti-sweat heaters in response to a grid signal or by the consumer to reduce peak demand charges. During a grid event, delaying the defrost cycle can reduce the refrigerator's load. Freezer precooling works by overcooling the freezer prior to a curtailment period or during a scheduled peak load reduction period and then modulating the airflow from the freezer to the refrigerator to maintain its setpoint. These technologies have low potential to provide load shifting. Farzamkia et. al. (2016) reported that refrigerator peak load can be shifted by about 11% by precooling strategies and by over 40% optimized algorithms.

Similar to residential refrigerators, commercial refrigeration equipment could benefit the grid using low operation mode, defrost cycle delay, and freezer precooling. However, in a commercial building such as a supermarket or refrigerated warehouse, these technologies can be staggered across multiple pieces to provide additional benefits. These technologies have high potential to offer grid services primarily through load shifting using scheduled precooling. Some load shedding is possible with corresponding load shifting to bring the equipment back to setpoint following the grid event. Energy efficiency gains are possible with smart controls, which can benefit owners through lower operating costs but with little benefit to the grid because the savings will most likely occur during off-peak times. Glavan et. al. (2018) indicated that a peak load reduction of 18% can be achieved for commercial refrigeration in supermarkets due to precooling.

# 4. Results and Discussion

The GEB technologies that are reported in the literature review were categorized according to several criteria with the goal of identifying those commercially available technologies that have high potential for providing grid services and are capable of being analyzed in current state-of-art building energy modeling (BEM) software and tools. These categories are largely qualitative, but may form the basis for quantitative analysis using BEM tools.  

## 4.1 Architectural

The architectural technologies considered in this report to be suitable for GEB applications are summarized in Table 1. Of the nine technologies, thermal storage, dynamic glazing, and automated attachments have the highest potential to provide grid services with market-ready products that can be evaluated in BPS software. 

**Table 1. Summary of Architectural Technologies**

| Technology | DOE Potential | Mature/Available | BPS Software | 
| :- | :-: | :-: | :-: |
| Tunable Thermal Conductivity Materials | High | &#9675; | &#9673; | 
| Thermally Anisotropic Systems | High | &#9675; | &#9675; | 
| Thermal Storage | High | &#9673; | &#9673; | 
| Moisture Storage and Extraction | Medium | &#9675; | &#9675; | 
| Variable Radiative Technologies | Medium | &#9675; | &#9673; | 
| Building-Integrated Photovoltaics | Low | &#9673; | &#9673; | 
| Dynamic Glazing | High | &#9673; | &#9673; | 
| Automated Attachments | High | &#9673; | &#9673; | 
| Photovoltaic Glazing | Medium | &#9673; | &#9673; | 

## 4.2 Electrical

The GEB electrical technologies outlined in this report are summarized in Table 2. Of the six technologies, continuous-operation electronics have the highest potential to provide grid services with market-ready products that can be evaluated in BPS software.

**Table 2. Summary of Electrical Technologies**

| Technology | DOE Potential | Mature/Available | BPS Software | 
| :- | :-: | :-: | :-: |
| Hybrid Daylight SSL Systems | Medium | &#9673; | &#9675; | 
| SSL Displays | Low | &#9673; | &#9675; | 
| Continuous-Operation Electronics | High | &#9673; | &#9673; | 
| Battery-Powered Electronics | Medium | &#9673; | &#9673; | 
| Electronic Displays | Low | &#9673; | &#9673; | 
| Modulating, Advanced Clothes Dryers (electric) | Medium | &#9673; | &#9673; | 

## 4.3 Mechanical

The mechanical technologies reviewed in this report are summarized in Table 3. Of the seven technologies, separate sensible and latent space conditioning and TES have the highest potential to provide grid services with market-ready products that can be evaluated in BEM software. 

**Table 3. Summary of Mechanical Technologies**

| Technology | DOE Potential | Mature/Available | BPS Software | 
| :- | :-: | :-: | :-: |
| Separate Sensible and Latent Space Conditioning | High | &#9673; | &#9673; | 
| Liquid Desiccant Thermal Energy Storage | High | &#9675; | &#9675; | 
| Hybrid Evaporative Precooling for AC | Low | &#9673; | &#9673; | 
| Dual-Fuel HVAC Systems | Low | &#9673; | &#9673; | 
| Thermal Energy Storage | High | &#9673; | &#9673; | 
| Modulating Capacity Vapor Compression | Medium | &#9673; | &#9673; | 
| Non-Vapor-Compression Materials and Systems | High | &#9675; | &#9675; | 

## 4.4 Plumbing

The plumbing technologies suitable for GEBs identified in this report are summarized in Table 4. Of the three technologies, building-scale CHP has the highest potential to provide grid services with market-ready products that can be evaluated in BEM software.

**Table 4. Summary of Plumbing Technologies**

| Technology | DOE Potential | Mature/Available | BPS Software | 
| :- | :-: | :-: | :-: |
| Dual-Fuel Water Heater | Low | &#9675; | &#9673; | 
| Modulating, Advanced Clothes Dryers (gas) | Medium | &#9673; | &#9673; | 
| Building-Scale CHP | High | &#9673; | &#9673; | 

## 4.5 Controls

GEB-specific control technologies summarized in this report are listed in Table 5. Of the seven technologies, advanced sensors and controls for lighting, smart thermostats, and water heaters with smart connected controls (electric and gas) have the highest potential to provide grid services with market-ready products that can be evaluated in BEM software.

**Table 5. Summary of Controls Technologies**

| Technology | DOE Potential | Mature/Available | BPS Software | 
| :- | :-: | :-: | :-: |
| Advanced Sensors and Controls (lighting) | High | &#9673; | &#9673; | 
| Smart Thermostats | High | &#9673; | &#9673; | 
| Advanced Controls for HVAC Equipment with Embedded Thermostats | Medium | &#9673; | &#9673; | 
| Water Heaters with Smart Connected Controls (electric and gas) | High | &#9673; | &#9673; | 
| Advanced Dishwasher/Clothes Washer Controls | Medium | &#9673; | &#9673; | 
| Advanced Residential Refrigerator/Freezer Controls | Medium | &#9673; | &#9673; | 
| Advanced Controls for Commercial Refrigeration | Medium | &#9675; | &#9673; | 

# 5. Conclusions

This report reviewed and summarized the current literature reported for GEB suitable technologies with the goal of categorizing the technologies according to several criteria. These criteria include demand-side management strategies, potential to provide grid services, technology maturity, and ability to perform analysis and evaluation in whole-building simulation software. The results identified a total of ten market-ready technologies with high potential to provide grid services that could be evaluated with BPS software.
