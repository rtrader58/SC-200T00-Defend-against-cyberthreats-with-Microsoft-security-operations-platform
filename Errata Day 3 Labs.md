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
Step 13: in addition to removing the _for also remove the -tasks and the end > Add you initials to the beginning of the name <br>

Task 2: Update a Playbook in Microsoft Sentinel <br>
Step 1: You should be in the playbook you just created not the one listed in the lab <br>
Step 11: Your changes should auto-save, but selecting Save on the command bar ensures they are applied <br>

Task 3: Create an Automation Rule <br>
Step 1: You may have to navigate to the Automation section in the left pane <br>
Step 3: Choose Standard Rule before entering the name <br>
Step 9: Under Actions, select Run Logic App Playbook <br>
Step 10: The play book will be the same name you created in Task 1 <br>
Step 11: Select Create <br>
Step 10: Add your initials to the Name

### Exercise 2 - Create a Scheduled Query from a template
Task 1: Create a Scheduled Query rule <br>
Step 7: Instead of typing use the copy paste method the instructor showed you <br>
Step 8: You may have to wait for the rule to show up <br>
Step 10: Add your initials to the Name <br>

Task 2: Edit your new rule <br>
Step 3: Edit the rule you created in Task 1 <br>

Task 3: Test your new rule <br>
Step 11: You may have to refresh the screen and use search <br>

### Exercise 3 - Explore Entity Behavior Analytics <br>

Task 1: Explore Entity Behavior
Step 7: Configure UEBA
Step 8: Take note the slider bar is greyed out but UEBA is turned on

Task 1: Explore Entity Behavior
Step 8: Select a rule that does not have FLGT at the beginning, you may have to select multiple rules before you have the duplicate option
Step 9: Select the rule at the top of the list. It is the one you just duplicated

### Exercise 4 - Prepare to perform simulated attacks
Task 1: Connect an On-Premises Server <br>
Step 7: Run as is <br>

### Exercise 5 - Conduct attacks
No Errata <br>

### Exercise 6 - Create Detections
Task 1: Persistence Attack Detection <br>
Step 12: Add your initials to the name > Category has been renamed to MITRE ATT&CK <br>
Step 16: Add your initials to the name <br>
Step 23: Select Standard rule >  Navigate to the automation pane to create the new rule > Add your initials to the name and choose the playbook you create earlier > select Create <br>

Task 2: Privilege Elevation Attack Detection <br>
Note: I did not get any results when running the queries <br>
Step 3: The paste with add . to the first line. Delete it and hit enter to add a the second line<br>
Step 4: The paste with add ; to the first line. Delete it and hit enter to add a the second line<br>
Step 5: The paste with add ; to the first line. Delete it and hit enter to add a the second line<br>
Step 6: The paste with add ; to the first line. Delete it and hit enter to add a the second line<br>
Step 7 - 20: because there was no data was unable to complete <br>

### Exercise 7 - Investigate Incidents
Task 1: Investigate an incident <br>
Second Step 2: Click on Assets <br>
Second Step 6: Click on Activities <br>
Second step 9: there is no Unassigned <br>
Skip the second step 10 <br>
Second step 11: Investigations <br>
Step 14 - 19: Select an Alert under Detection and Categories > Select ... and Manage alert > Change status to Resolve > Classification to True Positive - Malware  <br>

### Exercise 8 - Deploy ASIM parsers
Skip - Exercises does not run as written  <br>

### Exercise 9 - Create workbooks
Task 1: Explore workbook templates <br>
Task 2: Save and modify a workbook template <br>
Step 4: If there is no option to save - delete the Azure Activities from My workbooks<br>

Task 3 Create a Workbook <br>
Step 6: Click Apply Changes at the top of the page <br>
Step 9: Click discard Changes at the top of the page <br>
Skip Step 18 and 19 <br>

### Exercise 10 - Use Repositories in Microsoft Sentinel

Task 3: Connect Sentinel to Azure DevOps
Step 3: Add your initials

