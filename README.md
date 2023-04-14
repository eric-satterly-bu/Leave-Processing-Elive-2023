# Leave-Processing-Elive-2023

Inside of your Power Automate instance you need to select the Import drop down
Then select Import Package (Legacy)

Next Upload the ZIP file in this GIT repository

You will need to resolve 6 connections in your environment, details are below...
1.	On Premise Data Gateway – location of the CSV export from ERP reporting tool
2.	OneDrive for Business – location of the Excel file that gets created from the CSV
3.	MS Graph API – call used to populate the Excel file with CSV data
4.	Excel Online for Business – tools for working with Excel tables
5.	SharePoint – Holds two critical lists for this project
6.	Office 365 Outlook – sends email to provide information and status 

Inside of the SharePoint Online Site you create to house the calendar you need the following two lists with these fields.

List named "Staff"
  Name - Single line of text	
  Email - Single line of text	
  Initials - Single line of text	
  Employee ID - Single line of text	
  Modified - Date and Time	
  Created - Date and Time	
  Created By - Person or Group	
  Modified By - Person or Group

List named "Leave Calendar"
  Email - Single line of text	
  Display Name - Single line of text	
  Employee ID - Single line of text	
  Leave Date - Date and Time	
  Leave Type - Single line of text	
  Leave Hours - Number	
  Leave Status - Choice	
  Leave Detail ID - Number	
  Initials - Single line of text	  
  Cal Disp - Single line of text	
  Modified - Date and Time	
  Created - Date and Time	
  Created By - Person or Group	
  Modified By - Person or Group
