---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = ItemEmail(
	display_name = "Business Email",
	type = EmailType.Work,
)

result = await graph_client.users.by_user_id('user-id').profile.emails.by_email_id('itemEmail-id').patch(request_body = request_body)


```