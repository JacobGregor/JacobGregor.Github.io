## Write the following steps in the correct order:\

1. Register your application to get a client_id and client_secret\
2. Ask the client if they want to sign in via a third party\
3. Redirect to a third party authentication endpoint\
4. Receive authorization code\
5. Make a request to the access token endpoint\
6. Receive access token\
7. Make a request to a third-party API endpoint\

## What can you do with an authorization code?\

->  
The Authorization Code grant type is used by confidential and public clients to exchange an authorization code for an access token./

After the user returns to the client via the redirect URL, the application will get the authorization code from the URL and use it to request an access token./

### What can you do with an access token?\

-> Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data./

## What’s a benefit of using OAuth instead of your own basic authentication?\

'Advantages of OAuth 2.0

This flexible protocol relies on SSL (Secure Sockets Layer) to ensure data between the web server and browsers remain private.
SSL uses cryptography industry protocols to keep data safe.
It uses tokenization to give limited access to the user's data. For example, instead of storing credit card information on Amazon’s web site, the credit card number, security code and consumer name are each given “token” IDs. The tokens are given to the merchant, not the actual data.
It is easy to implement and provides strong authentication. In addition to the two-factor authentication, tokens can be revoked if necessary (ie, suspicious activity).
Uses single sign on
Advantage of a Single Sign On Systems (SSO)

SSO enables users to use one set of login credentials to access multiple applications. The average person maintained 27 passwords in 2016, and 30% of help desk calls are related to password reset issues. When logins become cumbersome and users get frustrated, productivity and morale go down. Enabling users to use SSO through OAuth 2.0 eases access, mitigates risks and gives users control over where their data is shared.

The bottom line is that this standard should be utilized in all apps to provide ease of use and appropriate security. Keeping your users' data safe should always remain top priority.' -> Taken from OAuth Website.\

## Term:

### Client ID: The Client ID (cid) is a unique identifier for a browser\

### Client Secret: A client secret is a secret known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors.\

### Authentication Endpoint: The end-point at which you get your Authentication access.

### Access Token Endpoint: Where apps make a request to get a special access token unique to the user.\

### API Endpoint: A point where ther API connects to the end-point.

### Authorization Code: The Authorization Code grant type is used by confidential and public clients to exchange an authorization code for an access token.\

### Access Token: Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data./

Sources:\

- https://www.oauth.com/oauth2-servers/access-tokens/\
- https://oauth.net/2/grant-types/authorization-code/\
- https://www.owox.com/blog/use-cases/google-analytics-client-id/\
- https://auth0.com/docs/configure/applications\
