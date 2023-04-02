# Project Folder Naming Description
Purpose: This document describes the usage of the folder Structure for open-source projects. It will be explained which data is to put in which folder

## ChangeLog

Document control is not done by Github or other versioning solutions. Thus: 
Find here the Template version history and change documentation here  

>|Date   |Author | Vers.    |  Status  |Change Documentation    |  
>|-------|-------| :----------: | :-------: |:-----------|
>|02.04.23|tms|v01| draft |first creation, not in use yet|

## Open Issue list
Add here change requests, that needs to be improved in the new version

> |# |Date of CR|Change Request Description  |Status |Implementation Date| Implemented in Version|  
>|:-------|:-----|:-----|:----: | :----| :----|
>|1. |  02.04.2023|add open issue list |closed| 02.04.2023| v01|
>|2. | 02.04.2023 |add section with xy|open|tbd| tbd |

    

# Folder Structure


## 1_Documentaition_Structure_Process_Information
The intention of this folder to hold infomration about the project structure. Thus this document can be found there.
In addtion the following content could be found there:  

* Lizensing Information
* Definition of the used Toolchain
* Project Plan
* 

## 2_Literature_Research
Nobody does something for the first time. Thus in here are related projects, documents and further information about similar activities, projects and research.

## 3_MBSE_Requirements
MBSE stands for Model Based Systems Engineering. This folder has the follwing subfolders:  
In case Sysml tools like papyrus, enterprise architect or cameo modeller are used ths subfolder structure can be deleted.

For further information to the choosen structre refer to: https://sysml.org/tutorials/sysml-diagram-tutorial/

### 3.1_Use_Cases
Put use case diagramms here


### 3.2_Requirements

Define functional and non-functional requirements here

### 3.3_Systems_Architecture

Put the system context here
 
The systems architecture can also be further sub-devided into

#### 3.3.1 Structure_Diagramms
Includes:
* Block/Component Definition Diagram (bdd)
* Internal Block Diagram (ibd)
* Parametric Diagram (par)
* Package Diagram (pkg)  

#### 3.3.2 Behavior_Diagramms
Includes:  

* Activity Diagram (act)
* Sequence Diagram (sd)
* State Machine Diagram (stm)
* (Use Case Diagram (uc))

# Functional Decomposition Structure

The system architecture will be used to define a component diagramm. Those components represent system functions. Eg, MainControlUnit, PowerSupplyModule, etc
These module names are used to create a folder structure. 
Under this functional folder structure the engineering disziplins such as mechanics, electronics, electrics, software etc are mapped.
Thus a power-supply module will have a folder sub structure of mechanics, electronics, software etc.

## 4_Mechanical_Components
The information according the mechanical design will be stored here

### 4.1_MCad_Design
Put your mechanical CAD files here

### 4.2_MechComponents_Purchase
Put Information about non-self created mechanical parts and components here

### 4.3_Mech_BOM
The Bill of Material (BOM) for mechanical parts are stored here.

Note that the integration or assembly instructions of mechanical components will be covered in the integration folder

## 5_Electrical_Components

### 5.1_ECAD_Design
Put wiring and electrical desing here

### 5.2_PCB_Design
In case you need to create pcbs store the information in this folder

### 5.3_Elec_Modules_Purchase
Put Information about non-self created electrical or electronic parts and components here

### 5.4_PCB_BOM
Components and parts for the pcb creation

### 5.5_Elec_BOM
Components and part for the electrical infrastructure

### 5.6_Elec_Datasheets   
The collected and downloaded datasheets to be put here


## 6_Software  

### 6.1   

## Pictures&Rendering


## 7_Testing
All performed test with elements, components, modules and the overall system shall be documented here

### 7.1_Feasibility_Testing

Often different test have to perform to see how the function can be realized, these tests are documented in this folder.

## 7.2_FAT_Testing
The factory acceptance testing is been used to prove that the assembled system delivers the requested performance

## 8_Integration 
Here the system intgration will be documented. This can be   
*  Assembly Instructions
*  Start Up procedures

## 9_Purchasing_&_Ordering
The process of purchasing and ordering the parts shall be documented here

# Other Information- Where to put what

* Pictures : put under modules in a picture folder



