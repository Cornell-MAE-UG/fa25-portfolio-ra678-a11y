---
layout: project
title: Analysis of a Frigidaire FFSS2315TS Refrigerator
description: Thermodynamics
technologies: Vapor Compression Refrigeration Cycle 
image: assets/images/frigdaire-cover-picture.jpg
---

Device: Frigidaire FFSS2315TS Side-by-Side Refrigerator
Refrigerant: R-134a

## Device Specifications
Model: Frigidaire FFSS2315TS

Type: Side-by-Side Vapor-Compression Refrigerator

Capacity: 22.0 cubic feet (14.1 fresh food, 7.9 freezer)

Refrigerant: R-134a (140g charge typical)

Annual Energy Consumption: 672 kWh/year

Electrical: 120V, 8.5A, 1.02 kW connected load


## Explaination of How a Fridge Works
The device I have chosen to work with is the refrigerator in my home, the Frigidaire FFSS2315TS Side-by-Side Refrigerator. The refrigerator moves heat from inside the refrigerator to outside and uses a vapor-compression refrigeration cycle which has the refrigerant R-134a that changes between liquid and vapor states at different temperatures when the pressure is changed. The refrigeration cycle has four main components working together in a closed system.

This cycle begins at the evaporator, which is hidden inside the back of your refrigerator. These evaporator coils

<img class="center-img" src="{{ '/assets/images/frigdaire-evaporator.jpg' | relative_url }}" alt="Frigidaire evaporator" />

work at around -10 degrees Fahrenheit or -23 degrees Celsius. When the cold refrigerant enters the evaporator as a 2 phase mixture of liquid and vapor at low pressure, it is colder than the air inside the fridge. Air circulates through the evaporator coils and the refrigerant absorbs heat from the warmer air. This heat absorption causes the remaining liquid refrigerant to evaporate, turning into a low pressure and temperature vapor. 

After the refrigerant leaves the evaporator as a cold vapor, it travels to the compressor which requires electrical power and is usually at the bottom of your refrigerator.

<img class="center-img" src="{{ 'assets/images/frigdaire-compressor.jpg' | relative_url }}" alt="Frigidaire compressor" />

The job of the compressor is to compress the refrigerant vapor, which does three things. First, it increases the refrigerant’s pressure from about 15 psi to about 124 psi. Second, it increases the temperature from -10 degrees Fahrenheit to about 160 degrees Fahrenheit. Third, it requires electrical energy to perform work on the refrigerator. By compressing the refrigerant, the boiling point of  R-134a is raised. By doing this it allows the refrigerant to reject heat to the kitchen.

The high pressure vapor leaves the compressor to then flow into the condenser coils located in the back of your refrigerator.

<img class="center-img" src="{{ 'assets/images/frigdaire-condenser.jpg' | relative_url }}" alt="Frigidaire condenser" />

Inside these condenser coils, the hot refrigerator vapor rejects heat to the surrounding kitchen. As the refrigerant loses this energy, it condenses the refrigerant back into  a liquid state. By the time it exits the condenser, it has transformed from a hot vapor into a high pressure liquid by rejecting heat into the kitchen. 

After leaving the condenser as a high pressure liquid, the refrigerant moves to the expansion valve hidden inside the refrigerator where the high pressure liquid is forced through the tube reducing pressure from 124 psi to around 15 psi. 

<img class="center-img" src="{{ 'assets/images/frigdaire-expansion.jpg' | relative_url }}" alt="Frigidaire expansion" />

This quick drop in pressure causes some of the liquid to become vapor creating a 2-phase mixture of liquid and vapor. No work is rejected or added to the cycle during this process and the refrigerant maintains the same enthalpy before and after this process while its pressure, temperature, and state change. 

## System Diagrams

<div class="side-by-side">
  <img class="side-img" src="{{ '/assets/images/frigdaire-refrigeration-cycle.jpg' | relative_url }}" alt="Frigidaire refrigeration cycle" />
  <img class="side-img" src="{{ '/assets/images/frigdaire-ts-diagram.jpg' | relative_url }}" alt="Frigidaire ts diagram" />
</div>

