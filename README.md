Notes : 
•	created the objects and fields as described 
•	set the address field as a formula 
•	Enabled 'Enhanced Profile User Interface'
Here : https://orgfarm-a3eba06fd0-dev-ed.develop.lightning.force.com/lightning/setup/UserManagementSettings/home
•	Created Account record types busnies and person to enable Person Accounts
•	I was able to get the logic built using Flows, Apex did not seem to be required of this task 
•	I was able to pull down all files to my Visual Studio Code IDE

Get flows : 
•	sfdx force:source:retrieve --metadata Flow:Auto_Create_Release_Charge_Loan_Charge
•	sfdx force:source:retrieve --metadata Flow:Loan_Charge_Duplicate_check
•	sfdx force:source:retrieve --metadata Flow:Loan_Charge_Release_Charge_Date_alignment
Get Object: 
•	sfdx force:source:retrieve --metadata CustomObject:Loan__c
•	sfdx force:source:retrieve --metadata CustomObject:Loan_Charge__c



Crendentials: 
•	URL : https://orgfarm-a3eba06fd0-dev-ed.develop.my.salesforce.com
•	User : hassanch.hc438@agentforce.com
•	Password: Password123

•	Username	llyr@mt-finance.com.hctest



