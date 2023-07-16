<header>

<h1 class="header">Progress Report</h1>

<!-- follow -->
<a class="github-button" href="https://github.com/munish8448" data-color-scheme="no-preference: dark_high_contrast; light: light; dark: dark;" data-size="large" data-show-count="true" aria-label="Follow @munish8448 on GitHub">Follow @munish8448</a>

<!-- star -->
<a class="github-button" href="https://github.com/munish8448/munish8448.github.io" data-color-scheme="no-preference: dark_high_contrast; light: light; dark: dark;" data-size="large" aria-label="Star munish8448/munish8448.github.io on GitHub">Star</a>

<a class="github-button" href="https://youtube.com/@real_ee" data-color-scheme="no-preference: dark_high_contrast; light: light; dark: dark;" data-size="large" >YouTube</a>

<p class="header">My Notes</p>
	
<!--   
<ul>
     
<li><a class="buttons github" href="https://github.com/munish8448/munish8448.github.io">View On GitHub</a></li> 
</ul>
-->
        

<!--        
<ul>
    <li><a class="buttons github" href="https://github.com/munish8448">GitHub Profile</a></li>
	  
<li><p align="left">
<a href="https://www.youtube.com/c/@real_ee" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="@real_ee" height="30" width="40" /></a>
</p></li>

<li><p><a href="https://www.buymeacoffee.com/voidPlc"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="voidPlc" /></a></p><br><br></li>
    
</ul>
-->



<script async defer src="https://buttons.github.io/buttons.js"></script>



 
</header>





# O&M Department

## About
- Electrical systems need regular maintenance to ensure continued compliance with the codes and publications referred to in this document. Such maintenance will prevent system and equipment failures and ensure maximum safety and efficiency in the utilization of the facilities.

## System Overview

### SLD

- A single-line diagram (also known as an SLD or one-line diagram) is a simplified representation of an electrical system. Symbols and lines are used to represent the nodes and connections in the system, and electrical characteristics may be included as well. 

