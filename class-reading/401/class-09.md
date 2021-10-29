## Reading 9: Authorization/Authentication

1. What header(s) are used in authentication and authorization
   authentication: userName & password -> 'Basic Q2FwdGFpbjpQZmZpbmdzdG9u'
   authorization: token -> 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6IkNhcHRhaW4iLCJpYXQiOjE2MzU0ODAzMTF9.HO9txRVN44boV5mYOKMT0t1-21SZpMrwixVo8iYdeDU'

2. What is safe to put into a JWT

### Best Practices: https://curity.io/resources/learn/jwt-best-practices/

1. Used as an access Token or Time stamp\
   `Data token:` As the JWT serialized form is compact and easy to integrate in HTTP request JWT are often used as a mechanism of data interchange.
   `ID token:` Issued by an Identity Manager, on behalf of a client application, after authenticating the user. It allows the client application to get user information from the token in a safe way without the need of managing user credentials.
   `Access token:` Issued by an authorization server, on behalf of a client application, it allows the client application to access a protected resource on behalf of a user. This kind of token is used as an authentication and authorization mechanism by the client application towards the server holding the resource.

2. How are JWTs validated
   Source: https://auth0.com/docs/security/tokens/json-web-tokens/validate-json-web-tokens
   Use any existing middleware for your web framework.\

Choose a third-party library from JWT.io.\

Manually implement the checks described in specification RFC 7519 > 7.2 Validating a JWT.\

RBAC: Role Based Access Control: Role-based access controls help to enforce access and entitlement policies for any organization.
User Roles: User Roles are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.\
JWT Token: JSON web token (JWT), pronounced "jot", is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. Again, JWT is a standard, meaning that all JWTs are tokens, but not all tokens are JWTs.

Sources:
https://www.bbva.com/en/json-web-tokens-jwt-how-to-use-them-safely/  
https://auth0.com/docs/security/tokens/json-web-tokens/validate-json-web-token  
https://www.imprivata.com/role-based-provisioning?gclid=Cj0KCQjwt-6LBhDlARIsAIPRQcKTJ0aN5ECjIXtT25zzpIi05o0N7prO2fmr2sc6Ua9GqZvqWecwOv8aAt6PEALw_wcB  
https://central.smarsh.com/s/article/What-are-User-Roles  
https://auth0.com/docs/security/tokens/json-web-tokens
