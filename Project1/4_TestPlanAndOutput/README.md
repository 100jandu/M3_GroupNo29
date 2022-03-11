# Test plan
## High Level Test plan

|TEST ID | High Level Requirement | Expected output | actual output|
|---|---|---|---|
| HLTP1 |lock the door. | Shall lock the door of car | 
| HLTP2 |unlock the door. | Shall unlock the door of car |
| HLTP3 |activate/deactivate the alarm. | shall activate/deactivate the anti theft alarm |
| HLTP4 |activate the approach light. | shall activate the approach light |

## Low Level Test Plan

| TEST ID |Low Level Requirement | Test cases passed/Failed |
|---|---|---|
| LLTP1 |LEDs shall glow only after pressing Blue button. | 
| LLTP2 |Pressing Blue button once shall make all LEDs glow at once. | 
| LLTP3 |Pressing Blue button twice shall stop all LEDs from glowing at once. | 
| LLTP4 |Pressing Blue button thrice shall make all LEDs glow clockwise as shown below | 
|   | GREEN :arrow_right: ORANGE :arrow_right: RED :arrow_right: BLUE |  
| LLTP5 |Pressing Blue button four times shall make all LEDs glow anti-clockwise as shown below |
|   | GREEN :arrow_right: BLUE :arrow_right: RED :arrow_right: ORANGE 
