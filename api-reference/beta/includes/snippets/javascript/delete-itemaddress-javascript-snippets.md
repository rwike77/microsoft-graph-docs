---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

await client.api('/users/{userId}/profile/addresses/{id}')
	.version('beta')
	.delete();

```