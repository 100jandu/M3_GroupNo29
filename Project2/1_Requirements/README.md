# BiCom System
## Abstract
 
* The term BiCom system, is the extention of the unidirectional RKE to bidirectional RKE system. 
***
## Features
*	keyfob -> car (like a unidirectional RKE system) 
*	car -> keyfob (car status information for displaying on the keyfob by LED or display) 
***
## SWOT Analysis
| Strengths | Weakness | Opportunity | Threat |
|-----------|----------|-------------|--------|
| It does not Require physical key to lock/unlock the car | Distance from the car to operate the system is limited |  BiCom can be widely used in cars and other transportation systems instead of RKE |If the encryption algorithm is tampered, the system shall not work properly. | 
***
## # 4Ws and 1H

## What
* To perform various functions like lock and unlock the door activate/deactivate the alarm and enable the approach light.

## Where
* This System shall be installed in Cars.

## When
* System shall remain active when the user is not near the car. 

## Why
* BiCom provides better security than the RKE system.

## How
* By Pressing blue button in prescribed manner.

*** 
## High-Level Requirements (HLR)

| ID | High Level Requirement |
|---|---|
| HLR1 |Show Window Status  |
| HLR2 |Shall Print alarm status |
| HLR3 |Shall Print car battery status. |
| HLR4 |Shall Print Door status . |
| HLR5 |The communication shall be Bi-directional. |

***
## Low-Level Requirements (LLR)

| ID | HLR ID |Low Level Requirement |
|---|---|---|
| LLR1 |  - |LEDs shall glow only after pressing Blue button. |
| LLR2 |HLR1 |Pressing Blue button once shall make all LEDs glow at once. | 
| LLR3 |HLR2|Pressing Blue button twice shall stop all LEDs from glowing at once. | 
| LLR4 |HLR3 |Pressing Blue button thrice shall make all LEDs glow clockwise as shown below |
| ▶️  | ▶️ | GREEN :arrow_right: ORANGE :arrow_right: RED :arrow_right: BLUE |  
| LLR5 |HLR4|Pressing Blue button four times shall make all LEDs glow anti-clockwise as shown below |
|  ▶️ | ▶️  | GREEN :arrow_right: BLUE :arrow_right: RED :arrow_right: ORANGE | 
| LLR6 |HLR5| Car shall send back the info to remote by LED/display |

