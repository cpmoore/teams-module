Please use the official Microsoft PowerShell module, this is no longer maintained!


# teams-module
PowerShell module for Microsoft Teams using the rest API that are not documented from api.teams.skype.com.


# Requirements;
AzureAD PowerShell module


PowerShell 4.0 or higher


A Microsoft Teams license


# Usage:
import-module teams_v2.psm1


limited to 250 teams


connect-teamsservice -user admin@contoso.com -tenant contoso.onmicrosoft.com


get-Team


add-Team 


remove-Team


add-TeamMember


remove-TeamMember


get-TeamMember


convert-TeamMemberToOwner


convert-TeamOwnerToMember


get-TeamChannel


Add-TeamChannel


Remove-TeamChannel


Convert-GroupToTeam
