---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const itemPhone = {
  displayName: "displayName-value",
  type: "type-value",
  number: "number-value"
};

let res = await client.api('/me/profile/phones')
	.version('beta')
	.post(itemPhone);

```