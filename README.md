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

## Create a group in Azure AD using the portal

#### Login to Azure Portal https://portal.azure.com/ 

#### Then click on Groups icon or type group in the search bar from the home page.

![GitHub Logo](/Create-a-group-and-add-members-in-Azure-Active-Directory.jpg)

#### On Groups blade select New group

![GitHub Logo](/how-to-Create-a-group-and-add-members-in-Azure-Active-Directory-1-768x333.jpg)

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

Now lets verify that the Group has been successfully created.

![GitHub Logo](/How-to-create-a-group-and-add-members-using-Azure-Active-Directory.jpg)
