# Task Monitor Print by UART

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

## Demo image
![image](https://user-images.githubusercontent.com/48405514/235456342-10da450d-f84f-4ff4-b04d-cb8919e308b1.png)
