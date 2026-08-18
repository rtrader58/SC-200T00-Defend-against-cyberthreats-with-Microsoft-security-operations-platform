# SC-200T00-Defend against cyberthreats with Microsoft's security operations platform - Errata Day 3 Labs

## Learning Path 7 - Lab 01 – Connect logs to Microsoft Sentinel (~80 Minutes)

### Exercise 1 - Connect data to Microsoft Sentinel using data connectors
## Note: To see the entire screen click the > to close the solution box

Task 1: Access the Microsoft Sentinel Workspace in Microsoft Defender XDR <br>
Step 4: Credentials are in the Resources tab dropdown <br>

Task 2: Connect the Microsoft Defender for Cloud data connector <br>
Step 1: Click on the Show navigation to see the menu <br>
Step 10: You may have exit the content hub and navigate back to the connector <br>

Task 3: Manage the Azure Activity data connector <br>
Step 1: Click on Content hub to navigate back to the Content hub <br>

### Exercise 2 - Connect Windows devices to Microsoft Sentinel using data connectors

Task 1: Create a Windows Virtual Machine in Azure <br>
Step 17: You may have to click See all sizes then search for D2s_v3 (I had to change to US West)<br>
Availability Options - Set to No infrastructure redundancy required <br>

Task 2: Connect an On-Premises Server to Azure <br>
Step 4: After the prompt is completely pasted press Enter <br>
Skip Step 5 <br>
Step 6:  If there appears to be no progress installing the agent, select the Cmd window and press enter <br>

Task 3: Connect an Azure Windows virtual machine <br>
Step 8: Scroll to the bottom of the screen <br>
Step 11: Click Next Resources to select the computer > Expand the Subscription to choose the Virtual Machine  <br>
Step 12: AZWIN01 may be located in the RG-AZWIN01 resource group <br>

Task 4: Connect a non-Azure Windows Machine <br>
Step 2: Select the configuration you created in the previous step

### Exercise 3 - Connect Linux hosts to Microsoft Sentinel using data connectors
Task 2: Connect a Linux Host using the Common Event Format connector <br>
Step 6: Must log in manually copy and paste does not work - credentials are located in the Resources tab <br>

### Exercise 4 - Connect Defender XDR to Microsoft Sentinel using data connectors
Task 2: Connect Microsoft Sentinel and Microsoft Defender XDR  <br>
Step 13: If you close the "Your unified SIEM and XDR is ready" expand Investigations & response > select Advanced hunting <br>

## Learning Path 8 - Lab 01 – Create detections and perform investigations using Microsoft Sentinel (80 Minutes
#### NOTE: This lab will take at least 3 - 5 minutes to launch..... this is a good time to take a break

### Exercise 1 - Create a Playbook in Microsoft Sentinel
Task 1: Create a Playbook in Microsoft Sentinel <br>
Step 5: Click on Show Navigation to see the menu <br>
Step 7: Instead of typing use the copy paste method the instructor showed you <br>

Task 2: Update a Playbook in Microsoft Sentinel <br>
Step 11: Your changes should auto-save, but selecting Save on the command bar ensures they are applied <br>

Task 3: Create an Automation Rule <br>
Step 1: You may have to navigate to the Automation section in the left pane <br>
Step 3: Choose Standard Rule before entering the name <br>
Step 9: Under Actions, select Run Logic App Playbook <br>
Step 10: The play book will be the same name you created in Task 1 <br>

### Exercise 2 - Create a Scheduled Query from a template
Task 1: Create a Scheduled Query rule <br>
Step 7: Instead of typing use the copy paste method the instructor showed you <br>

### Exercise 3 - Explore Entity Behavior Analytics <br>
Task 1: Create a Scheduled Query rule <br>
Step 8: Scroll to the right to see the summary blade <br>

Task 2: Edit your new rule <br>
Step 12: Assign to your Labuser account <br>

### Exercise 4 - Explore Entity Behavior Analytics
No Errata <br>

### Exercise 5 - Prepare to perform simulated attacks
No Errata <br>

### Exercise 6 - Conduct attacks
No Errata <br>

### Exercise 7 - Create Detections
Task 1: Persistence Attack Detection <br>
Step 10: The paste with add ; to the first line. Delete it <br>
Step 11: The paste with add ; to the first line. Delete it <br>
Step 12: You may have to click on ... to see + New alert rule <br>
Step 13: Tactics has been renamed to MITRRE ATT&CK <br>

Task 2: Privilege Elevation Attack Detection <br>
Step 2: The paste with add . to the first line. Delete it <br>
Step 3: The paste with add ; to the first line. Delete it <br>
Step 4: The paste with add ; to the first line. Delete it <br>
Step 5: The paste with add ; to the first line. Delete it <br>
Step 7: There is no Tactics option <br>

### Exercise 8 - Investigate Incidents
No Errata <br>

### Exercise 9 - Deploy ASIM parsers
No Errata <br>

### Exercise 10 - Create workbooks
Task 1: Explore workbook templates <br>
Task 2: Skips steps 4 - 13 <br>

### Exercise 11 - Use Repositories in Microsoft Sentinel
Skip Task 2: Create our Azure DevOps environment <br>
