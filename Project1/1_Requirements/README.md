
#  REMOTE KEYLESS ENTRY(RKE)

# Abstract
 
 *  The term remote keyless entry (RKE), also called remote keyless system or remote central locking, refers to a lock that uses an electronic remote control as a key which is activated by a handheld device or automatically by proximity.  An RKE performs the functions of a standard car key without physical contact. When within a few yards of the car, pressing a button on the remote can lock or unlock the doors, and may perform other functions. 
 
### Features of the RKE system

1.  By pressing button once, the system shall lock the door.
2.  By pressing button twice, the system shall unlock the door.
3.  By pressing button thrice, the system shall enable/disable alarm.
4.  By pressing button four times, the system shall enable the approach light.


# 4Ws and 1H

## What
* To perform various functions like lock and unlock the door activate/deactivate the alarm and enable the approach light.
---
## Where
* This System shall be installed in Cars.
---
## When
* System shall remain active when the user is not near the car. 
---
## Why
* RKE provides better security than the traditional key-lock system.
---
## How
* By Pressing blue button in prescribed manner.
--- 

# SWOT Analysis

| Strengths | Weakness | Opportunity | Threat |
|-----------|----------|-------------|--------|
| It does not Require physical key to lock/unlock the car | Distance from the car to operate the system is limited |  RKE can be widely used in cars and other transportation systems|If the encryption algorithm is tampered, the system shall not work properly. | 

---

 
 
# High-Level Requirements (HLR)

| ID | High Level Requirement |
|---|---|
| HLR1 |Shall lock the door. |
| HLR2 |Shall unlock the door. |
| HLR3 |Shall activate/deactivate the alarm. |
| HLR4 |Shall activate the approach light. |


# Low-Level Requirements (LLR)

| ID | HLR ID |Low Level Requirement |
|---|---|---|
| LLR1 |  - |LEDs shall glow only after pressing Blue button. |
| LLR2 |HLR1 |Pressing Blue button once shall make all LEDs glow at once. | 
| LLR3 |HLR2|Pressing Blue button twice shall stop all LEDs from glowing at once. | 
| LLR4 |HLR3 |Pressing Blue button thrice shall make all LEDs glow clockwise as shown below |
| ▶️  | ▶️ | GREEN :arrow_right: ORANGE :arrow_right: RED :arrow_right: BLUE |  
| LLR5 |HLR4|Pressing Blue button four times shall make all LEDs glow anti-clockwise as shown below |
|  ▶️ | ▶️  | GREEN :arrow_right: BLUE :arrow_right: RED :arrow_right: ORANGE | 


