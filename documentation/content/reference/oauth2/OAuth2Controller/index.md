---
type: "class"
---

# `OAuth2Controller`

Helper for OAuth 2.0, as defined in [RFC 6749](https://datatracker.ietf.org/doc/html/rfc6749). See [`oslo/oauth2`](/reference/oauth2) for a full example.

## Constructor

```ts
function constructor(
	clientId: string,
	authorizeEndpoint: string,
	tokenEndpoint: string,
	options?: {
		redirectURI?: string;
	}
): this;
```

### Parameters

- `clientId`
- `authorizeEndpoint`
- `tokenEndpoint`
- `options`
  - `redirectURI`

## Methods

- [`createAuthorizationURL()`](ref:oauth2/OAuth2Controller)
- [`validateAuthorizationCode()`](ref:oauth2/OAuth2Controller)