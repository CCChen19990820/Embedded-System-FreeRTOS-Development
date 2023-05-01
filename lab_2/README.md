# lab2-CCChen19990820

● 走訪 pxReadyTasksLists、pxDelayedTaskList、pxOverflowDelayedTaskList，並且透過 uart4 印出所有 task control block 的資訊。  
● Create four task  
  ○Red_LED_App、Green_LED_App、Delay_App、TaskMonitor_App  
  ○TaskMonitor_App will call Taskmonitor() periodicity  
●TaskMonitor()  
  ○Traverse ReadyTaskList, DelayedTaskList, OverflowDelayedTaskList  
  ○Print TCB information by UART  
  ○Task Name、Priority(Base/actual)、Stack Pointer、Topofstack Pointer、Task State  
