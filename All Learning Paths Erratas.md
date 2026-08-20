# SC-200T00-Defend against cyberthreats with Microsoft's security operations platform - Errata All Learning Paths and Days
# SC-200T00-Defend against cyberthreats with Microsoft's security operations platform - Errata Day 1 Labs
# Ensure you choose "SAVE" if you do not finish all 4 labs - so as not to lose your work
## Learning Path 1 - Lab 1 - Explore Microsoft Defender XDR (~30 Minutes)
### Exercise 1 - Explore Microsoft Defender XDR

Task 2: Apply Microsoft Defender for Office 365 preset security policies<br>
#### Note: If presented with Sign in to Microsoft Edge select No, thanks<br>

Step 7: If needed click Show Navigation to see the navigation menu <br>
Step 12:  Your Domain name can be found in the Resources dropdown listed as Tenant Name <br>


Task 3: Preparing the Microsoft Defender XDR workspace <br>
The preparing the new space took oveer 15 minutes <br>
After step 2 while waiting for the workspace to be provisioned you can move on to Learning path 2, after finishing the simulations you can return to Learning Path 1 to finish the steps <br>
Step 3: You need to close the browser first the re-open to see the desired results.<br>

## Learning Path 2 - Lab 1 - Explore Microsoft Security Copilot (~45 Minutes)
### Exercise 1 - Explore Microsoft Security Copilot

TNo Errata

## Learning Path 3 - Mitigate threats using Microsoft Purview (~15 Minutes)
### Exercise 1 - Explore Microsoft Purview Audit logs 
Task 1: Enable Purview Audit logs<br>
Step 6: From the navigation menu, select More resources<br>
Step 9: click Get started<br>
Step 12:  It could take up to 60 minutes for the recordings to start. The blue bar will not disappear until it has started.  You can move on to the next lab. <br>

## Learning Path 4 - Lab 1 - Deploy Microsoft Defender for Endpoint (~60 Minutes)
### Exercise 1 - Deploy Microsoft Defender for Endpoint

Before starting the lab, if you did not close the browser after Learning Path Lab 1 step 2, close the browser <br> 

Task 2: Onboard a Device <br> 
Step 3: Should read ensure Windows 10 and 11 are selected in the Step 1 dropdown box > select standard in the Connectivity type dropdown <br> 

Task 3: Configure Roles <br> 
Step 13: If you get an error creating cancel and redo the steps <br> 

### Exercise 2 - Mitigate Attacks with Microsoft Defender for Endpoint

Task 1: Verify Device onboarding<br>
Step 2: \The computer name is Base23B not Win1 <br>
Step 3: You may need to log out, close and reopen the browser and log back in to see Endpoints <br>
Step 4: Should read ensure Windows 10 and 11 are selected in the Step 1 dropdown box <br>

Task 2: Investigate alerts and incidents <br>
Step 2: It took ~5 minutes for the alert to populate <br>

# SC-200T00-Defend against cyberthreats with Microsoft's security operations platform - Errata Day 2 Labs

## Learning Path 5 - Lab 01 – Create queries for Microsoft Sentinel using Kusto Query Language (KQL) (~45 Minutes)
### Exercise 1 - Task 1: Query log data with KQL in Defender XDR 
Task 1: Prepare the KQL testing area <br>
Step 3: Enter the TAP not the Passowd <br>
Step 4: If needed click Show Navigation to see the navigation menu <br>

## Learning Path 6 - Lab 01 – Configure your Microsoft Sentinel environment (~30 Minutes)
### Exercise 1 - Configure your Microsoft Sentinel environment
Task 1: Create a Watchlist<br>
Step 18: It will take at least 10 Minutes for the Watchlist to function even though it will be listed<br>

Task 3: Configure log retention <br>
Step 7: You may get an error when changing the retention, ignore and move on <br>

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

### Exercise 10 - Use Repositories in Microsoft Sentinel

Task 3: Connect Sentinel to Azure DevOps <br>
Step 3: Add your initials <br>

# SC-200T00-Defend against cyberthreats with Microsoft's security operations platform - Errata Day 4 Labs

