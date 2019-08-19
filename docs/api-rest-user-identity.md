---
id: api-rest-user-idenity
title: User identity
---

Returns the minimum data to identify a user.

## Facts.

| Attribute | Value                                                           |
|----------------|------------------------------------------------------------|
| url            | `https://www.moneybuton.com/api/v1/auth/user_identity`     |
| http verb      | `GET`                                                      |
| Required scope | `auth.user_identity:read`


## Response

``` json
{
	"data": {
		"id": "75101",
		"type": "user_identities",
		"attributes": {
			"id": "75101",
			"name": "John Doe"
		}
	},
	"jsonapi": {
		"version": "1.0"
	}
}
```