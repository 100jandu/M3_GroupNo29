# Test plan
## High Level Test plan

|TEST ID | Description | Input | Expected output | actual output|
|---|---|---|---|---|
| HLTP1 | Print Window status | Press Blue Switch Once | Shall Print Window status | shall Print Window status |
| HLTP2 | print alarm status | Press Blue switch Twice | Shall print alarm status  | shall print alarm status  |
| HLTP3 |	Print car battery info  | Press Blue Switch Thrice |Shall Print car battery info | shall activate/deactivate the anti theft alarm |
| HLTP4 | Print Door status  | Press Blue Switch Four Times | Shall Print Door status  | shall Print Door status  |
| HLTP5 | Encryption | Wheter it is equal to 1 , 2 , 3 or 4 | if it is equal then implement the requirement | if it is equal then implement the requirement |


## Low Level Test Plan

| TEST ID | Description | Low Level Requirement | Test cases passed/Failed |
|---|---|---|---|
| LLTP1 | To check if blue switch is pressed | LEDs shall glow only after pressing Blue button. | ✅
| LLTP2 | To check if blue switch is pressed once| Pressing Blue button once shall make all LEDs glow at once. | ✅
| LLTP3 | To check if blue switch is pressed twice | Pressing Blue button twice shall stop all LEDs from glowing at once. | ✅
| LLTP4 | To check if blue switch is pressed thrice | Pressing Blue button thrice shall make all LEDs glow clockwise as shown below | ✅
| |  | GREEN :arrow_right: ORANGE :arrow_right: RED :arrow_right: BLUE |  
| LLTP5 | To check if blue button is pressed four times | Pressing Blue button four times shall make all LEDs glow anti-clockwise as shown below | ✅
|  | | GREEN :arrow_right: BLUE :arrow_right: RED :arrow_right: ORANGE 

