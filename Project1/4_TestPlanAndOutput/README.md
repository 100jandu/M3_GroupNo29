# Test plan
## High Level Test plan

|TEST ID | Input | High Level Requirement | Expected output | actual output|
|---|---|---|---|---|
| HLTP1 | Press Blue Switch Once | lock the door. | Shall lock the door of car | shall lock the door |
| HLTP2 | Press Blue switch Twice |unlock the door. | Shall unlock the door of car | shall unlock the door |
| HLTP3 | Press Blue Switch Thrice |activate/deactivate the alarm. | shall activate/deactivate the anti theft alarm | shall activate/deactivate the anti theft alarm |
| HLTP4 | Press Blue Switch Four Times | activate the approach light. | shall activate the approach light | shall activate the approach light |
| HLTP5 | Encryption | Wheter it is equal to 1 , 2 , 3 or 4 | if it is equal then implement the requirement | if it is equal then implement the requirement |


## Low Level Test Plan

| TEST ID |  | Low Level Requirement | Test cases passed/Failed |
|---|---|---|---|
| LLTP1 | To check if blue switch is pressed | LEDs shall glow only after pressing Blue button. | 
| LLTP2 | To check if blue switch is pressed once| Pressing Blue button once shall make all LEDs glow at once. | 
| LLTP3 | To check if blue switch is pressed twice | Pressing Blue button twice shall stop all LEDs from glowing at once. | 
| LLTP4 | To check if blue switch is pressed thrice | Pressing Blue button thrice shall make all LEDs glow clockwise as shown below | 
|   | GREEN :arrow_right: ORANGE :arrow_right: RED :arrow_right: BLUE |  
| LLTP5 | To check if blue button is pressed four times | Pressing Blue button four times shall make all LEDs glow anti-clockwise as shown below |
|   | GREEN :arrow_right: BLUE :arrow_right: RED :arrow_right: ORANGE 
