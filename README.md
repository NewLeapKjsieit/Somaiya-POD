# Somaiya-POD
Official deployer of K. J. Somaiya Institute of Engineering and Information Technology's BeliefSat1
## Readme 

Somaiya *Pico-Satellite Orbital Deployer* (SomaiyaPod) is a Pocketqube Standard Deployer that is indigenously made by the undergraduate Students of **K J Somaiya of Engineering and Information Technology**. The  SomaiyaPod is a subpart of the team's proposal under the [PS4-Orbital platform program of ISRO](https://www.isro.gov.in/update/15-jun-2019/announcement-of-opportunity-ao-orbital-platform), wherein, the team aims to demonstrate the deployment of indigenously developed technologies for PocketQube standard nano-satellites. As a part of this demonstration, BeliefSat will be launched out of SomaiyaPod. The SomaiyaPod is based on the PocketQube Standards which was introduced by Alba Orbital, TU Delft, and GAUSS (Group of Astrodynamics for the Use of Space Systems). This ensures that the standard design can accommodate the various types of PocketQube standard Satellites.

### So what will Somaiya-POD do in Space and what result will it give?

- To contain the satellite and protect it during the launch stage.
- Then the main objective of the deployer is to deploy the PocketQube standard satellite i.e [BeliefSat-1](https://github.com/NewLeapKjsieit/BeliefSat)
- It will also communicate with the PS4-OP whether the satellite is deployed or not.

### Specifications:
<image src="images/IMG-20210409-WA0012.jpg" width=400 height=400>
</image>

| External dimensions 	| 200mm x 145mm x 195mm 	|
|:--:	|:--:	|
| Estimated mass 	| 1000g 	|
| Material used 	| Aluminium 6061 	|
| Manufacturing methods used 	| -Laser Cutting for Outer Covering -Simple Milling of L-angles to make internal rails  	|
| Pin puller 	| DucubeD's nD3PP 	|
| Pusher Construction 	| FR4 plate with aluminium L-angles to hold the spring  	|
| Constant Force Spring  	| 9N Force 	|
| Envelope 	| 10mm 	|
| Design extendable upto 	| 6P variant 	|

### Structure:

1. Outer Structure-

The outer Structure of SomaiyaPod is made up of Aluminium Sheets. The sheets are laser cut to acquire maximum accuracy and precise fitting.

<image src="images/1617963857032.jpg" width=400 height=400>
</image>

2. Inner Structure-

The internal Structure of Somaiya POD comprises aluminium LBands to ensure maximum support given to the outer Structure of the Deployer to withstand harsh conditions of space and  to provide stability during launch. 

image

### Mechanical interfacing with PS4-OP

SomaiyaPod Deployer will be bolted on the 4th stage of PSLV 4 orbital Platform by 4x M12 Titanium bolts. The following Image captures the mechanical footprint of the same:-

<image src="images/IMG-20210409-WA0024.jpg" width=400 height=400>
</image>


### Electrical Specifications:

- SomaiyaPod Deployer uses the Pin Puller provided by Dcubed Space to   operate the functioning of the Front Door of the deployer and endstop   switch to detect the deployment of the satellite.

- PS4 to PinPuller: the signal will be given to PinPuller by PS4 to open the doors of the Deployer.

- Door to End Stop Switch: Once the Door of the deployer has been opened, the end stop switch will be able to indicate whether the satellite has been launched through the deployer or not.

image

### Mechnism of Deployment:
When the PS4-OP will reach the required altitude, it will give a deployment signal to Pinpuller to retract  its pin, resulting in the opening of the Somaiya Pod . Then the Beliefsat will be launched with the help of Constant Spring Force.  