At state 1, the refrigerant exits the evaporator as a saturated vapor. At this point, it is a low pressure (around 15 psi) and a low temperature (around -10 degrees Fahrenheit). The refrigerant has an enthalpy of 386.6 kJ/kg and absorbs around 145 kJ/kg of heat from the inside of your refrigerator while evaporating. This cold vapor flows through the coils towards the compressor for the compression stage to start. Going from state 1 to state 2, the cold vapor enters the compressor, where a motor squeezes the refrigerant. This compression requires around 150- watts of electrical power and does around 59.6 kJ/kg work on the refrigerant. During this state the pressure increases from 15 psi to 124 psi while also raising the temperature from -10 degree Fahrenheit to 160 degree Fahrenheit. The compressor operates at around 70% isentropic efficiency, energy is lost to friction and heat. The refrigerant exists as a superheated vapor with an enthalpy of around 446.4 kJ/kg. This high temperature and high pressure vapor now flows to the condenser. Entering the condenser coils it rejects heat to the environment (kitchen). The vapor cools from 160 degrees Fahrenheit to around 90 degrees Fahrenheit while remaining as a gas while it begins condensing at a constant temperature as heat is removed. The phase changes from vapor to liquid and releases heat transforming the refrigerant into a saturated liquid by the condenser exit. At State 3, the refrigerant is a liquid at 90 degrees Fahrenheit and 124 psi with an enthalpy of 241.8 kJ/kg. This high pressure liquid now passes through the expansion valve that makes the pressure drop from 124 psi to 15 psi. No work or heat transfer is done during this process so enthalpy remains constant at 241.8 kJ/kg. The pressure lowers to 15 psi and the saturation temperature is around -10 degrees Fahrenheit. The refrigerant exists as a 2 phase mixture. This mixture then enters the evaporator and heat transfers from the air into the cold refrigerant. This heat absorption evaporates the remaining liquid at constant temperature (-10 degrees Fahrenheit) and pressure (15 psi). When exiting the liquid transforms into a saturated vapor where the refrigerant is now back at State 1 with an enthalpy of 386.8 kJ/kg. 

## Property Table

| State | Location | Pressure | Temp. | Enthalpy (kJ/kg) | Entropy (kJ/kg·K) | Quality | Phase |
|---:|---|---:|---|---:|---:|---:|---|
| 1 | Evaporator Exit | 103.4 kPa (15 psi) | -23.3 ℃<br>(-10 ℉) | 386.6 | 1.7395 | – | Saturated vapor |
| 2s | Compressor exit (isentropic) | 855 kPa (124 psi) | 55.0 ℃<br>(131.0 ℉) | 428.5 | 1.7395 | – | Superheated vapor |
| 2a | Compressor exit (actual) | 855 kPa (124 psi) | 71.1 ℃<br>(160.0 ℉) | 446.5 | 1.7842 | – | Superheated vapor |
| 3 | Condenser exit | 855 kPa (124 psi) | 32.2 ℃<br>(90 ℉) | 241.8 | 1.1456 | – | Saturated liquid |
| 4 | Expansion valve exit | 103.4 kPa (15 psi) | -23.3 ℃<br>(-10 ℉) | 241.8 | 1.1902 | X = 0.320 | Two-phase mixture |

## Energy Transfer Calculations

Component | Energy Transfer | Value  
Evaporator: | q_evap = h1 - h4 | Value: 144.8 kJ/kg
Compressor:|  W_comp = h2 - h1 | Value: 59.9 kJ/kg
Condenser: | q_cond = h2 - h3 | Value: 204.7 kJ/kg
Expansion Valve: |  W = 0, q = 0  | Value: h4 = h3

q_evap + W_comp = q_cond
114.8 + 59.9 = 204.7 kJ/kg

## Performance Metrics

Metric | Formula | Calculation | Result
COP | q_evap/W_comp | 144.8/59.9 | 2.42
Carnot COP (Ideal) | T_cold/(T_hot - T_Cold)| 249.8/(305.4 - 249.8) | 4.50
Isentropic Efficiency | (h2s - h1)/(h2a - h1) | (428.5 - 386.6) / (446.5 - 386.6) |70.0%

Refrigerant Mass Flow Rate:

ṁ = Ẇ_comp / w_comp

ṁ = 0.153 kW / 59.9 kJ/kg

ṁ = 0.002563 kg/s = 2.563 g/s

Cooling Power:

Q̇_evap = ṁ × q_evap

Q̇_evap = 0.002563 kg/s × 144.8 kJ/kg
 
Q̇_evap = 371.1 W

## Entropy Analysis 

Evaportor (State 4 to State 1)
s1 - s4 = 1.7395 - 1.1902 = 0.5493 kJ/(kg*K)

Compressor (State 1 to State 2)
s2 - s1 = 1.7842 - 1.7395 = 0.0447 kJ/(kg*K)

Condenser (State 2 to State 3)
s3 - s2 = 1.1456 - 1.7842 = -0.6386 kJ/(kg*K)

Expansion Valve (State 3 to State 4)
s4 - s3 = 1.1902 - 1.1456 = 0.0446 kJ/(kg*K)

The total entropy change in this adds up to zero as this is a closed thermodynamic cycle.

## Conclusion
The analysis of this Frigidaire refrigerator shows how a vapor-compression refrigeration cycle operates in the real world, connecting what we have learned in class to a real life application. Through this analysis I have applied the First Law of Thermodynamics on energy conservation, and the Second Law of Thermodynamics on entropy generation. By taking a specific device like a refrigerator, I have been able to verify the thermodynamic analysis by using the R-134a property tables to find enthalpy and entropy, and use the First and Second Law of Thermodynamics to quantify the performance of the refrigeration.


