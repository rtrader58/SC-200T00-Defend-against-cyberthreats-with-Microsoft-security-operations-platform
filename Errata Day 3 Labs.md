# SC-200T00-Defend against cyberthreats with Microsoft's security operations platform - Errata Day 3 Labs
## Learning Path 6 - Lab 01 – Configure your Microsoft Sentinel environment (~30 Minutes)
### Exercise 1 - Configure your Microsoft Sentinel environment
Task 1: Create a Watchlist<br>
Step 18: It will take at least 10 Minutes for the Watchlist to function even though it will be listed<br>

Task 3: Configure log retention <br>
Step 7: You may get an error when changing the retention, ignore and move on <br>

## Learning Path 7 - Lab 01 – Connect logs to Microsoft Sentinel (~80 Minutes)

### Exercise 1 - Connect data to Microsoft Sentinel using data connectors

Task 2: Connect the Microsoft Defender for Cloud data connector <br>
Step 10: You may have exit the content hub and navigate back to the connector <br>

Task 3: Manage the Azure Activity data connector <br>
Step 1: Click on Content hub to navigate back to the Content hub <br>

### Exercise 2 - Connect Windows devices to Microsoft Sentinel using data connectors

Task 1: Create a Windows Virtual Machine in Azure <br>
Step 17: You may have to click See all sizes then search for D2s_v3  <br>
Availability Options - Set to No insfrastructure redundancy required <br>
Step 20: If there is no option to check the box you have an on premise linsence skip to next step  <br>

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
