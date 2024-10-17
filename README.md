[![Latest-Version](https://img.shields.io/badge/Latest_Version-1.3-green)](https://github.com/PezzaD84/macOSLAPS/releases) ![macOS-Versions](https://img.shields.io/badge/macOS-11+-blue) ![Script-Language](https://img.shields.io/badge/Coding_Language-Bash-blue) [![Powered-by](https://img.shields.io/badge/Powered_by-SwiftDialog-red)](https://github.com/bartreardon/swiftDialog)


# JAMF LAPS UI

A GUI Interface for viewing the JAMF LAPS Password. (Credit to [@tempusthales](https://github.com/tempusthales) for the JAMF lock icons)
![Screenshot 2023-12-19 at 10 37 54](https://github.com/PezzaD84/JAMF-LAPS-UI/assets/89595349/a45a29bd-2eff-4c9b-adb6-85869665546c)
![Screenshot 2023-08-14 at 10 30 11](https://github.com/PezzaD84/JAMF-LAPS-UI/assets/89595349/ef86ecff-a6c8-4021-8efa-8aef2e58c461)

Upload the script and create a self service policy. Just input your JAMF URL and your encoded API credentials to get up and running. You can also add a Teams or Slack WebHook URL to add notifications to an admin channel. You can also add a service desk URL to create tickets based off a LAPS request.<br>[Teams WebHook Creation](https://learn.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/how-to/add-incoming-webhook?tabs=dotnet)<br>[Slack WebHook Creation](https://slack.com/intl/en-gb/help/articles/115005265063-Incoming-webhooks-for-Slack)

![Screenshot 2023-10-03 at 11 10 30](https://github.com/PezzaD84/JAMF-LAPS-UI/assets/89595349/ed2bfa60-5647-41e3-bf97-80ca888fedab)

Permissions for the API account:

**JAMF Pro Server Actions**
```
API Integrations: Create,Read,Update
Computers: Read
Users: Read
```
**JAMF Pro Server Actions**
```
Send Local Admin Password Command
Update Local Admin Password Settings
View Local Admin Password
```
