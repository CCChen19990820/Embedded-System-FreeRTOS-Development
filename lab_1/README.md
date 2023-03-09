# MultiTasking
○ Two tasks: one for LED controlling, the other for Button handling.  
○ Using Inter-Task Communication (ITC) mechanism.  

● LED-task will have two states (S1, S2)  
○ S1: ( 紅綠LED輪流 )  
First, only Green LED lights up for 2 seconds, and then only Red LED lights up for 2 seconds, and then switches back to the Green LED, then Red, and so on.
○ S2: ( 橘色LED )  
Only ORANGE LED is blinking (1 second ON, 1 second OFF, …).  
