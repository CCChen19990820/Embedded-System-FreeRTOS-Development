# lab2-CCChen19990820

● 走訪 pxReadyTasksLists、pxDelayedTaskList、pxOverflowDelayedTaskList，並且透過 uart4 印出所有 task control block 的資訊。  
● Create four task  
  ○Red_LED_App、Green_LED_App、Delay_App、TaskMonitor_App  
  ○TaskMonitor_App will call Taskmonitor() periodicity  
●TaskMonitor()  
  ○Traverse ReadyTaskList, DelayedTaskList, OverflowDelayedTaskList  
  ○Print TCB information by UART  
  ○Task Name、Priority(Base/actual)、Stack Pointer、Topofstack Pointer、Task State  

## Implement flow

### HackMD  
[https://hackmd.io/@E_5q7LQISpuM2vSkcJM0OQ/rkeGFqKgh
](https://hackmd.io/@E_5q7LQISpuM2vSkcJM0OQ/SymJJoFgn)

## Demo video
https://user-images.githubusercontent.com/48405514/224000585-fed0cc8b-83c4-4591-9b81-ad8049d7540d.mp4
