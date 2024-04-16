# Implement wind sensing with the antennal aristae for wind-guided odor navigation

## TODO 
- Read papers
## Questions to TA
- 

## Meeting 16.04
Project objectives 
- Implement wind
- Be sensed by antennae (we dont really know how it biologically works)

Objectifs next week
- Add wind (start laminar (only one direction, try to follow it))
- Put sensors on aristeas (at the basis sensing how the antenna is moving)
- External forces (MuJoCo) put on arista to define stiffness and damping of aristae (from external data)
  
## Define our problem: 
- Scene: (wind) odor plume, odor source (ON/OFF), one fly, idée: plusieurs sources d'odeur et un vent
- Sensing: antenna aristae movement, 
- Motor control: like odor-based modulation but variation of odor due to wind


## What already exists
- Wind (Mujoco, see doc wind:real())
- Odor plume (Sibo)

## Old Split work
(1) Person establishes wind-guided odor navigation environment / scenario **Emilie**

(2) Person implements aristae movements **ALINE**

(3) Person implements motor control of plume navigation with processed aristae inputs **Killian**