## Learning Path 8 - Lab 01 – Create detections and perform investigations using Microsoft Sentinel (~180 Minutes)
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
Step 10: Add your initials to the Name <br>

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

Task 1: Explore Entity Behavior <br>
Step 7: Configure UEBA <br>
Step 8: Take note the slider bar is greyed out but UEBA is turned on <br>

Task 1: Explore Entity Behavior <br>
Step 8: Select a rule that does not have FLGT at the beginning, you may have to select multiple rules before you have the duplicate option <br>
Step 9: Select the rule at the top of the list. It is the one you just duplicated <br>

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
Task 1: Deploy the Registry Schema ASIM parsers <br>
Step 8: Click the the down arrow next to Shema choose Function <br>
Skip step 12 and 13 <br>

### Exercise 9 - Create workbooks
Task 1: Explore workbook templates <br>
Task 2: Save and modify a workbook template <br>
Step 4: If there is no option to save - delete the Azure Activities from My workbooks<br>

Task 3 Create a Workbook <br>
Step 6: Click Apply Changes at the top of the page <br>
Step 9: Click discard Changes at the top of the page <br>
Skip Step 18 and 19 <br>

## Learning Path 9 - Lab 1 –Threat hunting in Microsoft Sentinel (~75 Minutes)

### Exercise 1 - Perform Threat Hunting with Microsoft Sentinel in the Microsoft Defender portal
Prerequisite task 1: Connect an On-Premises Server <br>
After step 7: Restart WINServer <br>

Task 1: Create a hunting query <br>
Step 7: In notepad remove the '''KQL and the last line that start with >**Note before pasting <br> 
Step 3: Search for -file c2.ps1 <br>
Step 6: Add your initials to the name <br>
Step 14: Search for the Incident you created in step 6 <br>

Task 2: Hunt with Microsoft Sentinel graph 
No errata <br>

Task 3: Create a Data lake KQL job <br>
Step 2: Use the dropdown arrow next to Create job <br>
Step 18: It took almost 10 minutes before the red ripple underline to go away - move on and come back to this step later<br>

Task 4: Create a hunt that combines multiple queries into a MITRE tactic <br>
Step 18: The run button is located at the top right of the screen <br>

### Exercise 2 - Threat Hunting using Data lake Notebooks in Microsoft Sentinel
Note: This exercise cannot be completed as it requires you to have a Github account <br>
To create the Github account requires MFA and you do not have access to the email <br>

## Learning Path 9 - Lab 01 – Create detections and perform investigations using Microsoft Sentinel
#### NOTE: This lab will take at least 30 minutes to launch..... this is a good time to take a break

### Exercise 1 - Modify a Microsoft Security rule
 No Errata <br>

### Exercise 2 - Create a Playbook in Microsoft Sentinel
Task 1: Create a Playbook in Microsoft Sentinel <br>
Step 14: Remove -tasks from the end of the name <br>

Task 2: Update a Playbook in Microsoft Sentinel <br>
Step 1: The name is Defender_XDR_Ransomware_Playbook_SecOps <br>
Skip step 7 as you are already in edit mode <br>

### Exercise 3 - Create a Scheduled Query from a template
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

## Learning Path 10 - Lab 1 –Threat hunting in Microsoft Sentinel
#### NOTE: This lab will take at least 30 minutes to launch..... this is a good time to take a break
### Exercise 1 - Perform Threat Hunting in Microsoft Sentinel
Prerequisite task 1: Connect an On-Premises Server <br>
After step 8: Restart WINServer <br>

Task 1: Create a hunting query <br>
Step 20: Paste into notepad first <br>
Step 24: Select PowerShell Hunt, Right click and select run <br>
Skip steps: 26 and 27 <br>

Task 2: Create an NRT query rule <br>
Step 3: Tactics has been renamed to MITRRE ATT&CK <br>
Step 5: Paste into Notepad first <br>

Task 3: Create a Search job <br>
Step 5: Name the table remove the - from the name <br>

### Exercise 2 - Threat Hunting using Notebooks with Microsoft Sentinel
No errata <br>