![SLD](https://en.wikipedia.org/wiki/File:One-line_diagram.svg)

## Equipment
- Various Equipments like **transformers, supply cables, RMU, Feeder pillar, ACB** etc are use throughout the electrical power distribution system in order to provide electricity to the consumers in an effient and reliable manner.

### Components of Distribution System

- **Distribution Transformer** - A distribution transformer is used to provide safe level of voltage to consumers as the transmission line voltages are very high in order to keep the transmission losses minimum. 

- These are step down transfomer that takes 11KV supply as primary and provides 220V (L-N) or 430V (L-L) at secondary. 

- Parts of DTR


    - **Main Tank** - Transformer tank also named transformer tank body. It is used to hold, protect, cool the winding and core in one Electrical distributor transformer. The tank body provides isolation of oil and the core from the outside environment. 
    
    ![main tank]()
    
    - **Conservator** - The Conservator Tank of a transformer is defined simply as a cylindrical tank mounted on the roof of the transformer main tank. It is used to provide enough space for the oil in the transformer to spread after heating.
    
    ![conservator]()
    
    - **Breather** - The breather is used in the transformer to filter out the moisture from the air. Breather consists of silica gel which absorbs moisture from the air. Conservator tank present at the top of the transformer which allows adequate space for expansion of oil.
    
    ![breather]()
    
    - **Magnetic Oil Gauge** - The MOG (Magnetic Oil Gauge) is a device by which we can supervise the level of liquid/oil inside the tank or conservator of power transformer and also gives us an alert low oil level indication with making mercury switch. 
    
    ![mog]()
    
    - **Bushing** - In electric power, a bushing is a hollow electrical insulator that allows an electrical conductor to pass safely through a conducting barrier such as the case of a transformer or circuit breaker without making electrical contact with it.
    
    ![bushing]()
    
    - **Radiator** - The radiator is an essential type of equipment of oil transformers used to transfer the thermal energy from one medium to another for the purpose of cooling. The radiators are linked to the transformer through the pipeline at the upper and lower side of the transformer
    
    ![radiator]()
    

- **RMU**
- **ACB**
- **Cables / Leads**

    - **HT Cable**
    - **LT Cable**
    - **Single Core Leads**
    - **HTAB Cable**
    - **LTAB Cable**
	- **Cable Connector**

### Transformer Load Calculation

- Max Current under normal condition
- Fault Current
- Load Balancing

## What is Load Balancing?
For a three-phase transformer, each phase should be considered as a single-phase transformer. When distributing single-phase loads between the three phases, each of the three windings should be evenly loaded with single phase loads.

Failure to balance loads can cause secondary voltage imbalances, additional transformer losses and high neutral currents. Significantly unbalanced loads can reduce the life of a transformer.

Since we can't control the load connected to a distibution transformer we try to supply electricity to the consumer such that each phase as nearly equal load. 


## How it's done?
If we take a closer look at the system we can see that the load or the service lines are not connected to the transformer directly we have an `LT-Main` connected to transformer's secondary. The `LT-Main` is then used to energies the `LT-Busbar` or `Sub-LT ACB` which are connected to the underground cables that are used to energize the `LTAB` mounted on poles.

So inorder to balance the load we first take the load connected on transformer using `clampon Ammerter` and load on all the LT-Main and sub LT-ACB.

After this we can try to shift the load by interchanging the LT-AB leads in order to get to a point where we have somewhat similar load on each phase.

*Note - Interchanging the leads of LT-Main won't change anything.*

If we are unable to balnace load by interchanging the leads of LT-ACB we try to balance load from the distribution box by transfering individual loads from one phase to another.

No changes is made in system during the process we first try to balance loads on paper by performing basic calculation if and only if we get the desired result the connections are changed according to the results obtained from the calculations.

A difference of under or equal to 50A between two phases can be accepted.

## Transformer Cooling Methods

## Transformer Preventive Maintenance

#### Cable Termination
#### Partial Discharge Test
#### Tool Inspection
#### LT Cable Fault Location
#### HT Cable Fault Location
#### Substation Inspection
#### Single Wire Earth Return System
#### Meter Installation Guidelines
---
# EHV Protection South - 2, 15-6-23

## About EHV Protection

![CRP Panel EHV Protection South 2 AIIMS]() 

![33KV GIS EHV Protection South 2 AIIMS ]()

- High voltage power systems are extremely complex since it is essential to keep certain electrical variables under certain ranges that cannot vary. Voltage, frequency and level of harmonics are some of the constantly supervised electrical parameters. The electric current and the active and reactive power flows, as well as the power factor, are other determining parameters to ensure enough quality and efficiency to the transported electrical energy. In addition, to avoid irreversible damage to electrical grids, high voltage systems have protection relays, whose purpose is to protect these grids against electrical faults, lightning strikes, incorrect operations, etc.
- For these reasons, the design and management of an electric power system is a very complex task due to the dynamics of its behavior and the constant power fluctuations that occur. Securing the stability of the electrical system is essential. For that purpose, the main elements of the system are analyzed, among them: transmission lines, generators and electrical power transformers.

## Various Tests performed on equipment

## Test Kits

| S.No. | Kit | Make |
|---|---|---|
| 1 | TanDelta | Megger |
| 2 | CT Analyzer | Omicron |
| 3 | WRM | Megger |
| 4 | TTR | Megger |

## Significance of Tests

### TanDelta Test

- The main purpose of the tan delta test is to make sure of maintaining a secure and reliable functioning of the transformer. With the calculation of dissipation factor and capacitance values, it provides the result of insulation behavior of bushings and in windings too.

### WRM

- Winding Resistance Measurement

- The purpose of the test is to check for gross differences between the windings and for opens in the connections.
- Winding resistance measurements detect various faults in motors, generators, and transformers: shorted & open turns, loose connections, and broken conductors & resistive connections problems. These issues may be the cause of wear or other defects in a wound rotor motor.
### Secondary Injection Test

- The purpose of secondary injection testing is to verify that the correct operation of the protection scheme from the relay input terminals onwards is functioning correctly with the settings specified.
### TTR

- Transformer Turn Ratio Test
- Transformer Turns Ratio (TTR) is one of the most common test used to assess the condition of the transformer's windings and core. It is performed as a part of acceptance and maintenance test procedure to determine any problems due to poor design, assembly, handling, overloading, fault conditions or poor maintenance.
-
### CT Analyzer

#### How CT Analyzer works
- Injects low test signals into secondary side of the CT  
 - Determines the CT‘s equivalent circuit parameters  
- Identifies all relevant CT performance parameters  
- Displays all relevant parameters of the CT and its accuracy at different currents and burdens  
 - Evaluates the CT according to the selected standard  
 - Determines unknown CT nameplate parameters  

## Relays
	
### Types

### Electromechanical
- An electromechanical relay is a type of relay which function using a magnetic field produced by an electromagnetic coil when a control signal is applied to it. It is called as electromechanical since it has moving contacts in the output circuit which are operated by applying an electrical signal.
#### Classification of EMRs based on their applications
- General Purpose Relays – Such as miniature relays, latching relays, timer relays, contactors, machine tool relays, hybrid relays, smart relays, signal relays, automobile relays and PCB relays etc.

 - Protection Relays – Such as thermal overload relays, earth fault relays, under or over voltage relays, under or over current relays, buchholz relay, differential relays, distance protection relays, sequence protection relays, electronic relays etc.  
#### Classification of EMRs based on contact configurations
- Single-Pole Single-Throw (SPST)
- Single-Pole Double-Throw (SPDT)
- Double-Pole single-Throw (DPST)
- Double-Pole Double-Throw (DPDT)
-
#### Classification of EMRs based on their construction & operation
- Electromagnetic Attraction Type Relay – Such as attraction armature type EMR, solenoid type EMR, balanced beam type EMR.
- Electromagnetic Induction Type Relay **– Such as shaded pole type EMR, watt-hour meter type EMR, induction cup type EMR.
-
### Numerical

### List of Relays

| S.No | Relay | Make | Use |
|---|---|---|---|
| 1. | SPAJ 140C | ABB | O/C, E/F, DR & NDR |
| 1. | SPAD 346 C3 | ABB | Diff., ITT fault, E/F |
| 1. | REU 610 | ABB | |
| 1. | REU 615 | ABB | O/V, U/V |
| 1. | REL 670 | ABB | Distance |
| 1. | REF 615 | ABB | O/C, E/F, DR & NDR |
| 1. | REL  511 | ABB | Distance |
| 1. | RED 670 | ABB | Line Diff. |
| 1. | RED 615 | ABB | |
| 1. | RET 615 | ABB | |
| 1. | REF 620 | ABB | O/C, E/F, DR & NDR |
| 1. | REU 615 | ABB | Line Diff. |
| 1. | P442 | GE MiCOM | Distance |
| 1. | P543 | GE MiCOM | Line Diff.l |
| 1. | P642 | ALSTOM | |
| 1. | P127 | Schneider | O/C, E/F, DR & NDR |
| 1. | P141 | Schneider MiCOM | O/C, E/F, DR & NDR |
| 1. | P142 | Schneider MiCOM | O/C, E/F, DR & NDR |
| 1. | P143 | Schneider MiCOM | O/C, E/F, DR & NDR |
| 1. | P120 | Schneider MiCOM | |
| 1. | P94V | GE Agile | |
| 1. | Vamp57 | Schneider | |
| 1. | 7SA6 | Siemens SIPROTEC | Distance |
| 1. | 7SJ6 | Siemens SIPROTEC | |
| 1. | 7SJ8 | Siemens SIPROTEC | O/V, U/V |
| 1. | 7RW6 | Siemens SIPROTEC | O/V, U/V |
| 1. | ADR 233 B | Ashida | |
| 1. | ADR 245 B | Ashida | |

**Abbreviations**
- O/C ---> Over Current
- O/V ---> Over Voltage
- U/V ---> Under Voltage
- E/F ---> Earth Fault
- Diff. ---> Differential
- DR ---> Directional
- NDR ---> Non-Directional

- ---

# What should we know

## Connections
- Every relay manufacturer provides the connection/ wiring diagram for all relay. This is always provided by the manufacturer with the relay when delivered to the user. In case it's lost or went missing, they are readily available on the manufacturers website.
-
  <i>Example : Siemens 7UT612</i>
	- ![image.png](../assets/image_1689242575518_0.png)
	-
    - Every relay will have varying number of similar input output like:
        
        Power Supply :
		- Can be AC/DC voltage level is also provided either in wiring diagram or on relay itself or both.
		- Relay may or may not have an option to be powered by an auxiliary supply.
		-
		  <i>Example : </i>
			- Relay used in 11KV protection system. These are powered by the current flowing through the CT and hence contribute to the relay burden.
	- Current Transformer (CT) : These are used to measure current
	- Voltage Transformer (PT) :
	- Binary / Digital Input (BI) :
		- These are used to get any digital signal either from another relay or SCADA.
	- Binary / Digital Output (BO) :
		- Normally Open : These are in OFF state initially but turn ON when a certain condition is met ( condition depends on the program logic )
		- Normally Close : These are in ON state initially but turn OFF when a certain condition is met ( condition depends on the program logic )
		- These can be of SPDT type (NO & NC pair) : These uses three terminal pair where one is common and one of remaining two is normally open and other is normally close. When condition is true the state of NO and NC terminal changes.
	-
#### Settings / Configuration
-
-
#### Output routing
- Enables the end user to program the relay so that the digital output (BO) can be used to trigger some indication or function in case some condition is true.
-
	  <i>Example :</i>
		- Block, Indication, to send data to SCADA, Trip the breaker
## Working of Specific Relays

	-
## Overview of System

	-
## Switchgear / Switch yard / CRP / GIS

	-
-
