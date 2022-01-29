# Tutorial to create a Azure Active Directory Group

## In this tutorial I will show you how to:
- Create a group in Azure AD using the portal
- Create a Security Group in Azure AD using the portal
- Add members to Azure AD Groups using the portal
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
- Group name (Mandatory field). You can give a meaning full name to the group. It will verify in the back end if that name is available or else you will have to modify the group   name.
- Group description(Optional)
- Membership type (Mandatory field)
  - Assigned (Select)
  - Dynamic User (Requires P1 licensing) 
  - Dynamic Device (Requires P1 licensing) 
  
Now click on the Create button.

![GitHub Logo](/Create-a-group-in-Azure-active-directory-768x778.jpg)
