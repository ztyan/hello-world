We have our Salesforce code here.
This article is intended to walk you through setting up development environment using Force.com IDE.

1.Install Eclipse

2.Install Force.com IDE
https://developer.salesforce.com/page/Force.com_IDE_Installation

3.Create a salesforce developer account
https://developer.salesforce.com/signup

4.Get code from repository
git clone https://github.com/TeamOCI/salesforce.git

5.Configure Eclipse workspace
Set it pointing to parent folder of the above created repository

6.Open force.com IDE
Go to Window->Open Perspective->Other

7.Create a new force.com project
Right click any place on left panel, then click New, finally click force.com Project
in the pop up window,
Note:
Project name must be same as your repository name
Enter your salesforce username, password, and Security token(you could get it under My settings->Personal->Reset My Security Token)

8.Git Reset
Because the salesforce is a brand new account, you need to get repository code back using
Git reset –hard
Here the code is connected to your Salesforce account.

9.Save code to your salesforce account
You just need to save the code to your account via right-click src folder, then click Force.com, and Save to Server

ok, the code is already deployed to your Salesforce code.

Refer
About how to use force.com IDE, see 
https://developer.salesforce.com/docs/atlas.en-us.eclipse.meta/eclipse/ide_about_perspective.htm
