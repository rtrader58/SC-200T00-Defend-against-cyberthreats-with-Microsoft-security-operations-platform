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

## Learning Path 9 - Lab 1 –Threat hunting in Microsoft Sentinel (~90 Minutes)
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





