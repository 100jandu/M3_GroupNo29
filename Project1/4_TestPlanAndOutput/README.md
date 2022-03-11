## Test plan
# HLR

|TEST ID | High Level Requirement | Expected output | actual output|
|---|---|---|---|
| HLR1 |lock the door. | Shall lock the door of car | 
| HLR2 |unlock the door. | Shall unlock the door of car |
| HLR3 |activate/deactivate the alarm. | shall activate/deactivate the anti theft alarm |
| HLR4 |activate the approach light. | shall activate the approach light |

# LLR

| TEST ID | HLR ID |Low Level Requirement | Test cases passed/Failed |
|---|---|---|---|
| LLR1 |   |LEDs shall glow only after pressing Blue button. | 
| LLR2 |HLR1 |Pressing Blue button once shall make all LEDs glow at once. | 
| LLR3 |HLR2|Pressing Blue button twice shall stop all LEDs from glowing at once. | 
| LLR4 |HLR3 |Pressing Blue button thrice shall make all LEDs glow clockwise as shown below | 
|   |HLR3 | GREEN :arrow_right: ORANGE :arrow_right: RED :arrow_right: BLUE |  
| LLR5 |HLR4|Pressing Blue button four times shall make all LEDs glow anti-clockwise as shown below |
|   |HLR4 | GREEN :arrow_right: BLUE :arrow_right: RED :arrow_right: ORANGE 
