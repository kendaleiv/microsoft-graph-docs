---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.PersonalContacts

$params = @{
	ParentFolderId = "parentFolderId-value"
	Birthday = [System.DateTime]::Parse("datetime-value")
	FileAs = "fileAs-value"
	DisplayName = "displayName-value"
	GivenName = "givenName-value"
	Initials = "initials-value"
}

New-MgUserContactFolderContact -UserId $userId -ContactFolderId $contactFolderId -BodyParameter $params

```