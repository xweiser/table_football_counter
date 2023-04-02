# table_football_counter
A small device to count the goals when playing foosball, table football or "kicker"


# Discussions and exchange is organized in a discord channel
all contributors should join here: https://discord.gg/77jfMQfU


# Project Information

## Project motivation and purpose 
	1) Have fun creating an open-source project 
	2) Enable focussing on the table football game, rather than forget counting a goal
	

## USE Cases and User Stories

### User stories
	1) 4 friends are playing table football and every goal needs to be counted.
	2) The counting in the game sometimes is forgotten and none of the 2, 3, or 4 players adds a goal to the manual counter
	3) ....

### Use cases
	1) Actor: Player resets the goal status
  2) Actor: System counts each goal 
	3) Actor: Player switches the system on / off
	4) 
	
### Unique Selling points
	1) TBD 
  
## Customer Requirements
### The System shall
	1) Show in alphanummeric numbers the amount of goals achieved by each team
	2) Play a sound once one team has achieved the required goals (5,6 or 10)
	3) Indicate on the display that the maximum required goals ((5,6 or 10) have been achieved.
  4) ndicate with an RBG light that the maximum required goals ((5,6 or 10) have been achieved.
	5) tbd
	
	

Nice to have or Future Requirement : Add a OBDII Adapter to the car and read motor values, speed, etc

## Non Functional Requirements
	1) The system shall indicate if connected to the cloud services
	2) The system shall enable debugging (Add display?)
	3) Test the power-loss function
	4) Test the alarming of the system
	5) Create an error and event Log- that can be analyzed later on
	6) The pcb board must have electrical contact pads to enable connecting measruement devices such as an oszilloscope for error detection (dont know the right wording)
	7) The board reset function needs to be accessible to the user (to reboot the board)
	8) In observation mode (no person in the campingcar) the display shall be deactived to save battery power (in case of main power loss) the system shall communicate to the cloud as long as possible 
	
	
	



## MVP - Minimal viable Product
In general a MVP describes a Solution which offers a minimal acceptable value for the user. In this case the Function: Alarm the user when the power is cut and the interior temperature falls below 5 degree, is defined as MVP. Thus the User can takes action and inform the Parkinglot owner to repair the power supply.
The satellite boxes can be added in a later stage.

### Requirements for the MVP
1) Measure the interior temperature & humidity
2) Measure the outside temperature
3) Alarm when power loss and temperature below 5*C using IFTT
