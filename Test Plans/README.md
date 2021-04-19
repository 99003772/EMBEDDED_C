# High Level Test Plan

| **SL No** | **TEST_ID**                                              | **Testing Function** | **Exp IN**  | **Exp OUT**    |**SL No**  |    
|-----------|----------------------------------------------------------|----------------------|-------------|----------------|-----------|
|1 | HLR_1 | Power Window | Pressing Button 1 and 2 for Door Window movement control.|	Door Window moves according to the switch pressed.|	1 |
|2 | HLR_2 |	Sunroof Control |	Pressing push button for sunroof window movement. |	Open/ close of sunroof based on button press. |  	2 |


# Low Level Test Plan

| **SL No** | **TEST_ID**                                              | **Testing Function** | **Exp IN**  | **Exp OUT**    |**SL No**  |    
|-----------|----------------------------------------------------------|----------------------|-------------|----------------|-----------|
| 1 |	LLR_1 |	Power Window |	When the input is 1 (button 1) i.e. when switch1 is pressed. |	The Green LED will glow i.e. the GPIO pin 13 will be set and GPIO pin 14 will be reset. |	1 |
| 2 |	LLR_2 |	Power Window |	When the input is 1 (button 2) i.e. when switch2 is pressed. | The Red LED will glow i.e. the GPIO pin 14 will be set and GPIO pin 13 will be reset. |	2 |
| 3 |	LLR_3 |	Power Window |	When the input is 1,1 (button 1, button 2) i.e. when both switch1, switch2 is pressed. |	No LED will glow i.e. the GPIO pin 13 and GPIO 14 will be reset. |	3 |
