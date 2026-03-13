# SC-200T00-Defend against cyberthreats with Microsoft's security operations platform - Errata Day 3 Labs
## Learning Path 7 - Lab 01 – Configure your Microsoft Sentinel environment (~30 Minutes)
### Exercise 1 - Configure your Microsoft Sentinel environment
Task 4: Create a Watchlist<br>
Step 18: It will take at least 10 Minutes for the Watchlist to function even though it will be listed<br>

Task 5: Create a Threat Indicator <br>
#### Note you may not be able to complete this task.  Threat indicators are being move from Sentinel to Microsoft Defender XDR. 
#### If you see the following image in step 1 you will not be able to complete the task
![Example image](Threat.jpg) <br>

## Learning Path 8 - Lab 01 – Connect logs to Microsoft Sentinel (~80 Minutes) (+ 30 Minute Build Time)
#### NOTE: This lab will take at least 25 minutes to launch..... this is a good time to take a break

### Exercise 1 - Connect data to Microsoft Sentinel using data connectors
Task 2: Connect the Microsoft Defender for Cloud data connector <br>
Step 10: You may have exit the content hub and navigate back to the connector  <br>

### Exercise 2 - Connect Windows devices to Microsoft Sentinel using data connectors
Task 2: Connect an On-Premises Server to Azure <br>
Step 6:  If there appears to be no progress installing the agent, select the Cmd window and press enter <br>

Task 3: Connect an Azure Windows virtual machine <br>
Step 12:  AZWIN01 may be located in the RG-AZWIN01 resource group <br>

Task 4: Connect a non-Azure Windows Machine <br>
Step 4: WINSever may be located in the RG-AZWIN01 resource group <br>

### Exercise 3 - Connect Linux hosts to Microsoft Sentinel using data connectors
Task 2: Connect a Linux Host using the Common Event Format connector <br>
Step 6: Must log in manually copy and paste does not work - credentials are located in the Resources tab <br>
Step 26: LIN1 may be located in the RG-AZWIN01 resource group <br
Step 31: Should read connected to LIN1 not LIN2 <br>

Task 3: Connect a Linux host using the Syslog connector
Step 27: LIN2 may be located in the RG-AZWIN01 resource group <br

### Exercise 4 - Connect Defender XDR to Microsoft Sentinel using data connectors
Task 2: Connect Microsoft Sentinel and Microsoft Defender XDR  <br>
Step 13: If you close the "Your unified SIEM and XDR is ready" expand Investigations & response > select Advanced hunting <br>
