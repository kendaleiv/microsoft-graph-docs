---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Users

$params = @{
	DueDateTime = @{
		DateTime = "2020-07-25T16:00:00"
		TimeZone = "Eastern Standard Time"
	}
}

Update-MgUserTodoListTask -UserId $userId -TodoTaskListId $todoTaskListId -TodoTaskId $todoTaskId -BodyParameter $params

```