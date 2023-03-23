# MultiTasking
○ Two tasks: one for LED controlling, the other for Button handling.  
○ Using Inter-Task Communication (ITC) mechanism.  

● LED-task will have two states (S1, S2)  
○ S1: ( Red-Green-LED turn )  
First, only Green LED lights up for 2 seconds, and then only Red LED lights up for 2 seconds, and then switches back to the Green LED, then Red, and so on.
○ S2: ( Orange-LED )  
Only ORANGE LED is blinking (1 second ON, 1 second OFF, …).  

## main function
The main program code is in [lab_1/Core/Src/main.c](https://github.com/CCChen19990820/Embedded-System-FreeRTOS-Development/blob/main/lab_1/Core/Src/main.c).  
Using two tasks for LED control and button control respectively.  
The queue implementation receives messages and triggers transitions.  

## Demo video
https://user-images.githubusercontent.com/48405514/224000585-fed0cc8b-83c4-4591-9b81-ad8049d7540d.mp4

## Implement flow

### step1 
因為是透過FreeRTOS來實做所以要先在main.c
```
#include "FreeRTOS.h"
#include "task.h"
```

