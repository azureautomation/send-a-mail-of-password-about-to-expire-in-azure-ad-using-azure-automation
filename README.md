Send a mail of password about to expire in Azure AD using Azure Automation
==========================================================================

            

 


    This Azure Automation runbook looks up a user in Azure active direcotry and determines if their

    password is about to expire. If it is, it can optionally send an email to the user. You need to

import the MSOnline module from the Automation module gallery. If no user is specified, all users
    are looked up.

    It is required to set up a credential called AzureADCredential in the Automation assets store.
    This credential is used to authenticate against Azure AD to look up the user. You can pass
    in a different credential name if needed.

    If you are going to send an email to the user, a credential called O365Credential is required
    to be set up in the Automation assets store. This is the mail account that will send the email
    to the user. You can pass in a different credential name if needed.


** *** *

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
