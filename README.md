# CloudFormation Password Checker Lambda Backed Custom Resource
Verify your passwords *BEFORE* you deploy

## Description
Add this code to your favorite CFT to add password verification to the CFT.  This keeps you from accidentally typing the wrong password and needing to redeploy.

## How to use
Simply copy the main sections of the CFT into your existing CFT.  Then you'll want to create two password parameters and reference them in the Lambda callback section.  If the passwords match, the CFT will complete as normal.  If they do not, the CFT will fail out.




