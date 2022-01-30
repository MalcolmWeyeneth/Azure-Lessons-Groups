# How to create an Azure Active Directory Group

## In this tutorial I will show you how to:
- Create a group in Azure AD using the portal
- Create a Security Group in Azure AD using the portal
- Add members to Azure AD Group using the portal
- How to create a Group in Azure AD using PowerShell
- PowerShell command to get Azure AD group details
- Add member to Azure AD group using PowerShell
- Update Azure AD Groups using PowerShell
- Delete Azure AD group using PowerShell

## Create a New Group (Portal)

#### Login to Azure Portal https://portal.azure.com/ 

#### Then click on Groups icon or type group in the search bar from the home page.

![GitHub Logo](/Create-a-group-and-add-members-in-Azure-Active-Directory.jpg)

#### On Groups blade select New group

![GitHub Logo](/how-to-Create-a-group-and-add-members-in-Azure-Active-Directory-1-768x333.jpg)

## Create a Security Group (Portal)
To create the Security Group in Azure AD, You will need to follow the below steps

Select the Group type as Security from the New Group window.
- Group name (Mandatory field) Lets name the Group "TSinfoGroup"
- Group description(Optional)
- Membership type (Mandatory field)
  - Assigned Select this option from the drop down
  - Dynamic User (Requires P1 licensing) 
  - Dynamic Device (Requires P1 licensing) 
  

![GitHub Logo](/Create-a-group-in-Azure-active-directory-768x778.jpg)

Now click on the Create button.

The newly created Group should now appear in the "All Groups" blade if successfully created.

![GitHub Logo](/How-to-create-a-group-and-add-members-using-Azure-Active-Directory.jpg)

## Add members to Azure AD Groups
Now we can add the members to the group TsinfoGroup we just created.

Click on the group name -> Select the Members link from the left and then click on the Add Members button. (If there are no users watch my tutorial on creating a New User)

![GitHub Logo](/add-members.jpg)

Now on the Add members window, Search for the users need to be added.Then click on Select button.

![GitHub Logo](/add_user_member.jpg)

Now you can see Member added successfully.

![GitHub Logo](/add_user_member_added.jpg)

So you now have the knowledge on how to setup a group and how to add a memeber to the group using the Azure portal, pretty easy!! 
